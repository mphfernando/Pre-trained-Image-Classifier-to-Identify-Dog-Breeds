# Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
AWS AI &amp; ML Scholarship Program 
1st project
GitHub Description
# Image Classification: Identifying Dogs and Their Breeds

This project implements an image classification system using Convolutional Neural Networks (CNNs) to identify:

Whether an image contains a dog or not.
The specific breed of the dog if present.
It also evaluates the performance of three pretrained CNN architectures—ResNet, AlexNet, and VGG—and determines the best model for achieving accuracy with minimal computational resources.

## Project Objectives

Correctly classify pet images as "dog" or "not a dog."
Accurately classify the breed of dogs for dog images.
Evaluate and compare ResNet, AlexNet, and VGG architectures.
Assess computational efficiency and propose alternative "good enough" solutions.
## Features

Utilizes pretrained CNN models from PyTorch.
Reads pet images from the provided pet_images/ folder.
Incorporates a custom classifier.py function for image classification.
Processes dognames from the dognames.txt file for accurate categorization.
Outputs performance metrics like classification accuracy and runtime for each model.
## How to Run

Clone the repository:

bash
Copy code
git clone [repository-link]  
cd [repository-name]  
Execute the script with appropriate arguments:

bash
Copy code
python check_images.py --dir pet_images/ --arch resnet --dogfile dognames.txt  
Replace resnet with alexnet or vgg to test other architectures.

## Technologies Used

Python
PyTorch and torchvision
Command-line utilities
Pretrained CNN models (ResNet, AlexNet, VGG)
## Results

Comprehensive analysis of model accuracy and resource requirements.
Identification of the best CNN architecture for classifying dog images and breeds.
## Future Enhancements

Extend the project to other pet categories.
Implement a user-friendly GUI or web application for image upload and classification.
Improve performance with fine-tuning of pretrained models.
## Repository Structure

check_images.py: Main script with functionality to classify images and compare models.
classifier.py: Script to apply pretrained CNNs to classify images.
pet_images/: Folder containing pet images for testing.
dognames.txt: File listing valid dog names for reference.
