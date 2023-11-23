
TensorFlow Image Classification with Multi-Output Model

This project demonstrates multi-task learning using TensorFlow, where a model is trained to predict both the digit and color of handwritten images from the MNIST dataset. The code is organized into several tasks, each serving a specific purpose.

Task 1: Setup and Data Preparation
Import necessary libraries and set up the environment for TensorFlow and visualization.
Load the MNIST dataset and prepare a function (create_example) to create examples with random colorization.
Task 2: Dataset Generation
Implement a data generator (generate_data) to yield batches of images, digits, and colors for training and testing.
Task 3: Model Creation
Build a multi-task model using TensorFlow's Keras API. The model predicts the digit and color of input images.
Define a custom Logger callback to monitor and display training progress.
Task 4: Model Training
Train the multi-task model using the defined data generator and Logger callback.
Utilize TensorBoard for visualizing training metrics and logs.
Task 5: Final Predictions
Implement a function (test_model) to visualize predictions on a single test example.
Display a grid of test predictions to assess the model's performance on multiple samples.

