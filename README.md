# Fashion-Images-Classifier

## Objective
This project involves building, optimizing, and evaluating a neural network model for image classification using the Fashion MNIST dataset. The goal is to enhance the model’s performance through hyperparameter tuning and to assess its effectiveness in classifying different types of fashion items.

## Data
The dataset used in this project is the Fashion MNIST dataset, consisting of:

- **Training Set**: 60,000 images with corresponding labels (split into 6 parts for GitHub).
- **Test Set**: 10,000 images with corresponding labels.

Each image is a 28x28 grayscale image representing one of 10 fashion categories.

### Important: Data Download Instructions
Due to GitHub's file size limitations (25 MB per file), the training set has been split into 6 separate files:

- `Fashion Train Data 1.csv`
- `Fashion Train Data 2.csv`
- `Fashion Train Data 3.csv`
- `Fashion Train Data 4.csv`
- `Fashion Train Data 5.csv`
- `Fashion Train Data 6.csv`

Please download all 6 files and keep them in the same directory. The notebook contains code that will automatically merge these files into a single dataset. Just ensure that the files are named exactly as listed above, and the merging process will be handled for you.

## Key Features
### Data Preparation:
- Loading and preprocessing the dataset.
- Merging the training set files into a single dataset.
- Splitting the dataset into training, cross-validation, and test sets.

### Model Development:
- Designing a neural network architecture with dropout layers.
- Experimenting with different hyperparameters.

### Model Training:
- Training the model on the combined training and cross-validation data.
- Utilizing early stopping to prevent overfitting.

### Model Optimization:
- Hyperparameter tuning to find the optimal configuration.
- Evaluation of different models to select the best-performing one.

### Evaluation and Analysis:
- Analyzing performance metrics including accuracy, loss, and confusion matrix.
- Generating classification reports to assess precision, recall, and F1-scores.

### Visualization:
- Displaying misclassified images to understand model errors.
- Comparing initial and optimized model performance visually.

## Conclusion
- **Summary of Results**: Overview of model performance and key findings.
- **Model Robustness**: Assessment of generalization and effectiveness.

*Note: This project serves as a practical demonstration of neural network optimization and performance evaluation in image classification tasks. The data files were split due to GitHub's file size limitations, but they can easily be merged as explained.*
