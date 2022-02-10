# CameraAppDemo
My first camera app by Camera2 library

This app is based on the following project
https://github.com/Jiankai-Sun/Android-Camera2-API-Example/blob/master/app/src/main/java/com/jack/mainactivity/MainActivity.java
And take reference from the stackOverFlow answer 
https://stackoverflow.com/questions/43460985/android-camera2-preview-occasionally-rotated-by-90-degrees
The Orientation issue has not been resolved, hence this project is still under development

1. Add permission on AndroidManifest.xml for camera2
2. Check if the library is deperated, replace with correct one
3. Add the function to onResume(), onSurfaceTextureSizeChanged, openCamera()
4. In the UI (res/layout/activity_main.xml) add one button plus TextureView

Would update the project once I find the solution
