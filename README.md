# Python-Trucks-Detection
Based on lbeaucourt/Object-detection

Apply tensorflow object detection on m3u8 input video stream.

# To use it:

- Requirements: Python3.9

- Clone repo in your working directory

- Install the requirments.txt file 

- Run the run.cmd file or execute the following from the commandline
> python.exe my-object-detection.py ...~~

All possible arguments are:

```
-n (--num-frames): type=int, default=0: # of frames to loop over for FPS test

-d (--display), type=int, default=0: Whether or not frames should be displayed

-f (--fullscreen), type=int, default=0: Enable full screen

-o (--output), type=int, default=0: Whether or not modified videos shall be writen

-on (--output-name), type=str, default="output": Name of the output video file

-I (--input-device), type=int, default=0: Device number input

-i (--input-videos), type=str, default="": Path to videos input, overwrite device input if used

-w (--num-workers), type=int, default=2: Number of workers

-q-size (--queue-size), type=int, default=5: Size of the queue

-l (--logger-debug), type=int, default=0: Print logger debug

```

![alt text](https://github.com/TomerAdmon/Python-Trucks-Detection/blob/master/Screenshot_2.png)


### notes
- FPS configuration is set to <5 FPS, changes could be made in the app_utils.py file
- Output is set not to mark cars or traffic lights 
