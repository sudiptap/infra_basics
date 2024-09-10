1. Compute Services
EC2 (Elastic Compute Cloud): Virtual servers for running applications.
ECS (Elastic Container Service): Container orchestration service for Docker containers.
EKS (Elastic Kubernetes Service): Kubernetes orchestration service.
AWS Lambda: Serverless compute service for running code without provisioning servers.
Elastic Beanstalk: Platform-as-a-Service for deploying and scaling applications.
AWS Fargate: Serverless compute engine for containers (works with ECS and EKS).
2. Storage and Databases
S3 (Simple Storage Service): Object storage for large-scale data storage.
EBS (Elastic Block Store): Block storage volumes for EC2 instances.
EFS (Elastic File System): Managed file storage service for use with EC2.
Glacier: Long-term cold storage.
RDS (Relational Database Service): Managed relational database service (supports MySQL, PostgreSQL, SQL Server, etc.).
DynamoDB: Fully managed NoSQL database service.
Aurora: High-performance relational database compatible with MySQL and PostgreSQL.
Redshift: Data warehousing service for large-scale analytics.
Amazon DocumentDB: Managed MongoDB-compatible database service.
3. Networking & Content Delivery
VPC (Virtual Private Cloud): Isolated network environments for deploying AWS resources.
Elastic Load Balancing (ELB): Distributes incoming traffic across multiple targets.
Route 53: DNS web service for domain name resolution.
CloudFront: Content delivery network (CDN) for distributing content globally.
API Gateway: Managed service for building and deploying APIs.
Direct Connect: Dedicated network connection between your data center and AWS.
4. Security, Identity, and Access
IAM (Identity and Access Management): Manage user access and encryption keys.
Cognito: Authentication and user identity service for web and mobile apps.
Secrets Manager: Manage and retrieve database credentials, API keys, and other secrets.
KMS (Key Management Service): Manage encryption keys for securing data.
AWS Shield: DDoS protection for applications.
AWS WAF (Web Application Firewall): Protects applications from common web exploits.
CloudHSM: Hardware-based key storage for compliance with security regulations.
5. Monitoring, Logging, and Analytics
CloudWatch: Monitoring for AWS resources and applications.
AWS X-Ray: Distributed tracing for analyzing and debugging applications.
CloudTrail: Log and monitor account activity across AWS infrastructure.
AWS Config: Assess, audit, and evaluate configurations of AWS resources.
Athena: Query service for analyzing data in S3 using standard SQL.
Elasticsearch Service (OpenSearch): Search, analyze, and visualize log data.
Kinesis: Real-time data streaming and analytics service.
AWS Glue: Fully managed ETL (extract, transform, load) service for data analytics.
6. Application Integration
SNS (Simple Notification Service): Publish/subscribe messaging service.
SQS (Simple Queue Service): Managed message queuing service.
Step Functions: Serverless orchestration for event-driven applications.
EventBridge: Event bus to connect applications using data from your own apps or AWS services.
7. DevOps and Management Tools
CloudFormation: Infrastructure as Code (IaC) service for defining AWS resources.
Elastic Container Registry (ECR): Docker container registry for storing container images.
CodePipeline: Continuous delivery service for automating release pipelines.
CodeBuild: Managed build service for compiling source code and running tests.
CodeDeploy: Automated deployment service for applications to various compute services.
Systems Manager: Manage and automate operations across AWS resources.
8. Migration & Transfer
AWS Data Migration Service (DMS): Migrate databases to and from AWS.
Snowball/Snowmobile: Physically transfer large amounts of data to AWS.
AWS Migration Hub: Track the progress of application migrations.
9. Machine Learning & AI
SageMaker: Fully managed service for building, training, and deploying machine learning models.
Rekognition: Image and video analysis service.
Lex: Build conversational interfaces using voice and text.
Polly: Text-to-speech service.
Transcribe: Automatic speech recognition (ASR) service.
Translate: Language translation service.
10. Edge Computing
AWS IoT Core: Service for connecting IoT devices to AWS.
AWS Greengrass: Local compute, messaging, data caching, and sync for connected devices.
Outposts: Bring AWS services to your on-premises infrastructure.
Wavelength: Low-latency applications running at the edge of mobile networks.
11. Cost Management & Optimization
Cost Explorer: Analyze and track AWS spending.
AWS Budgets: Set custom cost and usage budgets.
Trusted Advisor: Real-time guidance to help optimize resources and improve security.
Key Concepts to Master:
High Availability (HA) and Fault Tolerance: Using services like ELB, RDS Multi-AZ, and Auto Scaling to build resilient systems.
Scaling: Elasticity using services like Auto Scaling, ECS, Lambda, and DynamoDB Auto Scaling.
Security: Designing with least privilege principles, securing data using KMS and IAM, and building with security best practices.
Monitoring and Observability: Leveraging CloudWatch, X-Ray, and AWS Config to maintain visibility into system health and performance.
Cost Optimization: Understanding how to use Reserved Instances, Spot Instances, and using services like Trusted Advisor to keep costs in check.
Microservices Architecture: Using services like ECS, API Gateway, Lambda, and Step Functions to build loosely coupled, independently deployable components.
Mastering these services and understanding how they fit together in system design will enable you to design, build, and manage complex, scalable systems on AWS.