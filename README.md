
# URL: [https://bit.ly/2RsMqpk](https://bit.ly/2RsMqpk)

# Register for an IBM Cloud account: http://ibm.biz/angelhack-c4c-sv-2019
Click on "Join the 2019 Challing Community" button.  

# Visual Recognition and Watson AI Services

<hr size="50" color ="blue">
<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# 1) Introduction

Natural disasters can’t be prevented but we can be better prepared. In this workshop you will learn about solutions to help with natural disasters preparedness/recovery. 

### [IBM Cloud](https://cloud.ibm.com/catalog)

### [Watson AI services](https://cloud.ibm.com/catalog?category=ai)

### [Watson Visual Recognition demo](https://www.ibm.com/watson/services/visual-recognition/demo/)

### [Visual Recognition Service Features](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/visual-recognition-overview.html)

### Data for Visual Rcognition: kaggle.com

### [Create a mobile app with visual recognition capabilities.](https://developer.ibm.com/patterns/visual-recognition-for-io)

### Visual Recognition Models

<img src="models.png">

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## 2) Step by Step Introduction to Visual Recognition in the IBM Cloud

1. [Select "Watson Visual Recognition service" in the IBM Cloud Catalog](https://cloud.ibm.com/catalog/services/visual-recognition). 
   Click on "Create" in bottom right corner to create an instance of the Watson Visual Recognition in the IBM Cloud
1. Click on the hamburger menu at the uppler left hand corner in the window and select
[Resource List](https://cloud.ibm.com/resources)
<img src="resource_list.png">

1. Click on your "Visual Recognition Service" in the Services Section. This is the Visual Recognition Service you just created.
1. Click on "Manage" in the upper left hand corner
1. Click on the "Show Credentials" to the right in the picture below to make it visible and then click on the "copy API 
   key icon: for later use. To invoke the Visual Recognition service we will need the API key.
   
   <img src="Visual_Recognition.png" height="400" width="600">

1. [Click "API Reference", shown in the picture above](https://cloud.ibm.com/apidocs/visual-recognition) for a description on how to invoke the Visual Recognition Service from Curl, Go, Java, Node, Python, Ruby, and Swift.

1. [This getting started tutorial](https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-getting-started-tutorial) guides you through how to use some built-in models in IBM Watson Visual Recognition to classify an image and then detect faces in an image.

1. [Working with the Visual Recognition API](https://cloud.ibm.com/apidocs/visual-recognition?code=try) brings us to the screen below  
<img src="/visual_recognitionapi.png">

1. [Visual Recognition Getting Started Tutorial ](https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-getting-started-tutorial#getting-started-tutorial)

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## 3) Create Visual Recognition Custom Model

1. From the IBM Cloud Catalog, create an instance of [Cloud Object Storage](https://cloud.ibm.com/catalog/services/cloud-object-storage) That is where we will store the images we will analyze.

1. Click on the hamburger menu in the upper left hand corner the IBM Cloud window

1. Click on the Resource List

1. Click on your Visual Recognition Service in the Resource List
 <img src="Visual_Recognition.png" height="400" width="600">
1. In the Visual Recognition service window, click on the blue Launch Watson Studio button. (The same window we see higher up in this tutorial

1. Then click on "Classify Images" and "Create Model" as shown in the picture below.

<img src="create_model.png">

<img src="new.project.png">

1. Fill in data and click "Create" in the lower right-hand corner.

<img src="visual.recognition.project.png">

In the next window we will create a class of visual objects such as dogs, which will
contain nothing but picturs of dogs, and a negative class, which will contain nothing but non-dogs,
in our case cats. We upload one zip-file of images of dogs and one zip-file of cats and then press on the blue
"Train Model" button in the upper right hand corner.

<img src="create.model1.png">

To analyze data in our newly created data model,
we click on the "Default Custom Model" in the topmost Actionbar "Projects", "Dogs", "Default Custom Model"
and then on "Test"

<img src="test.png">

We can nown begin to drag ansd drop images for testing our model.

<img src="thresh.png">

For the result of the dragging and. dropping see the next image below.

Data to analyze

1. https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/beagle.zip
1. https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/golden-retriever.zip
1. https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/husky.zip
1. https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/cats.zip


===============

### Visual Recognition Custom Model API calls

1. [Create a Classifier](https://cloud.ibm.com/apidocs/visual-recognition#create-a-classifier)
1. [Classify an Image](https://cloud.ibm.com/apidocs/visual-recognition#classify-an-image)
1. [Classify Images](https://cloud.ibm.com/apidocs/visual-recognition#classify-images)


1. [Create Visual Recognition Custom Models](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/visual-recognition-create-model.html) 

1. [Overview: Visual Recognition in Watson Studio](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/visual-recognition-sample-training-images.html?audience=wdp&linkInPage=true)

1. [Create Watson Studio service](https://cloud.ibm.com/catalog/services/watson-studio) 

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## 4)  Deploying the custom visual model on IBM Cloud and then use in your applications 

[YouTube: IBM Watson Studio: Get Started With Visual Recognition](https://www.youtube.com/watch?v=o8xxZcmuc2Q)

<img src="analyze_results.png">

<img src="default.custommodel.png">


[Kaggle free datasets](https://www.kaggle.com/datasets)


# Integrating other Watson cognitive services in your applications

1. [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant)
1. [All AI services in the IBM Cloud](https://cloud.ibm.com/catalog?category=ai)
1. [Speech to Text](https://www.ibm.com/watson/services/speech-to-text/)


# [Watson Starter Kits](https://cloud.ibm.com/ developer/watson/starter-kits)

### IBM Code Patterns.  

1. [A beginner’s guide to setting up a visual recognition service](https://developer.ibm.com/articles/a-beginners-guide-to-set-up-a-visual-recognition-service/)
1. [Identify Cities from Space](https://developer.ibm.com/patterns/identify-cities-from-space-using-watson-visual-recognition/)
1. [Classify Vehicle Damage Images](https://developer.ibm.com/patterns/classify-vehicle-damage-images/)
1. [Optimize your visual recognition classification](https://developer.ibm.com/patterns/optimize-visual-recognition-classification/)
1. [Create a real-time object detection app using Watson Machine Learning](https://developer.ibm.com/patterns/create-a-real-time-object-detection-app-using-watson-machine-learning/)

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# Appendix

1. custom image classifier with Watson Visual Recognition 

1. deploying the custom visual model on IBM Cloud and then use it in your applications 

1. integrating other Watson cognitive services in your applications.

###  Sign up for Call for Code: [https://ibm.biz/Bdz4SD](https://ibm.biz/Bdz4SD)

[White listing:](https://cloud.ibm.com/registration/whitelist)

# Updates from the command line:

1. [https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-tutorial-custom-classifier#tutorial-custom-classifier](https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-tutorial-custom-classifier#tutorial-custom-classifier)
1. [Best practices for custom classifiers in Watson Visual Recognition](https://www.ibm.com/cloud/blog/watson-visual-recognition-training-best-practices)
1.[Coinmonks](https://medium.com/coinmonks/watson-visual-recognition-custom-models-9cbcc20a6f98)
1.[Visual Recognition API[(https://cloud.ibm.com/apidocs/visual-recognition) 
