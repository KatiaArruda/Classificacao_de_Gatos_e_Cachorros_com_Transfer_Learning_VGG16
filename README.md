# Classificacao_de_Gatos_e_Cachorros_com_Transfer_Learning_VGG16
Classification of Cats and Dogs with Transfer Learning (VGG16)
This project utilizes the Transfer Learning technique with the pre-trained VGG16 model to classify images of cats and dogs.

# Code Structure
- Importing Libraries: Import necessary libraries such as TensorFlow, Keras, NumPy, and Matplotlib.
- Dataset Preparation: The image dataset is organized into specific directories (cats and dogs).
- Image Processing: Random selection of up to 50 images per class, resizing, and normalization.
- Data Shuffling and Splitting: The data is shuffled and split into training (70%), validation (15%), and test (15%) sets.
- Pre-trained VGG16 Model: Loading the VGG16 model with ImageNet weights and adding custom layers.
- Training and Evaluation: Training the model and evaluating its performance on the test set.
- Visualization of Results: Plotting the training and validation accuracy over epochs.

# Results
Test Set Accuracy: Varies based on training
The model achieved an accuracy of approximately 73% on the test set in one execution, demonstrating a good ability to classify images of cats and dogs. The accuracy may vary depending on dataset characteristics and training conditions.

# Requirements:
- TensorFlow
- Keras
- NumPy
- Matplotlib

# Visualization of Results
The training and validation accuracy graphs over epochs were plotted for visual analysis of the model's performance.

# Main Points of the Code
 - Image Processing: Selection of up to 50 random images of cats and dogs, resizing, and normalization.
 - Data Splitting: The data was split into training (70%), validation (15%), and test (15%) sets.
 - Pre-trained VGG16 Model: Utilization of the VGG16 model with ImageNet weights and addition of custom layers for classification.
 - Training: The model was trained for 10 epochs, monitoring validation accuracy.
 - Evaluation: Achieved approximately 73% accuracy on the test set in one execution, but the result may vary.

 # Result Summary
After training the image classification model using transfer learning with VGG16, the performance was evaluated on the test set. The model achieved an accuracy of around 73%, but the result may vary depending on training conditions and dataset characteristics. This demonstrates a good ability of the model to differentiate between the two classes.

