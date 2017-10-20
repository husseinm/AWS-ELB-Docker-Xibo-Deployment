# AWS Deployment of Xibo Sign CMS

Steps to make this (Start at 4 for simple Deployment):
1) Download the latest Xibo Docker zip
2) Use https://github.com/micahhausler/container-transform
3) Make sure to update the Volumes from ```./shared/...``` to ```/var/app/current/shared/...```
4) Upload the Dockerrun.aws.json file to Elastic Beanstalk
