[//]: # (Image References)

[image1]: ./images/sample_dog_output_2.png "Sample Output"
[image2]: ./images/sample_human_output_2.png "Sample Output_2"
[image3]: ./images/sample_cat_output.png "Sample Output_3"
[image4]: ./images/sample_dog_output_3.png "Sample Output_4"

## Installation

Standard libraries installed with the Anaconda distribution.

python 3.7.6

pytorch 

torch

torchvision

glob2

## Project Overview

In this project, I developed an algorithm for classification of dog breeds. Given the user input image, the code will differentiate whether it is human, dog or neither. If a dog image is detected, it will identify an estimate of the canine’s breed.  If a human face is detected, the code will identify the resembling dog breed. Convolutional Neural Networks (CNN) models were developed for dog breed classification. 

![Sample Output][image1]
![Sample Output_2][image2]
![Sample Output_3][image3]
![Sample Output_4][image4]

## Project Instructions

### Instructions

1. Clone the original repository from Udacity and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
	
__NOTE:__ if you are using the Udacity workspace, you *DO NOT* need to re-download the datasets in steps 2 and 3 - they can be found in the `/data` folder as noted within the workspace Jupyter notebook.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```


