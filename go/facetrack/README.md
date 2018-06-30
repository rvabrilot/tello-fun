# Facetrack

This program enable use of an xbox360 joystick for manually controlling the tello drone and implements a facetracking function.

- Press Start to takeOff
- Press A to print battery percentage
- Press B to activate/deactivate face tracking that move the drone using a green box around any face.
- Use controls to manipulate drone 
- Press Back to Land
- Press Lt/Rt to do flips

see the code for more information (source code is the best documentation).

## How to run on Linux (Ubuntu)

- Install GO: https://golang.org/doc/install
- Install GOCV: https://github.com/hybridgroup/gocv#ubuntulinux  (use that handy makefile to compile and install opencv3)
- Install ffmpeg: ```sudo apt-get install ffmpeg ```
- Use "go get" to install other required go libraries from project gobot using something like ```go get -d -u gobot.io/x/gobot/...``` (many thanks to them)
- Follow instructions on: https://github.com/hybridgroup/gobot/tree/master/platforms/joystick to install joystick
- connect you computer to the tello's wifi
- connect joystick to you computer
- cd to program folder with a terminal and write ```go run facetrack.go model proto.txt``` to initiate
- Enjoy!    

## How to run on Windows
TO-DO    