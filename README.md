# Deploying a Static Website using AWS CodePipeline and S3

AWS CodePipeline and AWS S3 bucket can be used together to automate the deployment of static websites. CodePipeline is a continuous delivery service that automates the steps required to release your software changes. S3 is an object storage service that can be used to host static websites.

To deploy a static website using CodePipeline and S3, you will need the following:

- A CodeCommit repository to store your website files.
- An S3 bucket to host your website.
- A CodePipeline pipeline to automate the deployment process.

The CodePipeline pipeline will typically have the following stages:

1. **Source Stage**: Fetches the latest version of your website files from CodeCommit.
2. **Build Stage**: Compiles and packages your website files.
3. **Deploy Stage**: Copies your website files to the S3 bucket.

Once the CodePipeline pipeline is created, it will automatically deploy your website whenever you make changes to your website files in CodeCommit.

## Steps to Deploy a Static Website using AWS CodePipeline and S3:

1. Create a CodeCommit repository to store your website files.
2. Create an S3 bucket to host your website.
3. Configure the S3 bucket for website hosting.
4. Create a CodePipeline pipeline.
5. Configure the CodePipeline pipeline stages.
6. Test the CodePipeline pipeline.
7. Deploy your website.

## Task completion

Step-by-step process of task completion has detailed description in prepared material on moodle LMS (AWS_CodePipeline_CodeCommit).

In source file `index.html` should be added string like `Author: YourName YourSurname YourGroup`

As a proof of succefully completed task should be provided URL of created static website, like follows:<br> 

[http://singlepage-webapp.s3-website.eu-central-1.amazonaws.com/](http://singlepage-webapp.s3-website.eu-central-1.amazonaws.com/)

## Additional Resources:

Here are some additional resources that you may find helpful:

- AWS CodePipeline documentation: [https://docs.aws.amazon.com/codepipeline/latest/userguide/](https://docs.aws.amazon.com/codepipeline/latest/userguide/)
- AWS S3 documentation: [https://docs.aws.amazon.com/AmazonS3/latest/userguide/](https://docs.aws.amazon.com/AmazonS3/latest/userguide/)
- Tutorial: Deploy a static website to Amazon S3: [https://docs.aws.amazon.com/codepipeline/latest/userguide/tutorials-s3deploy.html](https://docs.aws.amazon.com/codepipeline/latest/userguide/tutorials-s3deploy.html)
- Deploying a Static Website on AWS S3 with AWS CodePipeline: [https://adamtheautomator.com/aws-codepipeline/](https://adamtheautomator.com/aws-codepipeline/)

