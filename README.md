# performance_fps

Flutter plugin for calculate fps online on Android and IOS,
  its result is the same as flutter performance

## Getting Started

This project is a starting point for a Flutter
[plug-in package](https://flutter.dev/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.

#demo 

#for start
Fps.instance.registerCallBack((fps, dropCount) {
      //fps is current fps
    });
    
    
#cancel 
Fps.instance.cancel();