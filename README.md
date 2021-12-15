# ELEC0134_ASSIGNMENT

## Assignment overview
The assignment is to solve MRI image classification tasks. For both task A and task B, classifiers are designed including SVM and KNN. Tests are designed to do hyper-parameters selection, and final testing dataset proves that the models achieve considerable accuracy in both tasks.
## Requirements
-	Python == 3.7
-	scikit-learn == 1.0.1
-	numpy == 1.21.2
-	pandas == 13.4
-	matplotlib == 3.4.3
-	OpenCV == 3.4.2
-	Keras == 2.3.1
## Datasets
-	training data: 3000 512x512 pixel gray-scale MRI images organized in 4 classes. 
-	training data path: ./assignment_dataset/image
-	training label path: ./assignment_dataset/label.csv
-	testing data: 200 512x512 pixel gray-scale MRI images organized in 4 classes.
-	testing data path: ./test/image
-	testing label path: ./test/label.csv

## Code organization
The code is separated into two jupyter files, taska.ipynb for task A and taskb.ipynb for task B. Both files include the functions need for data pre-processing and model training. To execute the code, click Run button to run the whole program or click run icon of each line to run the single code block.
## Results
|       | Model | Training Accuracy | Validation Accuracy | Testing  Accuracy |
| :----: | :----: | :----: | :----: | :----: |
| TaskA | SVM | 100% | 94.4% | 91.5% |
| TaskA | KNN | 100% | 95.0% | 92.4% |
| TaskB | SVM | 97.5% | 83.4% | 80.5% |
| TaskB | KNN | 93.4% | 78.6% | 77.0% |
