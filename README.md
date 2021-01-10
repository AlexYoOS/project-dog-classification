
# DOG BREED CLASSIFIER 

This is the DogBreed Classifier Training Project of the Deep Learning ND of Udacity. 
In this project Convolutional Neural Networks (CNN) are built and trained.
There are numerous models applied in this project, so that this Classifier could be used in e.g. in a mobile app where decisions will be made, after the outcome of each model, plus additional features.

![Sample Output][image1]

The data processing pipeline is a great exercise to show complexities of real world applications, and what must be done, do come to a desired result.


## Instructions

Clone: 
	
	```	
		git clone https://github.com/AlexYoOS/project-dog-classification.git
	```
	
_The datasets are already in the repo, but can be found here;_
- [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
- [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  unzip into location `path/to/dog-project/lfw`
- Environment requirements are in the repo: requirements.txt

## Execution

Run the project in the jupyter notebook, and follow instructions:

	```
		jupyter notebook dog_app.ipynb
	```
You can use the checkpoint files in the repo:

- model_scratch.pt
- model_transfer.pt

Or train the model yourself if you have GPU capacities, e.g. AWS.

