# Object Detection Performance Testing on AWS Serverless Environments

This repository contains performance test reults of various object detection algorithms (YOLO, SSD, Faster R-CNN) deployed on AWS Lambda, AWS Fargate, and SageMaker Serverless Endpoints. 
Tests are conducted using the OpenCV Deep Neural Networks (DNN) module. 

See [ocv-dnn-detector](https://github.com/rosealexander/ocv-dnn-detector), 
[ocv-dnn-lambda-handler](https://github.com/rosealexander/ocv-dnn-lambda-handler).

## Directories

- **images:** Images from the Common Objects in Context (COCO) dataset that have been used for testing.

- **results:** Latency metrics of performance on different AWS platforms.

## Licensing

Both COCO images and results are under Creative Commons 4.0.
