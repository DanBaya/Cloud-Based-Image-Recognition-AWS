# Cloud-Based-Image-Recognition-AWS
Architected a fully cloud-native image identification system using Python on Amazon EC2, storing image data in Amazon S3, and leveraging Amazon Rekognition to generate labeled bounding boxes with confidence scores; visualized detection results using MATLAB.


Tech Stack

- Python (Boto3 SDK)
- AWS EC2
- AWS S3
- AWS Rekognition
- MATLAB

---

## Features

- Cloud-native architecture 
- Scalable and reusable workflow 
- Confidence-based filtering of results 
- Visual output with labeled bounding boxes 

---

## Example Output
Object: Person | Confidence: 98.7%
Object: Car | Confidence: 95.3%

---

##  Setup Instructions

### 1. AWS Setup
- Create an S3 bucket 
- Launch an EC2 instance 
- Configure IAM roles with access to S3 and Rekognition 

Instance type
t2.micro

IAM Permissions (Important)
Ensure your EC2 role includes:
AmazonS3FullAccess (or scoped bucket access)
AmazonRekognitionFullAccess

Future Improvements
Add CI/CD pipeline (GitHub Actions)
Deploy as serverless (AWS Lambda)

Author
Daniel Bayasgalan
