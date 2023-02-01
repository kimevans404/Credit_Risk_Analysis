# Credit_Risk_Analysis

## Overview of Analysis

To apply machine learning to solve a real-world challenge: credit card risk. This analysis will employ different techniques to train and evaluate models with unbalanced classes. 

## Results

### Using Resampling Models to Predict Credit Risk

#### Naive Random Oversampling

<img width="710" alt="Random1Accuracy" src="https://user-images.githubusercontent.com/111471057/216112212-822c3a92-25c1-4630-9b51-da61b1c07486.png">
<img width="710" alt="Random2Confusion" src="https://user-images.githubusercontent.com/111471057/216112220-ade8303c-ddbd-4bab-bb90-1e5b2639c950.png">
<img width="710" alt="Random3Report" src="https://user-images.githubusercontent.com/111471057/216112231-e24976ee-8331-4e46-a075-a3afa63277af.png">


#### SMOTE Oversampling

<img width="715" alt="Smote1Accuracy" src="https://user-images.githubusercontent.com/111471057/216112271-3920fde0-c24b-4c39-81ad-0d96d6f3bed6.png">
<img width="715" alt="Smote2Confusion" src="https://user-images.githubusercontent.com/111471057/216112282-e99d3c6c-e85e-4c29-81ab-b4f6f6361482.png">
<img width="715" alt="Smote3Report" src="https://user-images.githubusercontent.com/111471057/216112291-95e2b53d-28ab-494e-a2ae-2af09ff68d22.png">


#### Cluster Centroids Undersampling

<img width="716" alt="Cluster1Accuracy" src="https://user-images.githubusercontent.com/111471057/216112621-4c2afd55-0886-419b-b6aa-16a16f65268d.png">
<img width="715" alt="Cluster2Confusion" src="https://user-images.githubusercontent.com/111471057/216112639-ae9a9341-37f0-4c00-97a9-916f285146d4.png">
<img width="715" alt="Cluster3Report" src="https://user-images.githubusercontent.com/111471057/216112649-c912298b-35d5-447e-8b7b-407fc1e85069.png">


#### Using SMOTEENN algorithm to Predict Credit Risk

<img width="720" alt="Smoteenn1Accuracy" src="https://user-images.githubusercontent.com/111471057/216113252-14370954-52c2-45d3-a42e-a9015fd29048.png">
<img width="720" alt="Smoteenn2Confusion" src="https://user-images.githubusercontent.com/111471057/216113271-687981dd-9f63-46dc-ac13-ba476be9fdc1.png">
<img width="720" alt="Smoteen3Report" src="https://user-images.githubusercontent.com/111471057/216113284-aba38108-f4b4-4dda-8928-d38eca0ecd3d.png">



### Using Ensemble Classifiers to Predict Credit Risk

#### Random Forest Classifier

<img width="720" alt="Forest1Accuracy" src="https://user-images.githubusercontent.com/111471057/216114121-e3bd1397-7772-402c-950d-4596bfe7e25f.png">
<img width="720" alt="Forest2Confusion" src="https://user-images.githubusercontent.com/111471057/216114134-7112f74f-4c67-4490-a239-011355003818.png">
<img width="720" alt="Forest3Report" src="https://user-images.githubusercontent.com/111471057/216114140-5eb9d693-e518-4537-addf-e4dadfa1f908.png">


#### Easy Ensemble AdaBoost classifier

<img width="442" alt="Easy1Accuracy" src="https://user-images.githubusercontent.com/111471057/216114445-f523a116-02d9-427e-958c-6bfe15fc8e84.png">
<img width="510" alt="Easy2Confusion" src="https://user-images.githubusercontent.com/111471057/216114465-2215ca1c-36a3-4b2c-b3ae-2ca743488e81.png">
<img width="719" alt="Easy3Report" src="https://user-images.githubusercontent.com/111471057/216114489-12fd3277-8740-4f5a-9dc7-357eacae36f2.png">


## Summary

Evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
