aad image here
## Foreword
Focus on the learning and certification will follow. Certification should never be the Target. Your ability to comprehend and apply those learnings should be.

## What is this?
> You can never understand everything but you should push yourself to understand the system.<br/>
> *-Ryan Dahl (creator of Node.JS)*

This a complete guide for achieving AWS certified developer mettle. It comprises of notes, lab works, exam break down, essential tips and probable questions that could be asked. Each topic in the content has 3 sections; Notes, then the practical work you should do and lastly dozens of questions that can be asked in the AWS Certified Developer Exam related to that topic.

## Contents
1. API Gateway
1. CICD
1. CloudFormation
1. CloudWatch
1. DynamoDB & RDS
1. EC2 & Elasticache
1. Elastic Beanstalk
1. IAM
1. Kinesis
1. KMS
1. Lambda
1. Route53
1. S3
1. SQS
1. SNS
1. SWF
1. VPC


## Exam Blue Print
Deployment 22%<br/>
Security 26%<br/>
Development with AWS Services 30%<br/>
Refactoring 10%<br/>
Monitoring and Troubleshooting 12%<br/>

Exam Duration: 130 Minutes<br/>
Total Questions: 65 Questions<br/>
Maximum Score 1000<br/>
Passing is 720<br/>
Resuts are available immediately.<br/>
In case you were unsuccessful you can always retake the exam , 14 days after yor first attempt.<br/>
The certification is valid for 3 years.<br/>


## Question Category Breakdown

IAM

Questions will definetly be asked from IAM including IAM role for DynamoDB, Web Federation, Corporate network, CloudFront, Elastic Beanstalk, Cloud Formation and Elastic Cache.
Options on authenticating using LDAP together with IAM.

S3 ~ 12 Questions.

CORS, Static Hosting, S3 Encryption Header, S3 Performance optimisation(Mostly on adding uniqueness before the key), Bucket policy and ACL (basically how to restrict), Limits (like total bucket)

DynamoDB ~ 12 Questions

Basic questions about Hash and range key, DynamoDBStreams, Throughput error (like if not Table then what is the cause), One question on write throughput calculation.

EC2 ~ 5 Question

Less questions from EC2 as they are focusing more on serverless. Basic API like DescribeImages, AMI related(example EC2 can be launched from the same region where AMI is stored) and Root Device Encryption. Also one question regarding EC2 instance profile. One question about EBS and multi container docker.

SQS  ~ 6-7 Questions

Basic SQS functionality, Protocols used and, Long Polling, Max Visibility and Timeout Scenario Questions. One question about grouping messages by messageid in SQS.

SNS ~ 4-5 Questions

Basic Functionality, Do check the Format of the SNS Notification and Field used in (JSON ), Fanout concept.

SWF ~ 1-2 Questions

Basic Functionality Scenario Based(like what all the functionally used by SWF)

VPC ~ 5 Questions
All scenario based 2-3 lines revolving around assigning Elastic address or public address to access the instance and NAT in subnet. One question related to VPC flow logs.

Kinesis ~ 2-3 Questions
Questions about Kinesis Client Library and resharding.

API Gateway
How to solve api gateway autodeployment with SAM.
How the user(client) can evict API gateway cache.

Note: 
1. Know/review limits for S3, DynamoDB, EC2, SNS, and SQS. 
1. Understanding the service limits would help with at least 5 questions.
1. Also know which AWS services are key-based and which platforms Elastic Beanstalk supports and which resources it can create.
1. One question about chosing Fargate over ECS when you don't want to take care of everything yourself and you can leave it to AWS :)
1. Resharding (KCL), Evicting API cache (Default not DLB), Fargate, Glue and VPC/Security Groups (?)
1. Acess Control Lists vs Security Group
1. Rest Questions were on AWS SDK, Default region (us-east-1) and Elastic Beanstalk Platforms and Elastic Cache to avoid the session state problem.  

## Some Essential Tips
1. Do Practice Tests on AWS Cloud Guru and other sites.
1. Lookout for scenario based questions.
1. Confirm big focus on DynamoDB (~15/55 questions) and S3 (~12/55 questions)
1. Attempt all questions as there are no negative marks.
1. If you have a long question, read the full question once and then only re read the last one or two lines as the real question lies there.
1. Practise the art of elimination! Eliminate the options that you are sure are not correct.

## Important Links

1. https://acloud.guru/forums/aws-certified-developer-associate/discussion/-KBkBPMHpN2ITSH1oDTO/passedwith90%25-myexamtips
1. https://docs.aws.amazon.com/streams/latest/dev/kinesis-record-processor-scaling.html
1. Linux Academy Course
1. Whiz Labs Test
1. https://acloud.guru/forums/aws-certified-developer-associate/discussion/-KUdI5f2LNbi4wvK7v4I/howtopassawscertified_deve
