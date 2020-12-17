# carBattle
## Requirements
- Python3
- Pytorch
- Box2d
- OpenAI gym
## version
1. **Simulation environment construction:** In the barrier-free environment without formal training, the car uses laser (isosceles triangle simulation) to complete a simple battle.

## Introduction
There are two small cars, red and blue. The cars move within the range of the wall. When the distance between the cars is less than 4, the attack can be carried out. The attack method is laser(simulated based on the actual laser transmitter).There are four sensor on the two cars. When the laser collides with the sensor and the car collides, the health will be reduced.When the HP of any car is 0,it will restart.
## simulation environment 
![enviroment](imgs/enviroment.gif)
| parameter   |  description  |
| ----  | ----  |
| wall | number:4 ; size: 8 x 0.2 & 6 x 0.2 |
| car | size: 0.6 x 0.42 |
| laser | shape: Isosceles triangle ; size:（botom: 0.32 height: 4） |
| gun | size:0.2 x 0.02 |
| sensor | number:4 ; size: 0.02 x 0.02 |
| wheel | number:4 ; size: 0.1 x 0.06 |

## Reference:
[1] Box2d 手册：https://github.com/pybox2d/pybox2d/wiki/manual
[2] JachinShen：https://github.com/JachinShen/supreme-invention


