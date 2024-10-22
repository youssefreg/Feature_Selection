# Feature_Selection
Evaluation of the impact of Feature Selection algorithms on an intrusion detection system based on machine learning


## Implementation N1 (*Average Feature Importance*)

(Implementation N.1) provides an overview of the treebased ML classification framework for intrusion detection.
The process of the proposed model is as follows. Firstly, sufficient network traffic data is collected. Secondly, if the classes of the data set are imbalanced, oversampling is implemented to reduce its impact. At the next stage, feature selection based on averaging feature importance is done to reduce computational cost. After that, four base-models are built to be the input of the stacking ensemble model. At the end, the final model is built to classify the data.

 ![results_AVI](https://github.com/youssefreg/Feature_Selection/assets/112189559/44ea8b45-0d9c-4f54-aa13-5f41fb335ae7)


## Implementation N2 (*information gain && Fast Correlation Based Filter (FCBF)*)
 
In (implementation N.2) the data pre-processing stage involves the utilization of feature selection algorithms to identify and retain relevant features. Information gain and correlation-based feature selection methods are employed to eliminate irrelevant and redundant features from the dataset. Additionally, the Fast Correlation Based Filter (FCBF) model is used to further reduce dimensionality and eliminate noisy features, thereby improving the quality of the network data.

![results_IGandFCBF](https://github.com/youssefreg/Feature_Selection/assets/112189559/eb9b5fc7-93e3-43f9-ad1b-20b0ad1540b2)


## Stages of project implementation

*Step 1: Binary Analysis using CICIDS2017 Dataset.*

*Step 2: Study of Each Attack using CICIDS2017 Dataset.*

*Step 3:Study of Each Attack using CICIDS2017 Dataset with Augmented Dataset by CSE-CIC-IDS2018 and HTTP databases.*




## Citations

If you use the source code please cite the following paper:

```bibtex
@MastersThesis{Regragui2023,
    author = {Regragui, Youssef},
    title = {{Evaluation of the impact of Feature Selection algorithms on an intrusion detection system based on machine learning}},
    school = {Faculty of Sciences of Rabat, MOHAMMED V},
    year = {2023}
}
