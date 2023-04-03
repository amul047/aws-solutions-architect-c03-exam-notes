# AWS Solutions Architect Associate Exam Notes

## Context
- [I am a software architect](https://www.linkedin.com/in/aamirmulla/) having worked primarily in the application development space, not networking. 
- I have done so on premise, in Heroku and Azure. 
- I have also worked on PoCs (proof of concepts) across GCP and AWS.
- I also sat the AWS developer associate exam in 2019, but never used AWS in production.
- With my workplace now gravitating towards AWS more recently, I want to prepare myself and tick off AWS solutions architect associate exam as well.
- Exam is scheduled for next week, and these will be my last shrinking set of notes before I sit it.

## Acknowledgements
- I have used https://learn.cantrill.io/ as my primary resource for learning, based on recommendation of my ex-colleague and friend [Shawn Jiang](https://www.linkedin.com/in/shawnjiang/). I would reccomend it highly too now, as Adrian (the author) not only covers the exam, but uses nice diagrams and concise explanations in shorter than 20 minute lessons.

## Let's do it!

AWS Systems Manager Session manager cost effective for dev access

dynamodb rcu 4kb

### Placement group limits
- 500 per account per region
- 7 per AZ if spread
- 7 partitions per AZ if partition
- account limits only if cluster

![image](https://user-images.githubusercontent.com/50348897/228983838-90b86432-ff8e-48de-9f64-7597bdec332c.png)

![image](https://user-images.githubusercontent.com/50348897/228986535-0cfffb29-2315-41e1-af49-4c2f6650f14a.png)

![image](https://user-images.githubusercontent.com/50348897/228990114-e675ecfe-1ec8-4b2f-be71-43dc1fc14c71.png)

![image](https://user-images.githubusercontent.com/50348897/228992213-10c461d6-4732-46c2-b840-893fec26068b.png)

![image](https://user-images.githubusercontent.com/50348897/229266311-65644fbe-cd81-43d7-9280-cc62dfc538e4.png)

### DR

![image](https://user-images.githubusercontent.com/50348897/229266830-4ec26a8c-3ae9-4fd0-a0de-c8fe6a425809.png)

### S3

|  | Limit |
|-------|-------|
| Max number of objects | Unlimited |
| Max size of 1 object | 5 TB |
| Max size of 1 upload without multipart / Max size of 1 part of multipart  | 5 GB |
| Size to consider multi-part | > 100 MB |
| Min size of 1 part of multipart | 5 MB |
| Max number of parts in multipart | 10000 |


