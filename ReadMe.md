# AWS Solutions Architect Associate

## Context
- [I am a software architect](https://www.linkedin.com/in/aamirmulla/) having worked primarily in the application development space, not networking. 
- I have done so on premise, in Heroku and Azure. 
- I have also worked on PoCs (proof of concepts) across GCP and AWS.
- I also sat the AWS developer associate exam in 2019, but never used it in production since.
- With my workplace now gravitating towards AWS more recently, I want to prepare myself and tick off AWS solutions architect associate exam as well.
- Exam is scheduled for next week, and these will be my last shrinking set of notes before I sit it.

## Acknowledgements
- I have used https://learn.cantrill.io/ as my primary resource for learning, based on recommendation of my ex-colleague and friend [Shawn Jiang](https://www.linkedin.com/in/shawnjiang/). I would reccomend it highly too now, as Adrian (the author) not only covers the exam, but uses nice diagrams and concise explanations in shorter than 20 minute lessons.

## Let's do it!
Notes
General
The S3 9s
learnt he ec2 class names... instanace type names - acronyms?
s3 object size max 5TB
RDS for sql server has native mirroring feature
hibernate ec2 - keep processes and RAm contents in EBS, but instance store is wiped like a stop/start
iot greengradd and amazont ime strwma
encrypt ec2
db billing?
gateway load balancers
ec2 costs
Domain 1: Design Secure Architectures
CloudHSM
FIPS 140-2 Level 3 is CloudHSM, Level 2 is KMS
CloudHSM accessed via standard crpto APis like PKCS#11,JCE and CryptoNG unlike KMS
Secrets manager [saves and] rotates secrets unlike SSM parameter store
Domain 2: Design Resilient Architectures
FIFO delivers exactly once
FIFO quotes must have a .FIFO suffix in name
Domain 3: Design High-Performing Architectures
AWS s3 cp cli command automatically use multi-part upload as necessary
AWS Privat link setup connection
Domain 4: Design Cost-Optimized Architectures
AWS Systems Manager Session manager cost effective for dev access
cluster placement group numbers
‘maintenance’ page for when the application is offline or has failed. route53?
vpc connectivity
dynamodb rcu 4kb
OAI s3
s3 stotrage clases
sqs long polling

