# DogBreed_Classifier

In this notebook, we will make the first steps towards developing an algorithm that could be used as part of a mobile or web app. At the end of this project, our code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

## Steps

Step 0: Import Datasets<br>
Step 1: Detect Humans<br>
Step 2: Detect Dogs<br>
Step 3: Create a CNN to Classify Dog Breeds (from Scratch)<br>
Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)<br>
Step 5: Write your Algorithm<br>
Step 6: Test Your Algorithm<br>

## Data

Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in this project's home directory, at the location /dogImages.
Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the home diretcory, at location /lfw.

## Testing Images

![](exampleImages/download.jpg)
![](exampleImages/download-1.jpg)
![](exampleImages/download-2.jpg)
![](exampleImages/download-3.jpg)
![](exampleImages/download-4.jpg)
![](exampleImages/download-5.jpg)

## Libraries Used
[PyTorch](https://pytorch.org)
