# Hardware Notes

## Main Components
- STM32 development board
- PCA9685 servo driver
- 12 servos
- external power supply
- quadruped robot structure

## Control Architecture
The STM32 board is used as the main controller.  
The PCA9685 is used to generate control signals for the servos.

## Main Hardware Tasks
- servo signal control
- I2C communication with PCA9685
- power distribution
- wiring and connection verification
- mechanical assembly support

## Important Considerations
The robot performance depends not only on the code, but also on:
- servo calibration
- joint direction
- wiring reliability
- power stability
- mechanical balance

## Notes
This project required repeated testing to match the software control with the real hardware behavior of the robot.
