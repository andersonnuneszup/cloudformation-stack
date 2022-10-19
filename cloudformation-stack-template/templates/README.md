# About cloudformation-stack
* Project destined to create a simple yaml file to create the structures ECR, S3 Bucket, Dynamo Table and Lambda Function using the cloudformation tecnology.

## Objective
* The purpose of this stack is to make it easier for the developer to create a basic infrastructure on amazon using cloudformation technology. With the examples in this stack, a lot of research time will be saved.

## Prerequisites
* It is necessary that the user has an aws account with permission to create the structures contemplated in the yaml of the template.

## How to use
* There are some settings in the file that must be modified for user environment data. They are marked as "<>" tags
* Sign in to the AWS Management Console and open the AWS CloudFormation console at https://console.aws.amazon.com/cloudformation.
* If this is a new CloudFormation account, choose Create New Stack. Otherwise, choose Create Stack.
* In the Template section, select Specify an Amazon S3 Template URL to type or paste the URL for the sample template, and then choose Next
* In the Specify Details section, enter a stack name in the Name field. The stack name can't contain spaces.
* On the Specify Parameters page, you'll recognize the parameters from the Parameters section of the template. You must provide values for all parameters that don't have default values, including DBUser, DBPassword, DBRootPassword, and KeyName. In the KeyName field, enter the name of a valid Amazon EC2 pair in the same region you are creating the stack.
* Choose Next.
* Review the information for the stack. When you're satisfied with the settings, choose Create.
* Your stack might take several minutes to create – but you probably don't want to just sit around waiting. If you're like us, you'll want to know how the stack creation is going.
- For more details you can check the documentation from the link below: https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-reference.html