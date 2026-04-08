# Assignment 4 ICS 435 Machine Learning


## Part I. Convolutional Neural Networks (CNN) for FashionMNIST
- Objective: The goal of this assignment is to implement a Convolutional Neural Network (CNN) to classify images from the FashionMNIST dataset. You will learn how to preprocess the data, build and train a CNN, and evaluate its performance.
- Dataset: FashionMNIST is a dataset of 60,000 training images and 10,000 test images, each of size 28x28 grayscale, categorized into 10 different fashion classes (e.g., T-shirt, dress, sneaker, etc.).
  
## Step 1: Data Preprocessing
1. Load the FashionMNIST dataset using torchvision.datasets (for PyTorch) or tensorflow.keras.datasets (for TensorFlow).
2. Normalize the images to the range [0,1] and reshape them if necessary.
3. Split the dataset into training and validation sets.


## Step 2: Building the CNN Model
1. You can try different CNN architectures (depth, kernel size) yourself
2. Pick appropriate loss function and optimizer

   
## Step 3: Training & Evaluation
1. Train the model
o Plot loss curves.

3. Evaluate the model:
o Compute test accuracy.
o Generate a confusion matrix

## Step 4: Experimentation & Improvements
1. Try at least two modifications (e.g., adding more layers, changing filter size, adding dropout, batch normalization, or data augmentation).
2. Compare the results with your baseline model and discuss improvements.
   
# Part II: Fine-Tuning GPT-2 for Joke Generation
- Dataset: You will be working with a dataset containing 1,622 short jokes.
- Task: Fine-tune a GPT-2 model (see the documentation here) to generate a complete joke based on the first three input words.
- Example:
Given the input:
"what", "did", "the",
your model should generate a full joke, such as:
### "What did the bartender say to the jumper cables? You better not try to start anything."

In your report, make sure to include:
1. Examples of generated jokes based on three starting words that exist in the dataset.
2. Examples of jokes generated from three randomly chosen words (not necessarily from the
dataset). Analyze and discuss how well the model performs in both cases.

# Submission Requirements:
• Upload your Jupyter Notebook or Python script with code, comments to a GitHub repository.
• A report containing the GitHub link.
