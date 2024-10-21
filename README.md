# S3-SQS
Demo: Creating above architecture with S3 and SQS using AWS Console
Objective:
1. Create an S3 bucket using terraform
2. Create an SQS queue using terraform with any IAM policies needed
3. Link an upload activity in S3 to SQS such that it will trigger an alert notification.
a. Hint: Think of aws_s3_bucket_notification
4. Test your resources by going to your S3 bucket and uploading a non-sensitive file from your local machine. Open
another browser tab that contains your SQS created too.
5. If successful, you will see alerts from polled messages coming into SQS from your S3
