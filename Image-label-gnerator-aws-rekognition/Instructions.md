# image label generator using Amazon Rekognition

## What youll need:
- aws cli 
- s3 bucket to store images 
- iam role with cli, s3 and rekognition access

### install aws cli depends on operating system 
- https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html 

### Configure cli
- https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html

### Create Bucket (aws mb help)
```
aws s3 mb s3://unigue-bucket-name
```
### Upload local images (aws cp help) 
```
aws s3 cp image-name.jpeg s3://unique-bucket-name
```
### Install dependancies 

```
pip install boto3
pip install matplotlib
```
### update image_labels.py with your values and run.  
