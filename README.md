# Ship-Detection
<img src="https://github.com/ethanhou99/Ship-Detection/blob/master/images/Team_logo_v2.png" />

## Introduction
- This project is designed for the Airbus Ship Detection Challenge(reference link:https://www.kaggle.com/c/airbus-ship-detection)

## Backstory
- Shipping traffic is growing fast. More ships increase the chances of infractions at sea like environmentally devastating ship accidents, piracy, illegal fishing, drug trafficking, and illegal cargo movement. This has compelled many organizations, from environmental protection agencies to insurance companies and national government authorities, to have a closer watch over the open seas.

## Method and Examples

### - Block Diagram
<img src="https://github.com/ethanhou99/Ship-Detection/blob/master/images/block_diagram.png" />

- This project can be seprated into two parts: "Object Detection & User Input". The model will be trained using thousands of training set and be frozen after training. While user using the designed application, a set of photos will be inputed. Then the application will call the trained model and output the ships' directions. 
  
### - Current Result(reat-time update)
<img src="https://github.com/ethanhou99/Ship-Detection/blob/master/images/current_result.png" />

- Current application can detect the sea and other objects. For the next step, we will add some complex training set to improve the noise-process-ability.

### - Application Interface
![preview](https://github.com/ethanhou99/Ship-Detection/blob/master/images/Application_demo.gif)

## Keynote
- Use Unet to detect ship in a Satellite Picture dataset offered by Kaggle. 
- Methods are specially modified to fit the time limit on Kaggle notebook.

