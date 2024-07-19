# Summer_Internship_SEM_7
I am Working as Cloud Intern at ScaleCapacity starting from 30th May.I am working on the object-detection using sagemaker and IoT greengrass.

[Link of dataset](https://www.kaggle.com/datasets/truongthanh081203/license-plate)

### Week-1
- Team introduction and induction.
- I was given some articles to explore on AWS Sagemaker and IoT greengrass.
- Explored the articles and did some basic rearch on object-detection and SSD.
- Find a dataset for ObjectDetection.
### Week-2
- Figured out the IAM policies for working with the sagemaker notebook
- Setup the notebook with the required dependencies and libraries.
- Uploaded the dataset and into default s3 of sagemaker and downloaded the dataset into jupyter notebook
### Week-3
- Find correct format for converting labels from YOLO to SSD format.
- Convert the Labels into a format Accepted by SSD.
- Save the dataset to default s3 of sagemaker.
- Generate list files from dataset.
- Prepare RecordIO files from list files.
### Week-4
- Find how to do hyperparameter-tuning job in sagemaker.
- Find which parameters are tunable for SSD and which must are mandatory to mention before starting Hyperparameter tuning job.
- Troubleshoot the Hyperparameter training job.
- Do the training job.
- Create a model group and register the the trained model
## Refrence
- https://docs.aws.amazon.com/sagemaker/latest/dg/object-detection.html 
