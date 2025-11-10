📅 Week 1 — Project Setup & Data Preparation

✅ Summary

During Week 1, the focus was on understanding the project problem, setting up the environment, collecting the dataset, and preparing the folder structure. This week laid the foundation for the development phase.

✅ Tasks Completed

Researched crop diseases and how they affect plant health.

Created project folder structure with separate directories for dataset, model, and application.

Set up Python virtual environment and installed necessary libraries (TensorFlow, Keras, matplotlib, scikit-learn, Streamlit).

Downloaded the PlantVillage dataset from Kaggle.

Organized the dataset into training and validation folders.

Preprocessed image data using resizing, normalization, and augmentation techniques.


✅ Output

A clean and organized project structure.

Augmented and preprocessed leaf images ready for training.



---

📅 Week 2 — Model Building & Training

✅ Summary

In Week 2, the main goal was to build a CNN model using transfer learning and train it on the prepared dataset.

✅ Tasks Completed

Implemented EfficientNetB0 as the base model using transfer learning.

Added custom fully-connected layers for classification.

Compiled the model using Adam optimizer and categorical cross-entropy loss.

Successfully trained the model for 10 epochs using augmented dataset.

Monitored validation accuracy and ensured no overfitting.

Saved the trained model as crop_disease_model.h5.


✅ Output

Trained model with high accuracy (90%+ on validation set).

Model file stored in /model/crop_disease_model.h5.

Plots for training/validation accuracy and loss curves generated.
