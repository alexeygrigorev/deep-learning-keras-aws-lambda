# Deep Learning with Keras and AWS Lambda

[Link for registration](https://learning.oreilly.com/live-events/deep-learning-with-keras-and-aws-lambda/0636920060925/0636920060924/)

> Deep learning achieves the best performance for computer vision, natural language processing, and recommendation tasks.
> 
> However, it’s difficult to use deep learning in production: it requires a lot of effort to develop proper infrastructure for serving deep learning models. Platforms for serverless computing, such as AWS Lambda, provide a good alternative: they take care of scaling up and down and offer attractive pricing based only on actual usage.
> 
> In this workshop, you'll learn how to do a deep learning project end-to-end. First, we will use Keras to train an image classification model that classifies pictures of clothes. Then we’ll deploy this model with AWS Lambda and TensorFlow-Lite.
>
> After finishing, you’ll be able to train a similar model and host it in the cloud. 


## Outline

### Segment 1: Introduction (10 minutes)

* About the instructor
* What we’ll cover today
* How to set up the environment — AWS, Anaconda + Jupyter, TensorFlow + Keras, Docker, VS Code
* The first look at the dataset

### Segment 2: Training the first model (35 minutes)

* Loading and preparing data
* Transfer learning with Keras
* Training a small model on a GPU
* Saving the model and using it

### Segment 3: Improving the model (35 minutes)

* Adding more layers
* Checkpointing: saving the best version of our model
* Making model generalize better: adding dropout
* Generating more data with data augmentation
* Training a larger model
* Testing the model: applying it to test data

### Segment 4: AWS Lambda (15 minutes)

* What is AWS Lambda
* Implementing a simple Lambda function
* Lambda and Docker 

### Segment 5: TenserFlow-Lite (30 minutes)

* TensorFlow vs TensorFlow-Lite
* Converting Keras models to TF-Lite
* Making predictions with TF-Lite
* Using keras-image-helper for pre-processing of images

### Segment 6: AWS Lambda + TF-Lite (40 minutes)

* Putting everything together
* Preparing a Docker file 
* Using a pre-compiled version of TF-Lite for AWS Lambda
* Testing Lambda code locally
* Uploading the docker image to ECR 
* Creating and testing a Lambda function
  
### Segment 7: API Gateway (10 minutes)

* Putting the Lambda function in a web service
* Using the webservice for image classification


More info coming soon!
