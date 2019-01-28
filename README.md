# Ship-Detection
<img src="https://github.com/ethanhou99/Ship-Detection/blob/master/images/Team_logo_v2.png" />

## Introduction & Dataset source
- This project is designed for the Airbus Ship Detection Challenge, and all the infos needed and datasets are in the following link(reference link:https://www.kaggle.com/c/airbus-ship-detection)

## Backstory
- Shipping traffic is growing fast. More ships increase the chances of infractions at sea like environmentally devastating ship accidents, piracy, illegal fishing, drug trafficking, and illegal cargo movement. This has compelled many organizations, from environmental protection agencies to insurance companies and national government authorities, to have a closer watch over the open seas.

## Poster
<img src="https://github.com/Wwwzff/Ship-Detection/blob/master/images/poster.png" />

## Todo List
- [x] Model select
- [x] Webpage basic design
- [x] Metric choosing
- [x] Loss Function choosing
- [x] Learning Rate Adjustment
- [x] Hyper Parameters choosing
- [ ] Model improvement
- [ ] Webpage improvement
- [ ] Webpage Deployment

## Current Best Result
<img src="https://github.com/Wwwzff/Ship-Detection/blob/master/images/bestresult_v2.png"/>
- Check our training log here: https://github.com/Wwwzff/Ship-Detection/blob/master/Train_history/Summary.md

## Method and Examples

### Block Diagram
<img src="https://github.com/ethanhou99/Ship-Detection/blob/master/images/block_diagram.png" />

- This project can be seprated into two parts: "Object Detection & User Input". The model will be trained using thousands of training set and be frozen after training. While user using the designed application, a set of photos will be inputed. Then the application will call the trained model and output the ships' directions. 

- Current application can detect the sea and other objects. For the next step, we will add some complex training set to improve the noise-process-ability.

### Application Interface
![preview](https://github.com/Wwwzff/Ship-Detection/blob/master/images/website.jpg)
Try the web app at location: https://github.com/Wwwzff/ShipDetector


## Keynote
- Use Unet to detect ship in a Satellite Picture dataset offered by Kaggle. 
- Methods are specially modified to fit the time limit on Kaggle notebook.
