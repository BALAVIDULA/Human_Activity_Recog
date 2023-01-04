# Recognition of Daily Activities using Machine Learning

## Dataset

The Human Activity dataset is built using the recordings of 30 participants performing daily activities, carrying a mounted smartphone with sensors. Each person performs six activities :

> Walking

> Walking upstairs

> Walking downstairs

> Sitting

> Standing

> Laying

Download the dataset [Human Activity Recognition using Smartphones]( https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)

## Abstract
One of the current study fields in computer vision is human activity recognition. It has many applications in security monitoring, healthcare, and human-computer interaction. This model displays the proportion of each activity mentioned above using unsupervised algorithms. Machine Learning algorithms : Support Vector Classifier and Random Forest Classifier are used to classify in this code where Random Forest Classifier model provided with the high accuracy of 98%.

## Environment and Tools
- Colab Notebook
+ Numpy
* Pandas
- Python

# Model
The activities:

![activities](https://user-images.githubusercontent.com/114278846/210571171-69fe6373-2a59-42a2-ab1f-8063c94af1eb.jpeg)

Bar chart for each Activity:

![activity_bar](https://user-images.githubusercontent.com/114278846/210572171-18ae3be5-1aa7-40a2-9397-b32f47c2e41d.png)

Bar Chart for each person with respective each Activity
![each_person_bar](https://user-images.githubusercontent.com/114278846/210572434-d8039dc4-5726-4dd7-917c-4f2ab6232b82.png)

## Pre-processing
-> Feature Scaling

-> Label Encoder

![label_enc_1](https://user-images.githubusercontent.com/114278846/210571374-020087bb-dbdb-49db-b8d0-6900ffc83728.jpeg)

![label_enc_2](https://user-images.githubusercontent.com/114278846/210571395-cd37f7fc-2ecb-44ce-b034-c0aa7748af67.jpeg)

Label Encoder is used for changing the type to Integer form object type.

## Prediction

**Support Vector Classifier – SVC**
Model score: 97%

**Random Forest Classifier**
Model score: 98%

## Accuracy Metrics

> Confusion Matrix

![confusion_matris](https://user-images.githubusercontent.com/114278846/210571833-67638af6-e8d5-4586-8eeb-ec985dc6601b.jpeg)

> Accuracy Score

![acc_score](https://user-images.githubusercontent.com/114278846/210571899-aac89480-e8d5-4d7f-b4b5-82cbed0e9862.jpeg)

>  Recall value

![recall](https://user-images.githubusercontent.com/114278846/210571953-ee08e778-8773-4631-bf29-75f77a2c5151.jpeg)

> Precision value

![precision](https://user-images.githubusercontent.com/114278846/210571992-646db8f1-bcc2-41ee-be11-c24ddffc17ba.jpeg)

> F1 Score

![f1](https://user-images.githubusercontent.com/114278846/210572082-aff726d8-b94a-4a5c-bc4c-79a7493d670f.jpeg)
