**Objective:**
Create and delete AWS S3 buckets using AWS CLI.

**Description:**
AWS S3 buckets are used to store and manage data (like files, images, videos, backups, etc.) in the cloud. 
They provide scalable, secure, and easily accessible storage for any amount of data.

**Steps:**

_**1. List all S3 buckets:**_
  aws s3 ls

_**2. Create two S3 buckets:**_
  aws s3 mb s3://bucket1-2310030445
  
  aws s3 mb s3://bucket2-2310030445


_**3. Delete the S3 buckets:**_
  aws s3 rb s3://bucket1-2310030445 
  aws s3 rb s3://bucket2-2310030445

**Result:**
Both S3 buckets were successfully created and deleted using AWS CLI commands.

_**Reference:**_
https://www.youtube.com/watch?v=r6fcpwB1IeQ

2310030445 - Vyshnavi Devi
