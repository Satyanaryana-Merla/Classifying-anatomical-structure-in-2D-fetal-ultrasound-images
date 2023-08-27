# Classifying-anatomical-structure-in-2D-fetal-ultrasound-images
A deep learning model was trained on fetal ultrasound images, achieving promising classification results across four anatomical structures. The model was optimized and tested on a separate dataset. The code organized and saved classified images, establishing a robust pipeline for accurate fetal anatomical structure classification.

By Satyanarayana Merla
# Due to data privacy, the dataset and data labels are not provided.
## Data Preparation
- The dataset used for this task is loaded from 'E:/task1/image_label.csv'.
- Images were pre-processed, including resizing to 256x256 pixels and normalization.
## Model Training
- A Convolutional Neural Network (CNN) model was used for fetal ultrasound image classification.
- The CNN architecture consisted of multiple convolutional and max-pooling layers followed by fully connected layers.
- Data augmentation techniques were applied to the training set to improve model generalization.
- The model was trained for 10 epochs.
## Model Evaluation
- The trained model was evaluated on a test dataset to assess its performance.
- Evaluation metrics included loss and accuracy.
## Model Performance
- Test Loss: 0.4526
- Test Accuracy: 83.96%
## Model Application
- The trained model was used to classify images into four categories: abdomen, thorax, brain, and femur.
## Classification of External Image
- An external image, 'Patient01600_Plane6_1_of_8.png', was used to test the model's performance.
- The image was classified as: [Insert Predicted Label]
## Future Work
- Potential improvements for model performance were discussed, including transfer learning, hyperparameter tuning, and ensemble methods.
## Conclusion
- In conclusion, the trained model shows promise in classifying fetal ultrasound images into anatomical structures.
- Further improvements and refinements can be explored to enhance its performance.
## Ethical Considerations
- Ethical considerations, such as patient data privacy and responsible AI use, should always be prioritized in medical image analysis.
