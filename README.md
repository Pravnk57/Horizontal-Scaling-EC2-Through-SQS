# Horizontal-Scaling-EC2-Through-SQS
## Automatically Scale out whenever someone puts an object in an S3 bucket.

![scale_through_sqs](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/ba32871f-3f1f-42f6-be08-e1562c71a1ee)


# Project Description:
This is a simple proof of concept we are going to build for the fun purpose in which whenever someone drops an object in an s3 bucket it will create 
an EC2 instance automatically.

## Step 1: 
### Creating an S3 bucket:
1. Navigate to S3 console.
2. Follow the outlined steps.

![image (93)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/d087d4b7-e61c-4084-815e-fccfcdc9627b)

![image (94)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/00f1a725-adca-4408-bbcf-f14a9c67e6f6)

### Step 2 :
### Creating the Amazon SQS :

1. Navigate to SQS console.
2. Follow the outlined steps.
![image (95)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/0f4f64db-c22c-43ed-8e19-6b2733cbe2f3)

![image (96)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/1210d1d1-63f4-465e-8349-d49ce23f09e8)

![image (97)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/7aad56eb-a8e1-46cd-a7e7-e438074bea98)

![image (98)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/ac30ef09-7bef-47a2-a040-f8478d442932)

### Step 3 :
### Creating an Event Notification for S3:

1. Navigate to S3 console.
2. Follow the outlined steps.
3. Go to the bucket Properties.

![20 04 2024_11 11 36_REC](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/82fd8533-6f8c-4206-91e0-e7b35f2c03a7)
![image (99)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/5e7fcf2d-2ab3-4146-829a-7cfccf835529)

![image (100)](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/c4f8844d-695e-4754-b483-8b909ec6ca82)

![image - 2024-04-20T112451 773](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/0d64d496-9d17-414d-b474-e26ba4172a67)

![image - 2024-04-20T112946 248](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/82c82353-07db-4faf-8f66-36dd136149a5)

![image - 2024-04-20T113255 443](https://github.com/Pravnk57/Horizontal-Scaling-EC2-Through-SQS/assets/117705143/e779093e-f323-4c78-8d0d-41e91e843ced)

















































































