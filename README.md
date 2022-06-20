practice_ml_competition 2022-1
===
Team 8
---

- **김민준** 컴퓨터공학과 2016104107
- **강성문** 소프트웨어융합학과 2017103707
- **전민우** 소프트웨어융합학과 2017103752   

https://www.kaggle.com/competitions/2022-spring-khu-competition    
최종결과 3위

#### [Dataset]   
Birds Dataset
58388 images for train & 2000 images for test
![image](https://user-images.githubusercontent.com/65657711/174601950-25a1b94c-2d14-45fc-9e12-ccfceb2a23ed.png)



#### [Model]   
MixNet-M   

#### [Data Augmentation]   
![image](https://user-images.githubusercontent.com/65657711/174601539-a2c42d9d-d37f-431c-8eb6-b9b55e85e7c0.png)

#### [HyperParameter]   
BatchSize = 128 / LR = 0.0001 / EPOCHS = 50 / WD = 5e-4 /Momentum = 0.9 /Optimizer: SGD /Loss Function: CrossEntropy

#### [LR Scheduler]
Warm up start Cosine Annealing   
![image](https://user-images.githubusercontent.com/65657711/174602249-9d41ef9a-2305-418e-835a-064fa6ecd6a8.png)

#### [Test dataset accuracy]   
99.45%
