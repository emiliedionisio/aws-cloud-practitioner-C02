## Domain 1: Cloud Concepts (24% of scored content)

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/1-cloudconcepts.png)

#### 1.1: Define the benefits of the AWS Cloud
#### Knowledge of: Value proposition of the AWS Cloud
#### Skills in:
- Understanding the economies of scale (for example, cost savings)
- Understanding the benefits of global infrastructure (for example, speed of deployment, global reach)
- Understanding the advantages of high availability, elasticity, and agility

<!-- Type your questions and answers below -->

#### What is Cloud Computing?
Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing. On-demand delivery indicates that AWS has the resources you need, when you need them. 

#### What are the three deployment models for cloud computing, their definitions, and uses?
- Cloud-based Deployment Model, you can migrate existing applications to the cloud, or you can design and build new applications in the cloud. You can build those applications on low-level infrastructure that requires your IT staff to manage them.
  - Run all parts of the application in the cloud.
  - Migrate existing applications to the cloud.
  - Design and build new applications in the cloud.
- On-premises deployment is also known as a private cloud deployment.  In this model, resources are deployed on premises by using virtualization and resource management tools.
  - Deploy resources by using virtualization and resource management tools.
  - Increase resource utilization by using application management and virtualization technologies.
- Hybrid deployment, cloud-based resources are connected to on-premises infrastructure. You might want to use this approach in a number of situations. For example, you have legacy applications that are better maintained on premises, or government regulations require your business to keep certain records on premises.
  - Connect cloud-based resources to on-premises infrastructure.
  - Integrate cloud-based resources with legacy IT applications.







--------
#### 1.2: Identify design principles of the AWS Cloud
#### Knowledge of: AWS Well-Architected Framework
#### Skills in:
- Understanding the pillars of the Well-Architected Framework (for example, operational excellence, security, reliability, performance efficiency, cost optimization, sustainability)
- Identifying differences between the pillars of the Well-Architected Framework

#### 1.3: Understand the benefits of and strategies for migration to the AWS Cloud
#### Knowledge of:
- Cloud adoption strategies
- Resources to support the cloud migration journey
#### Skills in:
- Understanding the benefits of the AWS Cloud Adoption Framework (AWS CAF) (for example, reduced business risk; improved environmental, social, and governance (ESG) performance; increased revenue; increased operational efficiency)
- Identifying appropriate migration strategies (for example, database replication, use of AWS Snowball)

#### 1.4: Understand concepts of cloud economics
#### Knowledge of:
- Aspects of cloud economics
- Cost savings of moving to the cloud
##### Skills in:
- Understanding the role of fixed costs compared with variable costs
- Understanding costs that are associated with on-premises environments
- Understanding the differences between licensing strategies (for example, Bring Your Own License [BYOL] model compared with included licenses)
- Understanding the concept of rightsizing
- Identifying benefits of automation (for example, provisioning and configuration management with AWS CloudFormation)
- Identifying managed AWS services (for example, Amazon RDS, Amazon Elastic Container Service [Amazon ECS], Amazon Elastic Kubernetes Service [Amazon EKS], Amazon DynamoDB)

ASSIGNMENT 1
What is Cloud Computing? The on-demand delivery of IT resources over the internet with pay-as-you-go pricing.

What are the three deployment models for cloud computing, their definitions, and uses? On-Premises, Hybrid Deployment, Cloud Deployment
What are the Benefits of cloud computing and their definitions?Run all parts of the application in the cloud.
Migrate existing applications to the cloud.
Design and build new applications in the cloud
What are the Amazon EC2 instance types and their definitions?-General purpose- balanced
-Compute optimized - compute intensive, high performance processors
-Memory optimized- memory intensive, high performance databases
-Accelerated computing- floating point
-Storage optimized- high performance storage
What is a Load Balancer? Host to route orders and balance
ensuring even distribution to instances
application that takes into request to load instances
What is the primary purpose of AWS Regions in the global infrastructure? Regions act as integrated networks to allow for communications throughout the world
Describe the function of Amazon CloudFront in AWS's architecture.
How do AWS Edge locations enhance the performance of Amazon CloudFront? Infrastructural code
JSon or Yamil define what you want to build not how
storage, database, analytics
Explain how Amazon Route 53 integrates with AWS Edge locations to enhance user experiences. Directs customers to locations with low latency thereby resulting in low disruption of customer's business
What are the advantages of using AWS Outposts for local data processing needs? Allowing for local onsite AWS processing in a specific building 
How are AWS Lambda and AWS Outposts different in what they offer for cloud computing? Lambda is where code is pushed to the cloud and AWS institutes the changes from there in AWS Outposts the business is extending and running native AWS on premises.
What is high availability? In service availability, the services are able to ramp to a high level of operational performance consistently without failure.
What are the benefits of AWS having a global infrastructure with multiple regions? High availability and fault tolerance
Operating in regions
What is an AWS Region?Data centers in a region has multiple data centers
Why is data sovereignty important in AWS Regions? 1. Compliance: Requirements under a regulatory control
2.Proximity: How close to customer base?
- Latency: Time to send data
3. Feature Availability: based on customer request and needs AWS 

AWS Braket: Quantum computing software can only be run in certain areas
4. Pricing: Cost can be different than other regions
Transparent pricing 

How do AWS Regions enhance disaster recovery capabilities? Providing ultimate protection and fail over recovery in case of a disaster
What are the four main factors to consider when choosing an AWS Region? Compliance, Proximity, Feature Availability, Pricing
What is an AWS Availability Zone? Running multiple instances in various distances
What is the purpose of having multiple Availability Zones within an AWS Region? Prevent fail over provide more stability to client applications
How does AWS ensure low latency communication between Availability Zones? Using Route 53 concept
Why is it important to run EC2 instances across multiple AZs? Maximize fail over coverage
How do regional AWS services enhance high availability? Maximize coverage
What is the purpose of Amazon CloudFront? Infrastructural code
JSOn or Yamil define what you want to build not how
storage, database, analytics
What are edge locations in AWS?  delivery edge locations accelerates communication
What is AWS Outposts? Extend and run native AWS services on premises of a business
How do Availability Zones within AWS Regions contribute to disaster recovery and high availability? Maximize coverage and prevent fail over disaster
How do AWS Edge locations and Amazon CloudFront improve content delivery? Provided low latency
What is an API in the context of AWS? Application Program Interface
What is the primary method of interacting with AWS services? AWS Management Console
What are the main ways to interact with AWS services? Console, CLI and SDK
Why is automation important in cloud deployment? Provides consistency, allows for timed updates and allows for scheduling of updates
What is the primary advantage of using AWS Elastic Beanstalk over manual methods like the AWS Management Console?Provision Amazon EC2 instances- App code to Beanstalk to build out
What is AWS Elastic Beanstalk used for? provisioning
How does AWS CloudFormation help in managing AWS resources?Infrastructural code
JSOn or Yamil define what you want to build not how
storage, database, analytics
What are the main components of AWS Global Infrastructure?High availability and fault tolerance
Operating in regions
Which AWS services automatically run across multiple Availability Zones? EC2 instances
What is the recommended best practice for deploying infrastructure in AWS? CLI and automation
Answer the following questions about the topics in AWS Educate: Getting Started with Compute Lab and type the questions and answers on GitHub under Domain 1.
What is Amazon EC2? Virtual server "an instance"
What is Amazon EC2 and its primary benefits? No hardware, scalability, less experience needed, time/ cost savings, easy connectivity
What is a Security Group in EC2? Virtual firewall that allows: Control of traffic for the EC2 instance
What are the four main purchasing options for EC2 instances, and what are their key characteristics? - On-Demand: Per hr or per sec usually for start up service; use for baseline
- Savings plan: 1-3 yr term up to 72%
- Reserved: Steady state work loads 75% discount 3 payment options 1-3 yr
- Spot Instance: spare up to 90% of pricing can resume later
- Dedicated Hosts: Certain  compliance ; non shared
How does EC2 pricing work? Per hr, term load
What is an Amazon Machine Image (AMI)? image needed to launch and instance
How does EC2 integrate with other AWS services? This is the starting point for most integration with other services
What are the different computing models available in AWS? AWS Elastic Load Balancing, Amazon SQS, Amazon SNS
What is an instance and its use cases? Ability to use instance for various applicational use within the AWS system
What are containers and their advantages?COntainer is a Docker container- delivers software in a container- packages and run onto of instances. Host is an instance
Container orchestration- ECS helps to run this
What is serverless computing and its use cases?
When would you consider a hybrid deployment model?Depends on business needs
What are some of the popular AWS computing services?AW Container ACS, AWS Lambda-Upload code service waits for trigger, code run in managed environment
Lambda runs code in less than 15 min and handles the load
What is AWS Lambda?Upload coade service wairts for trigger,code run in managed environment
Lambda runs code in less than 15 min and handles the load
What is Amazon ECS? Elastic Container Service
How does AWS Fargate differ from Amazon EC2?Use for EKS or ECS
short running fuctnions, AWS Lambda
Managed service
No provisioning or managing of servers is needed.
What are the benefits of using AWS Elastic Beanstalk?Provision Amazon EC2 instances- App code to Beanstalk to build out

How does EC2 demonstrate elasticity? Provision Amazon EC2 instances- App code to Beanstalk to build out
What level of control do users have over EC2 instances? Limited based on admin level and contracts
How does EC2 integrate with other AWS services? Primary starting point to most service integrations
What security features does Amazon EC2 provide? Recovery, Load balancing
What are the main architectural components of Amazon EC2? Instances, AMI
What factors should you consider when choosing a region for your EC2 instance? The location of your customers, their base customer
What is the purpose of a VPC in Amazon EC2? Virtual private clous- your own private cloud
What are subnets and their role in EC2? A range of IP addresses for a VPC
How do security groups protect your EC2 instances? Controlling incoming and outgoing communications/ traffic-defining rules and boundaries
What are the steps to launch an EC2 instance? Select the best instance type for the work needed, configure the instance, connect the instance and terminate the instance
What is the importance of tagging in EC2? Allows for categorizing the AWS resources in various ways
Can you automate EC2 scaling? Yes 
What security features does EC2 offer? Shared responsibility model, data protection, infrastructure security, network isolation, security groups and Network ACL's, IAM roles, instance isolation
What are the benefits of using AMIs? Faster set up and configuration, highly flexible, reduced cost, replicability and consistency, quick deployment
