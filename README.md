<p align="center">
 <img width="150" height="146" src="https://user-images.githubusercontent.com/13907836/51081445-7d0d9300-16a4-11e9-8e4d-6ccad8359bf8.png">
</p>

<h1 align="center">Deep Neural Network with Raspberry Pi <br> Team Triton </h1>

 ## Description
 An implmentation and analysis of Raspberry Pis cluster in solving shallow and deep learning problems.
 ## Quick Links
  - [Research paper](https://github.com/sotheanith/DNN-with-Raspberry-Pi-by-Triton/blob/master/Research%20Paper/report.pdf)
  - [Demo with Scikit-Learn (GridSearchCV + SVC, Monte Carlo, RandomForest)](https://github.com/sotheanith/DNN-with-Raspberry-Pi-by-Triton/blob/master/Demo/Dash%20Demo.ipynb)
  - [Demo with Scikit-Learn + Tensorflow (Convolutional Neural Network)](https://github.com/sotheanith/DNN-with-Raspberry-Pi-by-Triton/blob/master/Demo/Demo2.ipynb)
  - [Demo with Scikit-Learn + Tensorflow (GridSearchCV + Fully Connected Neural Network)](https://github.com/sotheanith/DNN-with-Raspberry-Pi-by-Triton/blob/master/Demo/Keras%20Deep%20Learning%20Models%20with%20Scikit-Learn%20in%20Python.ipynb)
  - [Guide: How to setup the cluster](https://github.com/sotheanith/DNN-with-Raspberry-Pi-by-Triton/blob/master/HowToSetup.pdf)
  - [References](https://github.com/sotheanith/DNN-with-Raspberry-Pi-by-Triton/tree/master/References)
 ## Setup
  ### Software
   - [Python](https://www.python.org/)
   - [Dask](https://dask.org/)
   - [Dask-ML](https://ml.dask.org/)
   - [JobLib](https://joblib.readthedocs.io/en/latest/)
   - [Scikit-Learn](https://scikit-learn.org/stable/)
   - [Tensorflow](https://www.tensorflow.org/)
  ### Hardware
   - 4 x [Raspberry Pi](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)
   - 1 x Laptop
   - 1 x Desktop
   - 1 x Consumer-grade router
 ## Results for various size cluster used to train Random Forest Classifier
  Hardware                               | Computing Cores | Memory (GB) | Ideal Execution Time (seconds) | Execution Times (seconds) | Scalability 
  -------------------------------------- | --------------- | ----------- | ------------------------------ | ------------------------- | -----------
  1 x Raspberry Pi                       | 4               | 2           | 901                            | 901                       | 1            
  1 x Raspberry, 1 x Desktop             | 11              | 11.21       | 327.6363636                    | 237                       | 1.382431914            
  2 x Raspberry, 1 x Desktop             | 15              | 13.14       | 240.2666667                    | 181                       | 1.327440147            
  3 x Raspberry, 1 x Desktop             | 19              | 15.08       | 189.6842105                    | 152                       | 1.247922438            
  4 x Raspberry, 1 x Desktop             | 23              | 17.02       | 156.6956522                    | 134                       | 1.169370539            
  4 x Raspberry, 1 x Desktop, 1 x Laptop | 30              | 29.57       | 120.1333333                    | 124                       | 0.968817204
 ## Authors
  - Lauro Cabral
    - Email  : Lauro.Cabral@student.csulb.edu
    - Github : https://github.com/Lauro199471
  - Sotheanith Sok
    - Email  : Sotheanith.Sok@student.csulb.edu
    - Github : https://github.com/sotheanith
