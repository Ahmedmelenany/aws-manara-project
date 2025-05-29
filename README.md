# aws-manara-project

- Designing and Deploying a simple web application on AWS using EC2 instances, ensuring high availability and scalability with Elastic Load Balancing (ALB) and Auto Scaling Groups (ASG). 

## Key AWS Services Used:
- EC2: Launch instances for the web app.
- Application Load Balancer (ALB): Distributes traffic across multiple instances.
- Auto Scaling Group (ASG): Ensures instances scale based on demand.
- CloudWatch & SNS: Monitor performance and send alerts
- IAM: Role-based access to instances.

![diagram](./Architecture.png)

## Setup

### Application Load Balancer

![ALB](./Images/ALB.png)

### Auto Scaling Group

![ASG](./Images/ASG.png) 

### CloudWatch

![Alarm](./Images/CloudWatch-alarms.png) 

### Simple Notifications Service 

![SNS](./Images/SNS-topic.png) 

![email](./Images/SNS-topic-email.png) 

### EC2 Targets

![target](./Images/target-1.png) 

![target1](./Images/target-2.png) 

