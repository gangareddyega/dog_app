# Udacity dog breed project

Build a pipeline to process real-world, user-supplied images.
Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human face, the code will identify the resembling dog breed.

## Detect Humans
Assess the Human Face Detector The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected, human face.

## Detect Dogs
Use a pre-trained VGG16 Net to find the predicted class for a given image: dog_detector function returns True if a dog is detected in an image and False if not.

Assess the Dog Detector The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected dog.

## CNN to Classify Dog Breeds from Scratch
CNN architecture of trained model attains at least 10% accuracy on the test set.

## CNN to Classify Dog Breeds Using Transfer Learning
Model architecture that uses part of a pre-trained model with accuracy on the test set of 40% or greater.

## Project Submission

When you are ready to submit your project, collect the following files and compress them into a single archive for upload:
- The `dog_app.ipynb` file with fully functional code, all code cells executed and displaying output, and all questions answered.
- An HTML or PDF export of the project notebook with the name `report.html` or `report.pdf`.
- Any additional images used for the project that were not supplied to you for the project. __Please do not include the project data sets in the `dogImages/` or `lfw/` folders.  Likewise, please do not include the `bottleneck_features/` folder.__

Alternatively, your submission could consist of the GitHub link to your repository.
