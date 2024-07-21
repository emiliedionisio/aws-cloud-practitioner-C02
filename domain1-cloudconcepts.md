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

What is Cloud Computing?
  Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing.
What are the three deployment models for cloud computing, their definitions, and uses?
- Public Cloud: Services offered over the public internet and available to anyone who wants to purchase them, used for general-purpose workloads.
- Private Cloud: Computing resources used exclusively by one business or organization, offering enhanced security and control, typically used for sensitive data or critical applications.
- Hybrid Cloud: A combination of public and private clouds, allowing data and applications to be shared between them, used for flexibility and optimized resource use.

What are the Benefits of cloud computing and their definitions?
- Cost Savings: Reduce capital expenditures and operating expenses by paying only for what you use.
- Scalability: Easily scale resources up or down based on demand.
- Performance: Access to powerful infrastructure with low latency and high-speed connectivity.
- Security: Advanced security features to protect data, applications, and infrastructure.
- Flexibility: Choose from various services and technologies to meet specific business needs.

What are the Amazon EC2 instance types and their definitions?
General Purpose: Balanced compute, memory, and networking resources for a variety of workloads.
Compute Optimized: Ideal for compute-bound applications requiring high-performance processors.
Memory Optimized: Designed for memory-intensive applications and workloads.
Storage Optimized: Suitable for workloads requiring high, sequential read and write access to large datasets on local storage.
Accelerated Computing: Use hardware accelerators, or co-processors, to perform functions such as floating-point number calculations, graphics processing, or data pattern matching.

What is a Load Balancer?
load balancer distributes incoming network traffic across multiple targets, such as EC2 instances

What is the primary purpose of AWS Regions in the global infrastructure?
AWS Regions enable global distribution of infrastructure, allowing customers to deploy applications and services closer to their users to reduce latency and comply with data sovereignty requirements

Describe the function of Amazon CloudFront in AWS's architecture.
Amazon CloudFront is a content delivery network (CDN) service that delivers data, videos, applications, and APIs to users globally with low latency and high transfer speeds.

How do AWS Edge locations enhance the performance of Amazon CloudFront?
AWS Edge locations are globally distributed data centers that cache content closer to end users, reducing latency and improving performance.

Explain how Amazon Route 53 integrates with AWS Edge locations to enhance user experiences.
Amazon Route 53 integrates with AWS Edge locations to route end-user requests to the nearest location, improving DNS query performance and reducing latency.

What are the advantages of using AWS Outposts for local data processing needs?
AWS Outposts extend AWS infrastructure to on-premises locations, allowing for consistent hybrid operations, low-latency access to on-premises systems, and local data processing to meet specific regulatory or performance requirements.

How are AWS Lambda and AWS Outposts different in what they offer for cloud computing?
AWS Lambda is a serverless compute service that runs code in response to events without provisioning or managing servers, while AWS Outposts provide AWS services and infrastructure on-premises for low-latency applications and hybrid cloud deployments.

What is high availability?
High availability refers to systems or components that are continuously operational and accessible for a high percentage of time, often achieved through redundancy and failover mechanisms.

What are the benefits of AWS having a global infrastructure with multiple regions?
AWS's global infrastructure with multiple regions ensures high availability, disaster recovery, low latency, data sovereignty compliance, and fault tolerance for applications and services.

What is an AWS Region?
An AWS Region is a geographic area consisting of multiple, isolated locations known as Availability Zones, used to deploy and manage AWS resources.

Why is data sovereignty important in AWS Regions?
Data sovereignty ensures that data is subject to the privacy laws and regulations of the country or region where it is stored, which is crucial for compliance and legal requirements.

How do AWS Regions enhance disaster recovery capabilities?
AWS Regions enhance disaster recovery by allowing data and applications to be replicated across geographically separated locations, ensuring business continuity in case of regional failures.

What are the four main factors to consider when choosing an AWS Region?
Compliance: Regulatory requirements for data storage and processing.
Latency: Proximity to end-users for improved performance.
Service Availability: Availability of specific AWS services and features.
Pricing: Cost differences between regions.

What is an AWS Availability Zone?
An AWS Availability Zone is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region, providing high availability and fault tolerance.

What is the purpose of having multiple Availability Zones within an AWS Region?
Multiple Availability Zones provide redundancy, fault tolerance, and low-latency networking, ensuring high availability and resilience of applications.

How does AWS ensure low latency communication between Availability Zones?
AWS ensures low latency communication between Availability Zones through high-speed, low-latency networking connections.

Why is it important to run EC2 instances across multiple AZs?
Running EC2 instances across multiple Availability Zones enhances fault tolerance and high availability by protecting applications from data center failures.

How do regional AWS services enhance high availability?
Regional AWS services distribute resources and workloads across multiple Availability Zones and regions, ensuring high availability and disaster recovery capabilities.

What is the purpose of Amazon CloudFront?
The purpose of Amazon CloudFront is to deliver content, such as data, videos, applications, and APIs, to users globally with low latency and high transfer speeds.

What are edge locations in AWS?
Edge locations are sites that Amazon CloudFront uses to cache copies of content for faster delivery to users around the world.

What is AWS Outposts?
AWS Outposts is a fully managed service that extends AWS infrastructure, services, APIs, and tools to virtually any on-premises facility for a consistent hybrid experience.

How do Availability Zones within AWS Regions contribute to disaster recovery and high availability?
Availability Zones within AWS Regions contribute to disaster recovery and high availability by providing isolated locations for redundant deployment of applications and data, ensuring continued operation even if one zone fails.

How do AWS Edge locations and Amazon CloudFront improve content delivery?
AWS Edge locations and Amazon CloudFront improve content delivery by caching content closer to end-users, reducing latency, and increasing transfer speeds.

What is an API in the context of AWS?
In the context of AWS, an API (Application Programming Interface) allows interaction with AWS services programmatically through code, enabling automation and integration.

What is the primary method of interacting with AWS services?
The primary method of interacting with AWS services is through the AWS Management Console, AWS Command Line Interface (CLI), and AWS.

What are the main ways to interact with AWS services?
The main ways to interact with AWS services are the AWS Management Console, AWS Command Line Interface (CLI), and AWS SDKs (Software Development Kits).

Why is automation important in cloud deployment?
Automation is important in cloud deployment because it ensures consistency, reduces manual errors, increases efficiency, and enables rapid scaling and deployment of resources.

What is the primary advantage of using AWS Elastic Beanstalk over manual methods like the AWS Management Console?
The primary advantage of using AWS Elastic Beanstalk is that it automates the deployment, scaling, and management of applications, allowing developers to focus on writing code rather than managing infrastructure.

What is AWS Elastic Beanstalk used for?
AWS Elastic Beanstalk is used for deploying and managing applications in various languages and frameworks without needing to manage the underlying infrastructure.

How does AWS CloudFormation help in managing AWS resources?
AWS CloudFormation helps manage AWS resources by allowing users to define infrastructure as code, creating templates that automate the provisioning and updating of resources in a predictable and consistent manner.

What are the main components of AWS Global Infrastructure?
The main components of AWS Global Infrastructure are Regions, Availability Zones, and Edge Locations.

Which AWS services automatically run across multiple Availability Zones?
Services like Amazon S3, Amazon RDS, and Amazon DynamoDB automatically run across multiple Availability Zones to ensure high availability and fault tolerance.

What is the recommended best practice for deploying infrastructure in AWS?
The recommended best practice for deploying infrastructure in AWS is to use multiple Availability Zones and Regions for high availability, fault tolerance, and disaster recovery.
