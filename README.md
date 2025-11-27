Key Features

Hybrid Model: Combines tabular data (structured metadata) and image data (visual damage indicators) for enhanced accuracy.
Machine Learning Models: Includes Random Forest, XGBoost, AutoGluon TabularPredictor, and BERT for tabular data classification.
Deep Learning Models: Utilizes ResNet50 for image classification, fine-tuned for earthquake damage assessment.
Data Augmentation: Applied to image data to improve model generalization and reduce overfitting.
Meta-Classifier: Combines predictions from tabular and image models to achieve superior performance.
How to Run

Clone the repository:


Install dependencies:


Prepare the dataset:

Download the dataset from the StEER Network or use your own labeled dataset.
Place images in the data/images folder and tabular data in data/tabular folder.


Run the preprocessing script:


Train the models:

Tabular model:


Image model:


Hybrid model:




Evaluate the models:



Technologies Used

Python
TensorFlow/Keras
PyTorch
Hugging Face Transformers
AutoGluon
scikit-learn
XGBoost
GeoPandas
Matplotlib/Seaborn
