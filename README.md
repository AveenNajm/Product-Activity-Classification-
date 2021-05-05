# Product-Activity-Classification-
## Introduction 

Latest Mobile phones have lots of sensors like Acceleration, Magnetic Field, Orientation and angular velocity that are used by lots of mobile apps. Mobile apps can use these sensors to get data about our activities. One such mobile app is MATLAB which can be freely downloaded from Google play store or app store. This app can record the activities like walking, sitting, drop-pickup and standing and stored the data in MATLAB drive. From MATLAB drive data can be stored in CSV files and imported into the jupyter notebook for analysis using python machine learning and deep learning libraries. Artificial neural networks can be used train models using some dataset and this model can then be used to test some similar but unseen dataset

## Collected data and prepare data for machine learning   
![image](https://user-images.githubusercontent.com/81532727/117134395-6facd300-ad9d-11eb-9eec-a4652085b4a8.png)

### Orientation line graph example 
Clear  showing how I hold the phone compare with phone( x y z and -xyz)

![image](https://user-images.githubusercontent.com/81532727/117134646-ba2e4f80-ad9d-11eb-8dfc-b1096c4c5417.png)

### Create neural networking and training 

As you can see in the table blow when the hyperparameter were changed from batch size 120 raining and 80 epochs, it gave good accuracy result (0.9979) and the loss was (0.0058) for 2 hidden layers with 8 neurons(that is model chose ).   
![image](https://user-images.githubusercontent.com/81532727/117134756-e4800d00-ad9d-11eb-855c-3a2654453c25.png)

