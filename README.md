# Auto Focus Vuforia

Auto-focus Script for ARCamera in Vuforia SDK

### How to Use?

- First, you can download or copy-paste the code to your project
- Then you can add CameraFocusController.cs to ARCamera Object

// code from  Vuforia Developer Library
 // https://library.vuforia.com/articles/Solution/Camera-Focus-Modes
 void Start() {    
  var vuforia = VuforiaARController.Instance;    
  vuforia.RegisterVuforiaStartedCallback(OnVuforiaStarted);    
  vuforia.RegisterOnPauseCallback(OnPaused);
 }  
