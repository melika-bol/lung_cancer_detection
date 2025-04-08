In this project, we have tried to predict the presence or absence of lung cancer using deep learning models using medical data from patients.
The goal of this project is to build a model that can help doctors detect cancer early and detect 3 classes contain :
Bengin cases - Malignant cases - Normal cases
_______________________________________________________________________________________________________________________________________________________________
In this project, a deep learning model was developed to detect lung cancer from X-ray images.
First, I designed a CNN network and then compared it with the pre-trained 50ResNet model.
_______________________________________________________________________________________________________________________________________________________________
using :
- Python
- Pytorch
- Pandas & Numpy
- Matplotlib
- Scikit-Learn
_______________________________________________________________________________________________________________________________________________________________

The data for this project was obtained from the Lung Cancer Dataset OTHNCCD-IQ (Augmented) version on Kaggle,
which included X-ray images of patients with benign and malignant cancers, as well as healthy individuals.
_______________________________________________________________________________________________________________________________________________________________
CNN final results:

Train Accuracy: 80.74%

Validation Accuracy: 83.32% 

Precision, Recall, F1-score:

Benign cases → Precision: 79% | Recall: 73% | F1-score: 76%

Malignant cases → Precision: 93% | Recall: 98% | F1-score: 95%

Normal cases → Precision: 76% | Recall: 78% | F1-score: 77%
_______________________________________________________________________________________________________________________________________________________________
resnet50 final result:

Train Accuracy: 99.00% 

Validation Accuracy: 99.50% 

Precision, Recall, F1-score:

   Benign cases       0.99      0.99      0.99      1200
   
Malignant cases       1.00      1.00      1.00      1201

   Normal cases       0.99      0.99      0.99      1208

       accuracy                           0.99      3609
       
      macro avg       0.99      0.99      0.99      3609
      
   weighted avg       0.99      0.99      0.99      3609
   
