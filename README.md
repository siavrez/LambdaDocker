# DockerExample

This project contains source code and supporting files for a serverless application for classifying handwritten digits using a Machine Learning model in [scikit-learn](https://scikit-learn.org/). It includes the following files and folders:

- app/app.py - Code for the application's Lambda function including the code for ML inferencing.
- app/Dockerfile - The Dockerfile to build the container image.
- app/model - A simple scikit-learn model for classifying handwritten digits trained against the MNIST dataset.
- app/requirements.txt - The pip requirements to be installed during the container build.
- events - Invocation events that you can use to invoke the function.
- template.yaml - A template that defines the application's AWS resources.
- training.ipynb - A jupyter notebook to show the training process for the sample model at `app/model`.

