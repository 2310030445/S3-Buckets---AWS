Objective:
Create and delete AWS S3 buckets using AWS CLI.

Description:
AWS S3 buckets are used to store and manage data (like files, images, videos, backups, etc.) in the cloud. 
They provide scalable, secure, and easily accessible storage for any amount of data.

Steps:

1. List all S3 buckets:
  aws s3 ls

2. Create two S3 buckets:  
  aws s3 mb s3://bucket1-2310030445
  aws s3 mb s3://bucket2-2310030445


3. Delete the S3 buckets:
  aws s3 rb s3://bucket1-2310030445
  aws s3 rb s3://bucket2-2310030445

Reference:
https://www.youtube.com/watch?v=r6fcpwB1IeQ
