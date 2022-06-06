# Big-Data-Imbalanced-Learning
## Imbalanced Learning with ADASYN Oversampling using Big Data Techniques
### Project Description:
ADASYN is well known for its effectiveness in solving highly imbalanced datasets. It oversamples the minority classes to eliminate the bias of machine learning 
models towards the majority classes. However, with large and highly imbalanced datasets, using ADASYN potentially causes the dataset to double in size, 
significantly increasing the computational effort required for data processing and machine learning. In this work, we present a big data approach for imbalanced learning 
implemented under PySpark. 

<img src="https://user-images.githubusercontent.com/49972425/172186316-64b48747-cbba-48a7-afd7-d408627200ff.png" height="300"> <img src="https://user-images.githubusercontent.com/49972425/172186436-f74f87e8-3865-48bd-92d2-200cbd62081f.png" height="300">


### Implementation Details:
1. The solution was implemented in python using the pyspark, sklearn and imbalanced-learn packages. 
2. Dataset used in this implementation example is the ["IEEE-CIS Fraud Detection"](https://www.kaggle.com/competitions/ieee-fraud-detection) dataset.
3. All code used for the implementation is contained within the ["Fraud Detection.ipynb"](https://github.com/khoryongteng/Big-Data-Imbalanced-Learning/blob/main/Fraud%20Detection.ipynb) notebook.

### Results:
Results obtained can be read on the ["ADASYN for Imbalanced Learning in Big Data"](https://github.com/khoryongteng/Big-Data-Imbalanced-Learning/blob/main/ADASYN%20for%20Imbalanced%20Learning%20in%20Big%20Data.pdf) report.

### To run the experiments yourselves:
1. Download ["IEEE-CIS Fraud Detection"](https://www.kaggle.com/competitions/ieee-fraud-detection) dataset.
2. Run the ["Fraud Detection.ipynb"](https://github.com/khoryongteng/Big-Data-Imbalanced-Learning/blob/main/Fraud%20Detection.ipynb) notebook. Package installations are taken care of within the notebook.
3. File path to datasets may need to be changed.
