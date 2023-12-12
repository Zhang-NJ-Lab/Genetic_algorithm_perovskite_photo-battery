# Genetic programming

  Genetic algorithm codes to accelerate material property prediction, and provide mathematical equation to decouple contributions for ion/perovskite photo-rechargeable battery materialsgenetic classification and regression codes for ion battery paper


# Instructions

## Follow the three jupyter tutorial files
 
 symbolic_regression.ipynb         

regression task (accuracy unsually low if descriptors quality is low)

 symbolic_classification.ipynb     

classification task (stable or unstable)

 genetic_prediction.ipynb          

predict the expensive virtual space (input feature number should be the same as the train/test feature number, and a target name should be provided in the last column first row)


## Datasets

 prediction_withoutLable.csv       unlabelled virtual dataset to predict the expensive virtual space (input feature number should be the same as the train/test feature number, and a target name should be provided in the last column first row)

 TrainTest_classification_minus0.1_minus3_Feature_selection.csv       train/test dataset for classification 

 TrainTest.csv    train/test dataset for regression

 TrainTest-description.xlsx     description of the train/test dataset


## Paper to extract dataset

 74-ML-Ion-Perovskite-HWG-AMI.pdf


![Image text](https://github.com/Zhang-NJ-Lab/genetic_ion-perovskite_PhotoRechargeableBattery/blob/d3c783360adb07324894c02c1bf70ea58226f77b/images/paper.png)