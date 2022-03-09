# Deep Learning with Keras and AWS Lambda

> Deep learning achieves the best performance for computer vision, natural language processing, and recommendation tasks.
> 
> However, it’s difficult to use deep learning in production: it requires a lot of effort to develop proper infrastructure for serving deep learning models. Platforms for serverless computing, such as AWS Lambda, provide a good alternative: they take care of scaling up and down and offer attractive pricing based only on actual usage.
> 
> In this workshop, you'll learn how to do a deep learning project end-to-end. First, we will use Keras to train an image classification model that classifies pictures of clothes. Then we’ll deploy this model with AWS Lambda and TensorFlow-Lite.
>
> After finishing, you’ll be able to train a similar model and host it in the cloud. 

## Links

* [DataTalks.Club](https://datatalks.club/) - the community of people who love data
* [Machine Learning Bookcamp](https://mlbookcamp.com/) - the book on which the workshop is based
* [ML Bookcamp Github Repo](https://github.com/alexeygrigorev/mlbookcamp-code) - all the code from the book
* [Machine Learning Zoomcamp](http://mlzoomcamp.com/) - free course based on the book


## Part 1: Image Classification with TensorFlow and Keras

TODO: add the registration link

### Segment 1: Introduction

* About the instructor
* What we’ll cover today
* How to set up the environment — AWS, Anaconda + Jupyter, TensorFlow + Keras, Docker, VS Code
* The first look at the dataset

### Segment 2: Training the first model

* Loading and preparing data
* Transfer learning with Keras
* Training a small model on a GPU
* Saving the model and using it

### Segment 3: Improving the model

* Adding more layers
* Checkpointing: saving the best version of our model
* Making model generalize better: adding dropout
* Generating more data with data augmentation
* Training a larger model
* Testing the model: applying it to test data


## Part 2: Deploying Deep Learning Models with AWS Lambda 

TODO: add the registration link

### Segment 1: AWS Lambda

* What is AWS Lambda
* Implementing a simple Lambda function
* Lambda and Docker 

### Segment 2: TenserFlow-Lite

* TensorFlow vs TensorFlow-Lite
* Converting Keras models to TF-Lite
* Making predictions with TF-Lite
* Using keras-image-helper for pre-processing of images

### Segment 3: AWS Lambda + TF-Lite

* Putting everything together
* Preparing a Docker file 
* Using a pre-compiled version of TF-Lite for AWS Lambda
* Testing Lambda code locally
* Uploading the docker image to ECR 
* Creating and testing a Lambda function
  
### Segment 4: API Gateway

* Putting the Lambda function in a web service
* Using the webservice for image classification


## Extra resources

* [CS231n](https://cs231n.github.io/) - a course about neural networks for computer vision
* [Creating an AWS account](https://mlbookcamp.com/article/aws)
* [Tutorial about Lambda and API Gateway](https://github.com/alexeygrigorev/aws-lambda-docker/blob/main/guide.md)
* [Requesting a quota increase for AWS Sagemaker](https://livebook.manning.com/book/machine-learning-bookcamp/appendix-e)
