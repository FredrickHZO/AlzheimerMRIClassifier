# AlzheimerMRIClassifier

### Model Architecture
The model is a custom Convolutional Neural Network (CNN), built from scratch without relying on any pre-trained architectures. It was designed specifically for the multi-class classification of brain MRI images into four categories: `NonDemented`, `VeryMildDemented`, `MildDemented`, and `ModerateDemented`.

The architecture includes multiple convolutional and pooling layers, followed by dense layers with dropout for regularization. Batch normalization was applied to accelerate convergence and improve generalization.

### Training Summary
The model was trained for 30 epochs on the processed dataset. Early training phases showed moderate performance, but accuracy and loss improved consistently across epochs.

By the final epoch, both training and validation metrics showed strong convergence, with the model achieving high accuracy and low loss on both sets. The learning progression indicates effective architecture design and stable optimization without overfitting.

### Evaluation
After training, the model was evaluated on a held-out test set. It demonstrated excellent generalization across all classes, confirming the robustness of the hand-crafted architecture.