# Highway-accident-alert-system
Computer vision project for Real time Highway accident alert system through live CCTV cameras.

In this fast-paced world, the number of deaths due to accidents is growing at an expeditious rate. Major reasons for these accidents are rash driving, drowsiness, drunken driving, carelessness, etc. An indicator of survival rates after detecting accidents is the time between the occurrence of accidents and the advent of medical care to the victim. The rapid growth of technology has made everything more facile and this advancement in technology additionally increased accidents. Due to this delayed medical attention, the accident victims might die as well. As a solution to these problems, we introduce a system that detects road accidents and will provide an alert message to the most proximate control room immediately. The camera module of the system is deployed in accident-prone areas. Whenever an accident occurs, it will detect the accident and immediately report it to the nearby control room. The working of the system is based on deep learning techniques that use convolutional neural networks. By utilizing this system, many people can be saved from death. India had the most deaths in road accidents in the year 2019 with a total of 151113 deaths. There is a need for a lifesaving application that detects the accidents using the CCTV tapes and automatically sends a notification to the nearby government hospitals.

Architecture Used:
The proposed model uses ResNet50 CNN architecture for classification accident and non-accident image dataset. ResNet-50 is a convolutional neural network that is 50 layers deep.In residual learning, instead of trying to learn some features, we try to learn some residual. Residual can be simply understood as subtraction of features learned from the input of that layer. 

Dataset Used:
The dataset is collected from CCTV images available on the internet. Dataset has two types of labelled images Accident and Non-Accident.

Alert API:
After Successful classification, if the accident is detected in the live video feed
the notification is sent automatically to a nearby hospital. For Alerting a simple An API (TXTIND) is used which can send the location of the accident via SMS to the authorities.

Model Performance and Accuracy

<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/performace.png" width="250" height="200">


Block Diagram

<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/Picture1.png" width="700" height="500">

Screenshots

<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/screenshot1.png" width="400" height="300">

<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/screenshot2.png" width="400" height="300">

<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/Screenshot4.png" width="400" height="300">


<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/screenshot3.png" width="400" height="300">

Alert
<img src="https://github.com/anubhavmishra123/Highway-accident-alert-system/blob/main/screenshot%205.png" width="400" height="300">

