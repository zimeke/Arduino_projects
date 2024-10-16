# ClapCar

This project demonstrates how to control a small car using sound detection (clapping). By detecting different numbers of claps, the car can rotate or move forward. The use of LEDs provides visual feedback on the car’s status, making it easier to understand its current state.

![ClapCar](https://github.com/user-attachments/assets/ca8598f3-e6a3-466f-a0a4-00f13d131f96)


The car responds to claps as follows:
* One clap: starts rotating to the right
* Two claps: starts rotating to the left
* Three claps: moves forward

If the car is moving (rotating or moving forward), a single clap will stop it.

The car’s movement is indicated by LEDs:
* Red LED: the car is stationary
* Green LED: the car is moving
* Yellow LED: indicates when a clap is detected

![ClapCar_JPG](https://github.com/user-attachments/assets/a3855078-e7fa-45bf-afe0-d10d0ca9afbf)

## Components Used
* Arduino Uno Rev3
* Motor Driver (L298N)
* 2 x DC Motor (JGA25-370; 12V 50rpm variant)
* Analog Sound Sensor
* 5.5mm DC Male Jack Connector
* 3 x 1kOhm Resistor
* 2 x 4AA Battery Holder
* Chassis: A custom-built frame where the components are mounted on a wooden board, along with a support wheel for stability
