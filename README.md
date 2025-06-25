# 🤖 Obstacle Avoiding Robot

An autonomous robot built using Arduino Uno that  detects and avoids obstacles using an ultrasonic sensor and L293D motor driver. This robot demonstrates basic navigation capabilities without human control by measuring distances .



## 🛠️ Components Used

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- L293D Motor Driver
- Gear Motors (2×)
- 5V Battery or Power Bank
- Breadboard and Jumper Wires



## 💡 How It Works

- The ultrasonic sensor measures the distance to obstacles ahead.
- If an object is detected closer than 20 cm, the robot stops and turns right.
- Otherwise, it moves forward.
- All motor actions are controlled using the L293D motor driver.
