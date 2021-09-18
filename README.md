# bikeStabilizer

<em>The initial setup of the MPU-6050 sensor was taken from [https://github.com/jrowberg/i2cdevlib]. The license for use of this code is included in the program itself as instructed by the creator.</em>

This project used an MPU-6050 sensor to act as a safety measure in the use of a dirt bike. The sensor is used to constantly monitor the acceleration and roll of the dirt bike. If these measurements exceed a threshold set in the program, it immediately outputs an analog signal which is wired to the dirt bike, turning it off.
