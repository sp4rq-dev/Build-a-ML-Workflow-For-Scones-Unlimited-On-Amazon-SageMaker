# My Amazon SageMaker ML Workflow Project

In this project, I successfully completed a comprehensive Machine Learning (ML) workflow for Scones Unlimited using Amazon SageMaker. The project was divided into several phases, each with specific criteria for success. Here's a summary of my achievements in each phase:

## Setting Up SageMaker Studio Workspace

I began by setting up my SageMaker Studio workspace. This involved creating a workspace and configuring a kernel to run the project efficiently.

## Preparing Data for Machine Learning

To prepare the data for machine learning with SageMaker, I completed the ETL (Extract, Transform, Load) section of the starter code. This crucial step ensured that the data was ready for model training.

## Training and Deploying the ML Model

One of the key milestones was successfully training an image classification model in SageMaker. I followed the instructions up to the "Getting ready to deploy" section, which demonstrated that I had trained the model effectively. After training, I proceeded to construct an API endpoint associated with the model. This involved deploying the trained ML model, obtaining a unique model endpoint name, and successfully making predictions using a sample image.

## Building a Full ML Workflow

I authored three Lambda functions to create a complete ML workflow. Each Lambda served a specific purpose:
- The 1st Lambda was responsible for returning an object to the step function as image_data in an event.
- The 2nd Lambda handled image classification.
- The 3rd Lambda filtered low-confidence inferences. I saved the code for each Lambda function in a Python script.

I then composed these Lambdas together in a Step Function, exporting a JSON definition that defined the entire workflow. I also provided a screenshot to demonstrate the working Step Function, showcasing how the Lambdas were orchestrated to achieve a seamless workflow.

## Monitoring the Model for Errors

In the final phase, I extracted monitoring data from S3 and loaded it into my notebook. I also visualized Model Monitor data, creating custom visualizations of the Model Monitor data outputs to ensure the model's performance and identify potential errors.

Throughout this project, I followed the provided project materials and documentation to meet the specified criteria and deliver a successful end-to-end ML workflow for Scones Unlimited using Amazon SageMaker.

This experience has not only equipped me with practical skills in setting up ML workflows but also deepened my understanding of machine learning processes and best practices. It has been an enriching journey, and I am excited to apply these skills to future projects.