# shiva_plugin_mfi
A plugin that lets you use Apple-certified MFI controllers with your ShiVa games

## How to use
The plugin comes as a drop-in STE, which you can import into your existing ShiVa project. After you have imported the STE, add the Plugin to your game’s plugin tab. The MFI AI is merely an example to show you how to access handlers. In general, MFI controllers use nJoypad 1 to 4 (because 0 is always covered by the iOS gyro), rely on the Xbox360 input constants and use the default ShiVa joypad handlers. The only additional handler “onMFINotification” can be used to detect (dis)connection events and errors.

## Demo
The demo project is adapted from the ShiVa 2.0 samples “gamepad tester”. If you are done testing, simply close down/stop the game.

A youtube video of the demo can be found here: https://www.youtube.com/watch?v=1RZb2os34BI
