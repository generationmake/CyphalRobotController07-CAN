# OpenCyphalRobotController07
Main controller board for the T07 robot platform and similar robots with a Raspberry Pi Pico to connect via CAN using OpenCyphal and UCANPHY Micro 

## features

- power supply for the whole system
  - 5 V for the cyphal network and embedded board (Raspberry Pi or Beagle Bone Black)
  - switchable output of battery voltage to supply additional hardware
  - Input voltage up to 25 V
  - measurement of input voltage and current with TI INA226
- control 2 DC motors
  - 2 quad encoders for motors
  - emergency stop
- 3 ultra sonic sensors HC-SR04
- 9 axis IMU Bosch BNO055 via I2C
- serial port for optional GNSS
- CAN with Cyphal support
