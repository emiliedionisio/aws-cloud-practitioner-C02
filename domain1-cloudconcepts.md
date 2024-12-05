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


### AWS Educate

What is Amazon EC2?
Amazon EC2 (Elastic Compute Cloud) is a web service that provides resizable compute capacity in the cloud.
What is Amazon EC2 and its primary benefits?
Amazon EC2 is a cloud computing service that offers scalable virtual servers, enabling users to launch and manage server instances with benefits like flexibility, scalability, and cost-efficiency.
What is a Security Group in EC2?
A Security Group in EC2 is a virtual firewall that controls the inbound and outbound traffic to and from EC2 instances.
What are the four main purchasing options for EC2 instances, and what are their key characteristics?
The four main purchasing options for EC2 instances are On-Demand (pay-as-you-go), Reserved (discounted rates for reserved capacity), Spot (bid for unused capacity at reduced rates), and Savings Plans (flexible pricing for long-term commitments).
How does EC2 pricing work?
EC2 pricing is based on factors like instance type, operating system, region, and usage duration, with options for On-Demand, Reserved, and Spot instances.


What is an Amazon Machine Image (AMI)?
An Amazon Machine Image (AMI) is a template that contains the software configuration (operating system, application server, and applications) required to launch an instance.
How does EC2 integrate with other AWS services?
EC2 integrates with other AWS services such as S3 for storage, RDS for databases, VPC for networking, IAM for access control, and CloudWatch for monitoring and management.
What are the different computing models available in AWS?
The different computing models in AWS include EC2 (virtual servers), ECS/EKS (container services), Lambda (serverless computing), and Lightsail (simple virtual private servers).
What is an instance and its use cases?
An instance in EC2 is a virtual server used for running applications, web hosting, machine learning, data analysis, and other computing tasks.
What are containers and their advantages?
Containers are lightweight, portable units of software that include all dependencies and configurations, offering advantages like scalability, consistency, and efficiency.
What is serverless computing and its use cases?
Serverless computing allows you to run code without managing servers, ideal for microservices, real-time file processing, and event-driven applications.
When would you consider a hybrid deployment model?
A hybrid deployment model is considered when there is a need to integrate on-premises infrastructure with cloud resources for flexibility, cost savings, or data sovereignty requirements.
What are some of the popular AWS computing services?
Popular AWS computing services include EC2, Lambda, ECS, EKS, Lightsail, and Fargate.
What is AWS Lambda?
AWS Lambda is a serverless computing service that runs code in response to events and automatically manages the underlying compute resources.
What is Amazon ECS?
Amazon ECS (Elastic Container Service) is a fully managed container orchestration service that makes it easy to deploy, manage, and scale containerized applications.
How does AWS Fargate differ from Amazon EC2?
AWS Fargate is a serverless compute engine for containers that removes the need to manage EC2 instances, whereas Amazon EC2 requires you to manage the instances hosting your containers
What are the benefits of using AWS Elastic Beanstalk?
AWS Elastic Beanstalk simplifies application deployment and management by handling infrastructure provisioning, load balancing, scaling, and monitoring.
How does EC2 demonstrate elasticity?
EC2 demonstrates elasticity by allowing users to easily scale compute capacity up or down based on demand through features like Auto Scaling.
What level of control do users have over EC2 instances?
Users have complete control over EC2 instances, including root access, the ability to stop and start instances, and the ability to configure instance settings and software.
How does EC2 integrate with other AWS services?
EC2 integrates seamlessly with various AWS services like S3 for storage, RDS for databases, IAM for security, VPC for networking, and CloudWatch for monitoring.
What security features does Amazon EC2 provide?
Amazon EC2 provides security features like security groups, network ACLs, encryption, IAM roles, and monitoring and logging through CloudWatch and CloudTrail.
What are the main architectural components of Amazon EC2?
The main architectural components of Amazon EC2 include instances, AMIs, volumes, security groups, key pairs, and VPCs.
What factors should you consider when choosing a region for your EC2 instance?
Factors to consider when choosing a region include latency, data sovereignty, service availability, and pricing.
What is the purpose of a VPC in Amazon EC2?
A VPC (Virtual Private Cloud) provides an isolated virtual network where users can launch and manage AWS resources, including EC2 instances.
What are subnets and their role in EC2?
Subnets are subdivisions of a VPC that allow users to group resources based on security and operational needs within a single availability zone.
How do security groups protect your EC2 instances?
Security groups act as virtual firewalls, allowing users to control the inbound and outbound traffic to and from their EC2 instances.
What are the steps to launch an EC2 instance?
Steps to launch an EC2 instance include selecting an AMI, choosing an instance type, configuring instance details, adding storage, configuring security groups, and launching the instance.
What is the importance of tagging in EC2?
Tagging helps organize and manage EC2 resources by assigning metadata to instances, which can be used for cost allocation, automation, and resource management.
Can you automate EC2 scaling?
Yes, you can automate EC2 scaling using Auto Scaling, which adjusts the number of running instances based on defined policies and metrics.
What security features does EC2 offer?
EC2 offers security features like encryption, security groups, network ACLs, IAM roles, and monitoring through CloudWatch and CloudTrail.
What are the benefits of using AMIs?
Benefits of using AMIs include easy replication of instances, simplified deployment, faster scaling, and consistent configurations across multiple instances.
