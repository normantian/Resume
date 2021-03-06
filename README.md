# Resume of Yuan Yifan
## Write ahead
I'm looking for a **MACHINE LEARNING** job. My abilities is not limited in machine learning but my major work should be machine learning, this is really important.

## Basic info
**Name:** Yuan Yifan

**Nick:** Tsing Jyujing

**Mail Address:** [TsingJyujing@163.com](mailto://TsingJyujing@163.com "TsingJyujing@163.com")

**Tel:** 182-2085-2215

## Abilities

### 1 Machine Learning and Data Mining
1. Traditional machine learning, include regression(bp-neural-network, SVR), classification algorithms(SVM, logistic regression, bp-neural-network), cluster(AP, k-means), dimensionaly reduction(PCA, LDA, maniflod DR methods like IsoMap,LLE), sequential predict like hidden markov model;
2. Deeplearning, sequential predict network like RNN(LSTM), image recognition CNN and voice recognition CNN(CNN-1D);
3. Some basics about NLP like words division and N-Gram language model;
4. Mathematic basic of machine learning, convex optimization and intelligent optimization algorithms.

### 2 Programming
1. Have a good master of **MatLab, C and Python**;
2. To be familiar with **Java** and Scala.

### 3 Embedded Developing
1. Have a good master of 51/Arm Cortex-M development;
2. To be familiar with some common bus interface (CAN, USART, IIC, I2S, SPI,...).
3. Common peripherals' operation.

### 4 Signal Processing
1. Common signal processing methods like FFT, STFT, Wavelet decomposition, HHT and ect.;
2. Order analysis and waterfall diagramal analysis.

### 5 Automatic Control
1. Classic control theory and modern control theory;
2. To be familiar with fuzzy control theory

### 6 Automobile Knowledge
Automobile theory, constructure and design.

# Project Experiences

## While Working...
### Fault prediction
By using logistic regression to predict which vehicle may out of order, also can analysis which behavior will cause the specific fault and predict before happing. The accuracy of algorithm can predict 80%. Although the program can predict fault of vehicle but it can't when it will happen precisely.

### Correlation Analysis of Fuel-consumption and Driving Behaviour
We have a dataset which all vehicles have same model and same load, by linear regression, which using fuel-consumption (L) per hundred kilometer as dependent variable and use driving behaviour as independent variable, we found some resaon of high fuel-consumption and try to reduce it by training drivers. 

After training, the drivers their fuel-consumption while working successfully.

### User Cluster
For detecting how many types of power requirement in out users, we used torque-profiles and speed-profiles as feature to cluster, after cluster, we find there about 30 types of power requirement and explained it.

### GPS Heatmap Cluster
Some vehicles has it's specific working area, we cluster GPS-Heatmap by using manifold and k-means, and visualize the result.


### Driving Behaviour ETL System
For machine learning and data visualization, we extract features from driving data, after cleaned and transformed, we put them into a MongoDB. It update weekly and it's distributed and can scale-out easily.

### CAN Signal Panel
A control panel of CAN signal, it can connect 4 typed of USB-CAN and can be redeveloped by JavaScript.

## Experience in College
### Vehicle Dynamics Controller Development
For controlling vehicle, we built a yaw velocity controller by polynomial regression, and built an acceleration controller for longitude dynamics control, and we developed a car-following controller which can keep the distance of vehicles about 13~20m while speed is about 170kmph.

### Breath Motion Prediction
In gamma knife operation, the tumor will move caused by breath, by training a neural-network, we predict the position of tumor after 0.1,0.3,0.5 and 1s successfully.

### Fuzzy PID Controller of ABS Slip Rate
We built a vehicle model in ADAMS and used magic tire model for simulation, and we control the slip rate constantly about 20% for fast brake and kept control of direction.
