# Auto Focus Vuforia Unity Game Engine

Auto-focus Script for ARCamera in Vuforia SDK + Unity Game Engine

### How to Use?

- First, you can download or copy-paste the code to your project
- Then you can add CameraFocusController.cs to ARCamera Object

### Sneakpeek
```csharp
void Start() {    
  var vuforia = VuforiaARController.Instance;    
  vuforia.RegisterVuforiaStartedCallback(OnVuforiaStarted);    
  vuforia.RegisterOnPauseCallback(OnPaused);
 }  
```
