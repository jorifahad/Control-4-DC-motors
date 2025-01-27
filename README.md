
# Smart DC Motor Control System Using Arduino

## Project Description
This project demonstrates how to control four DC motors using an Arduino board and L293D motor driver ICs. The system is programmed to perform specific movements, including forward motion, backward motion, and alternating left-right rotations. The project provides precise speed and direction control, making it suitable for robotics and automation tasks.

![image](https://github.com/user-attachments/assets/f733c66a-ad2f-4064-a20e-ec81f46a2b99)

---

## Features
- **Multi-Motor Control**: Independently control up to four DC motors.
- **Programmed Movements**:
  - Move forward for 30 seconds.
  - Move backward for 1 minute.
  - Alternate left-right rotation for 1 minute.
- **Customizable**: Modify timing, speed, and motion logic through simple code changes.
- **Efficient Control**: Uses PWM for speed control and direction pins for precise motor movement.

---

## Components Required
1. **Arduino Uno**: Main microcontroller board.
2. **4 DC Motors**: For motion control.
3. **2 L293D Motor Driver ICs**: To manage motor power and direction.
4. **9V Battery**: Power source for the motors.
5. **Breadboard**: For wiring connections.
6. **Connecting Wires**: To establish electrical connections.
7. **USB Cable**: For uploading code to Arduino.

---


## Key Code Functions
- `moveForward()`: Moves all motors forward.
- `moveBackward()`: Moves all motors backward.
- `turnRight()`: Turns the system to the right.
- `turnLeft()`: Turns the system to the left.
- `stopMotors()`: Stops all motors.
- `alternateRightLeft()`: Alternates between turning right and left.

---


## Applications
This system can be used in:
- Robotics projects.
- Automated vehicles.
- Motion control systems.
- Prototyping for robotics research.

