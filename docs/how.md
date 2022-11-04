# How are we doing this!
This site uses github actions to sync to an S3 bucket and Route 53.

The S3 buckets were made using [these](https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-custom-domain-walkthrough.html#add-bucket-policy-root-domain) instructions
  
[![ci](https://github.com/jordanisonline/digidiscussions/actions/workflows/ci.yml/badge.svg)](https://github.com/jordanisonline/digidiscussions/actions/workflows/ci.yml)  
☝🏽  
That just shows the status of the sync action  


The sync action im using is from this [repo](https://github.com/jakejarvis/s3-sync-action) 

## THE LAB IS NOT A PLACE. IT'S A STATE OF MIND
