# Description
This is an example project to explore matrix mathematics as it applys to a four motor, underwater, remote operated vehicle.

By configuring motors in a 45 degree offset arrangement like so:

/ \  
\ /

You can achieve stable movement in two dimensions, including yaw rotation about the z-axis.
This example could easily be expanded to six motors allowing for three dimensional movement, with pitch about the x-axis or tilt about the y-axis rotation.
I leave that up to the reader as an exercise.
Further, I would challenge the reader to consider what it might take to accomplish both pitch AND tilt.

# Requirements
* Install dependencies: `pip install -r requirements.txt`
* Connect XBox 360 or other 360 driver compatible controller.
* Configure which axes control X, Y, and Yaw movement.
  * This project assumes DOWN in the Y, and RIGHT in the X are positive.
  * Configure the invert values as well to account for your controller. Alternatively, reconfigure your motors.

# Usage
`python FourMotorExample.py`

Manipulate joysticks to see resulting matrix calculations