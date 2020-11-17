# Auto Focus Vuforia Unity Game Engine

Auto-focus Script for ARCamera in Vuforia SDK + Unity Game Engine

### What is this?
to set the auto focus camera in vuforia ar sdk

### How to Use?

- First, you can download or copy-paste the code to your project
- Then you can add CameraFocusController.cs to ARCamera Object

### Sneakpeek

*Handler*
```csharp
void Start() {    
  var vuforia = VuforiaARController.Instance;    
  vuforia.RegisterVuforiaStartedCallback(OnVuforiaStarted);    
  vuforia.RegisterOnPauseCallback(OnPaused);
 }  
```
*Vuforia Started Handler and call Camera Device Mode to Auto Focus*
```csharp
private void OnVuforiaStarted() {    
  CameraDevice.Instance.SetFocusMode(
      CameraDevice.FocusMode.FOCUS_MODE_CONTINUOUSAUTO);
 }
```
