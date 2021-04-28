# Hand-Gesture-Recognition-Based-Interactive-Gaming
![8e815900-6cc9-11eb-8fe5-684a95443875](https://user-images.githubusercontent.com/42333996/116341304-453ba280-a7fe-11eb-9a98-34975b70a65a.png)

Wouldn’t it be fun, if you could use your hand to control the car in a game? So, here we have proposed a computer vision concept to control the game with hand gestures by mapping gestures to the W, A, S, D keyboard keys.

Tested on games like: Need for Speed, GTA 5, Blur, Spiderman.

Link for video: https://drive.google.com/file/d/1Xpey_UYsxnG0eSdDodW2cWsVR_jFOMq6/view?usp=drivesdk

The code is well commented at each step and is easy to understand and implement.

## Libraries used:
• python 3.x • imutils • numpy • opencv2 • time • sklearn • ctypes

The repository includes three main python(.py) files particularly:

control.py (Code to map gesture- slope and distance with the keys)
directkeys.py (Code to interact with the keyboard keys. Reference: https://stackoverflow.com/questions/14489013/simulate-python-keypresses-for-controlling-a-game%20#%20http://www.gamespp.com/directx/directInputKeyboardScanCodes.html)
final.py (Main code to take input i.e. hand gesture using background subtraction method, find end points of hand and henceforth distance and slope using convex hull)
## Steps to run the code:
Download the zip file and unzip all in same folder. We have used PyCharm Community Edition to run the codes. You may use other python editors which support the above libraries.
Run the final.py file.
Adjust the HSV values using the track bar, so that only your hand is visible.
After that, set the Start track bar to 1.
Hurray!! You can now use your hand to control the game.

## Note:
Please use plain white or black background for more accuracy. Also, make sure the room is well lit.
You are free to modify the slope and distance values depending upon the gesture you make in control.py.
You can map more gestures with keys. Refer to: https://gist.github.com/dretax/fe37b8baf55bc30e9d63
Hope you Like it!

Thanks.
