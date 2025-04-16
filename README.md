# cats_and_dogs_image_processing
Image Processing – Classify Cats and Dogs Using Deep Neural Network

## 1. Cat or Dog?
Image recognition is used to identify animal species for different tasks such as surveys and restrict
access. In this task, you are required to predict whether an image contains either a cat or a dog. Even
though a human being can easily differentiate between a cat and a dog, it is a tedious task that needs
full-time availability. We can use machine learning to find an automated solution for that.
You are given a labelled image dataset of cats and dogs as described in the next section. Using these
data, you need to train a machine learning model to predict whether an image has a cat or a dog. You
can use any machine learning algorithm to build the models, either from the sessions or your own
research based on the topics we discussed.

## 2. Data set
Within the data folder, there are two folders and two .csv files which are further described below.

train_images folder

Folder which contains the labelled images. Each image has an id as its name which is referred to by
the “train.csv” file.
Number of image files: 10,000
File format: .jpg

train.csv file
Details of training data to use with model training and validation.
Number of entries: 10,000
Columns:
- id – unique id assigned to each image in the train_images folder
- label – image label (cat or dog)

test_images folder

Folder which contains the test images. For these images, labels need to be predicted using the built
model.
Number of image files: 1,000
File format: .jpg

test.csv file

Testing data to use with predictions.
Number of entries: 1,000
Columns:
- id – unique id assigned to each image in the test_images folder
