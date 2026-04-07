# -NVIDIA-Robot-Classification-
AIM

To classify the type of autonomous robot (aerial or ground) using motion parameters such as speed and altitude.

PROCEDURE
Initialize input values: speed and altitude
Read the given motion parameters
Check the altitude value
If altitude > 0, classify as aerial robot
Otherwise, classify as ground robot
Display the result
CODE
# Input values
speed = 6        # in m/s
altitude = 15    # in meters

# Classification logic
if altitude > 0:
    robot_type = "Aerial Autonomous Robot"
else:
    robot_type = "Ground Autonomous Robot"

# Output
print("Robot Type:", robot_type)
OUTPUT

Robot Type: Aerial Autonomous Robot

RESULT

The robot is successfully classified as an Aerial Autonomous Robot based on the given altitude parameter.
