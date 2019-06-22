# 2019-06-29-30-School-42
# Image recognition
## Introduction
Natural disasters can’t be prevented but we can be better prepared. In this workshop you will learn about solutions to help with natural disasters preparedness/recovery. You will learn about: 

1. custom image classifier with Watson Visual Recognition 
1. deploying the custom visual model on IBM Cloud and then use in your applications 
1. integrating other Watson cognitive services in your applications.

<hr size="50" color ="blue">

## Step by Step

1. [IBM Cloud Catalog](https://cloud.ibm.com/catalog)
1. [IBM AI resources in the IBM Cloud](https://cloud.ibm.com/catalog?category=ai)
1. [Watson Visual Recognition in the IBM Cloud. Click on "Create" in bottom right corner to create an instance of the Watson Visual Recognition in the IBM Cloud ](https://cloud.ibm.com/catalog/services/visual-recognition)
1. [Your cloud Resources in the IBM Cloud, including Watson Visual Recognition. Click on your" Visual Recognition Recognition Service"](https://cloud.ibm.com/resources)

<img src="Visual_Recognition.png" height="400" width="600">

Save API key for later use

1. [Click on Visual Recognition Service](https://cloud.ibm.com/apidocs/visual-recognition?code=try)
1. [Visual Recognition API Docs](https://cloud.ibm.com/apidocs/visual-recognition)
1. [Visual Recognition](https://cloud.ibm.com/services/watson-vision-combined/)
1. [Try it out](https://cloud.ibm.com/apidocs/visual-recognition?code=try)

[This tutorial guides you through how to use some built-in models in IBM Watson™ Visual Recognition to classify an image and then detect faces in an image.](https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-getting-started-tutorial)

# Classify an image

curl -u "apikey:{apikey}" "https://gateway.watsonplatform.net/visual-recognition/api/v3/classify?url=https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/640px-IBM_VGA_90X8941_on_PS55.jpg&version=2018-03-19"

<img src="classify_image.png"     height="200" width="600">

1. curl -u apikey:XXXXXXXX
1. https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-getting-started-tutorial#classify 

To classify an image we need the following data:

1. Our API key: covered as:XXXXXXXX
1. The Watson Visual Recognition API: https://gateway.watsonplatform.net/visual-recognition/api/v3/classify
1. The image which is stored in github "watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/640px-IBM_VGA_90X8941_on_PS55.jpg&version=2018-03-19"

[Classify an image](https://cloud.ibm.com/docs/services/visual-recognition?topic=visual-recognition-getting-started-tutorial#classify)

curl -u apikey:XXXXXXXX  "https://gateway.watsonplatform.net/visual-recognition/api/v3/classify?url=https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/640px-IBM_VGA_90X8941_on_PS55.jpg&version=2018-03-19"

## output:

<code>

{
    "images": [
        {
            "classifiers": [
                {
                    "classifier_id": "default",
                    "name": "default",
                    "classes": [
                        {
                            "class": "circuit board",
                            "score": 0.578,
                            "type_hierarchy": "/electrical device/computer circuit/circuit board"
                        },
                        {
                            "class": "computer circuit",
                            "score": 0.755
                        },
                        {
                            "class": "electrical device",
                            "score": 0.757
                        },
                        {
                            "class": "disk controller",
                            "score": 0.553,
                            "type_hierarchy": "/controller/disk controller"
                        },
                        {
                            "class": "controller",
                            "score": 0.558
                        },
                        {
                            "class": "central processing unit",
                            "score": 0.535
                        },
                        {
                            "class": "PC board",
                            "score": 0.501,
                            "type_hierarchy": "/electrical device/computer circuit/PC board"
                        },
                        {
                            "class": "CPU board",
                            "score": 0.5,
                            "type_hierarchy": "/electrical device/computer circuit/CPU board"
                        },
                        {
                            "class": "electronic equipment",
                            "score": 0.6
                        },
                        {
                            "class": "memory device",
                            "score": 0.599
                        },
                        {
                            "class": "microchip",
                            "score": 0.592
                        },
                        {
                            "class": "jade green color",
                            "score": 0.838
                        },
                        {
                            "class": "emerald color",
                            "score": 0.787
                        }
                    ]
                }
            ],
            "source_url": "https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/640px-IBM_VGA_90X8941_on_PS55.jpg",
            "resolved_url": "https://watson-developer-cloud.github.io/doc-tutorial-downloads/visual-recognition/640px-IBM_VGA_90X8941_on_PS55.jpg"
        }
    ],
    "images_processed": 1,
    "custom_classes": 0
}

</code>




