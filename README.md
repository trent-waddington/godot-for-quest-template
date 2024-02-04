# godot-for-quest-template
This is my attempt to make a Godot project template that builds natively for all Quest headsets and provides an interface to the features exclusively available to native Quest development.

Looking for help!

HOW TO

1. Clone or download and unzip this project
2. Open in Godot (you can try Importing the zip? I don't know)
3. Project -> Project Settings -> Config and rename it to something uniquely you right now
4. Project -> Install Android Build Template -> Install
5. AssetLib -> enter "xr" into the box -> select Godot OpenXR Vendors plugin -> Download
6. A box will pop up with lots of files. Just ignore it all and press Install.
7. Reconnect your Quest headset to your PC because it has inevitably lost connection again. This is adb voodoo and for me it's usually enough to wake up the headset, and run: adb connect 192.168.1.xxx:5555 but it's always something.
8. Hover over the fourth button on the toolbar in the top right corner. Between the STOP button and the SCENE button. That's the Remote Debug button.
9. Click it because it sometimes needs to be clicked. Select your headset if you see it.
10. The export begins. You will see gradle stuff. If you get errors here, something went wrong. You have fun with that.
11. Your headset should pop up a window that says you don't have the plugins installed. (NO IT SHOULDN'T - if you did steps 5 and 6)
12. For me this is the end of the story.. I get darkness. If I look up and to the left I can catch a glimpse of a PAUSE button. Mocking me.
    

