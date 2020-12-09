# DNN with Raspberry Pi
 An implmentation and analysis of Raspberry Pis cluster in solving shallow and deep learning problems.
 ## Quick Links
  - Research paper
  - Demo with Scikit-Learn (GridSearchCV + SVC, Monte Carlo, RandomForest)
  - Demo with Scikit-Learn + Tensorflow (Convolutional Neural Network)
  - Demo with Scikit-Learn + Tensorflow (GridSearchCV + Fully Connected Neural Network)
  - Video on how to setup the cluster
  - References
 ## Setup
  ### Software
   - Python
   - Dask
   - Dask-ML
   - JobLib
   - Scikit-Learn
   - Tensorflow
  ### Hardware
   - 4 x Raspberry Pis
   - 1 x Laptop
   - 1 x Desktop
   - 1 x Consumer-grade router
 ## Cluster Sizes Testing (using RandomForest)
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
    - Email  : sotheanith.sok@student.csulb.edu
    - Github : https://github.com/sotheanith
