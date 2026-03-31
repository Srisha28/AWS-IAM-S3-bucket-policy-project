# Project 6: AWS IAM and S3 Bucket Policy

## Objective
To demonstrate AWS IAM and S3 bucket policies by restricting a user from deleting an S3 bucket.

## Steps Performed
1. **Created Bucket:** Created a new S3 bucket named `project-test-bucket-2026`.
2. **Applied Policy:** Applied a bucket policy with an explicit `Deny` effect for the actions `s3:DeleteBucket` and `s3:DeleteObject`.
3. **Tested Restriction:** Attempted to delete the bucket and successfully received the "Access Denied" permission error, proving the policy works.
4. **Cleanup:** Removed the policy and successfully deleted the bucket to clean up resources.
