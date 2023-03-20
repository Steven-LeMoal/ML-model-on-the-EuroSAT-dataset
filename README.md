# ML-model-on-the-EuroSAT-dataset

Task - Your task is to train a ML model on the EuroSAT land cover classification
dataset.
Dataset link- Dataset. The dataset contains 64x64 RGB images from Sentinel-2.
You can find references to the dataset here - https://github.com/phelber/EuroSAT

Deliverables -

1. Training [Jupyter notebook]: Include all steps from loading the dataset, to
saving the model and evaluation metrics.
2. Inference [Jupyter notebook]: Notebook to perform inference, generate and
save classification results. Use 20 sample images from the dataset.

Constraints of the current solution:

Limited size of training data (subset of 2000 images) may lead to overfitting and lower model accuracy.
VGG16 has a large number of parameters and may require significant computational resources for training.
Limited use of data augmentation techniques may limit the model's ability to generalize to new data.
Use of a pre-trained model may limit the flexibility in model customization.

Potential improvements to the solution:

Increase the size of the training data to improve model accuracy and reduce overfitting.
Explore the use of other pre-trained models or custom model architectures to improve model performance.
Use more advanced data augmentation techniques to improve model's ability to generalize to new data.
Experiment with different optimization algorithms and learning rates to improve model convergence and accuracy.
Analyze the performance of the model on a larger set of images to evaluate its generalization ability.
