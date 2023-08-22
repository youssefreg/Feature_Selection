# Feature_Selection
Evaluation of the impact of Feature Selection algorithms on an intrusion detection system based on machine learning


## Implementation N1

(Implementation N.1) provides an overview of the treebased ML classification framework for intrusion detection.
The process of the proposed model is as follows. Firstly, sufficient network traffic data is collected. Secondly, if the classes of the data set are imbalanced, oversampling is implemented to reduce its impact. At the next stage, feature selection based on averaging feature importance is done to reduce computational cost. After that, four base-models are built to be the input of the stacking ensemble model. At the end, the final model is built to classify the data.

![Implementation_1](https://github.com/youssefreg/Feature_Selection/assets/112189559/94d8c0dd-315a-4cbc-ba1e-e42d27c84ab1)


## Implementation N2

In (implementation N.2) the data pre-processing stage involves the utilization of feature selection algorithms to identify and retain relevant features. Information gain and correlation-based feature selection methods are employed to eliminate irrelevant and redundant features from the dataset. Additionally, the Fast Correlation Based Filter (FCBF) model is used to further reduce dimensionality and eliminate noisy features, thereby improving the quality of the network data.

![results_IGandFCBF](https://github.com/youssefreg/Feature_Selection/assets/112189559/eb9b5fc7-93e3-43f9-ad1b-20b0ad1540b2)
