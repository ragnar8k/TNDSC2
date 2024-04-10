**README**

**Introduction:**
This code is a demonstration of a Convolutional Neural Network (CNN) implemented using TensorFlow and Keras for the binary classification of images into cats and dogs. This README provides an overview of the code's functionality and instructions for usage.

**Files Included:**
1. `convolutional_neural_network.py`: Python script containing the CNN implementation.
2. `input.csv`: Training data containing images in CSV format.
3. `labels.csv`: Labels corresponding to training data images.
4. `input_test.csv`: Test data containing images in CSV format.
5. `labels_test.csv`: Labels corresponding to test data images.

**Setup:**
1. Ensure Python is installed on your system (version 3.6 or higher is recommended).
2. Install necessary packages by running:
   ```
   pip install numpy matplotlib tensorflow
   ```
3. Place the CSV files (`input.csv`, `labels.csv`, `input_test.csv`, `labels_test.csv`) in the same directory as the Python script.

**Instructions:**
1. Run the `convolutional_neural_network.py` script.
2. The script loads the training and test datasets from CSV files.
3. Data preprocessing includes reshaping and normalizing pixel values to the range [0, 1].
4. The CNN model architecture is defined and compiled with binary cross-entropy loss and Adam optimizer.
5. The model is trained on the training dataset for 5 epochs with a batch size of 64.
6. After training, the model is evaluated on the test dataset to measure loss and accuracy.
7. The script demonstrates making predictions on a random test image and displays the prediction result (cat or dog).

**Note:**
- Ensure the CSV files are correctly formatted and contain image data.
- Adjust hyperparameters like epochs and batch size according to your requirements.
- Experiment with different CNN architectures for potential improvements in classification accuracy.
- Basic familiarity with Python, TensorFlow, and Keras is assumed.

