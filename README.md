# Skin-Disease-Prediction
This project develops a skin disease prediction system utilizing a Random Forest classifier for classification and a pre-trained VGG16 model for feature extraction. The model is specifically trained and evaluated on a dataset containing images of two distinct skin diseases: benign and malignant.

Approach:
1. Feature Extraction with VGG16:
The project employs Transfer Learning by utilizing a pre-trained VGG16 model from ImageNet, implemented in Keras. This model extracts relevant features from the skin disease images, which serve as input for the classification process.
2. Classification with Random Forest:
The features extracted from the VGG16 model are given into the Random Forest classifier. This ensemble learning method provides multiple decision trees trained ojn subsets of the image data to predict the skin disease type.

Prerequisites:
Python 3.8 and higher.

Dependencies:
1. TensorFlow
2. Keras
3. NumPy
4. Matplotlib
5. Scikit-learn
6. Pandas

Dataset:
The dataset contains images of skin diseases categorized into two classees, organized into training and testing folders.

Results:
Model Performance:
Accuracy : 84%
ROC (area): 0.92

Conclusion:
The VGG16 model extracts deep features that enhace classification performance effectively. The Random Forest Classifier, which as a part of ensemble learning utilizes multiple decision trees to improve accuracy. With an accuracy of 84% and a AUC-ROC score of 0.92, this model demonstrates its efficiency in predicting skin diseases.
