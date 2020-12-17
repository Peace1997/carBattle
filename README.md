# carBattle
## Requirements
- Python3
- Pytorch
- Box2d
- OpenAI gym
## version
1. **Simulation environment construction：** In the barrier-free environment without formal training, the car uses laser (isosceles triangle simulation) to complete a simple battle.

## Introduction
#### simulation environment 
| parameter   |  description  |
| ----  | ----  |
| wall | size: 8 x 6 |
| car | size: 0.6 x 0.42 |
| laser | shape: Isosceles triangle ; size:（botom: 0.32 height: 4） |
| gun | size:0.2 x 0.02 |
| sensor | number:4 ; size: 0.02 x 0.02  |
| wheel | number:4 ; size: 0.1 x 0.06 | 
![enviroment](https://github.com/Peace1997/carBattle/tree/dev/img/enviroment.gif)