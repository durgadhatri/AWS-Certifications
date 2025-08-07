# Lab 01: Introduction to the AWS Console and Global Infrastructure (READ ONLY)

## Task 1: Basics of Cloud Computing

Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, organizations can access technology services such as computing power, storage, and databases on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

The core characteristics of cloud computing include on-demand self-service, broad network access, resource pooling, rapid elasticity, and measured service. This means users can provision resources whenever needed, access them over the internet, scale up or down automatically, and only pay for what they use.

In traditional infrastructure, companies invest heavily upfront in physical hardware and data centers. This requires long provisioning times, dedicated IT staff, and often leads to overprovisioning or underutilization. In contrast, cloud infrastructure allows businesses to scale resources instantly, reduce operational overhead, and respond quickly to changing demands.

**Cloud environments are generally classified into four types:**

There’s no one type of cloud computing that’s right for everyone. Several different cloud computing models, types, and services have evolved to meet the rapidly changing technology needs of organizations. There are three main ways to deploy cloud services: using a **public cloud**, **private cloud**, or **hybrid cloud**.

- **Public Cloud:** Public clouds are the most common type of cloud computing deployment. The cloud resources (like servers and storage) are owned and operated by a third-party cloud service provider and delivered over the internet. With a public cloud, all hardware, software, and other supporting infrastructure are owned and managed by the cloud provider.(e.g., AWS).

- **Private Cloud:** A private cloud consists of cloud computing resources used exclusively by one business or organization. The private cloud can be physically located at your organization’s on-site datacenter, or it can be hosted by a third-party service provider. But in a private cloud, the services and infrastructure are always maintained on a private network and the hardware and software are dedicated solely to your organization.

- **Hybrid Cloud:** A hybrid cloud is a type of cloud computing that combines on-premises infrastructure—or a private cloud—with a public cloud. Hybrid clouds allow data and apps to move between the two environments.

**There are three primary cloud service models:**

Cloud computing is typically delivered through three main service models: IaaS (Infrastructure as a Service), PaaS (Platform as a Service), and SaaS (Software as a Service). These are also known as cloud service offerings or cloud computing categories, and they define how organizations use the cloud and the level of responsibility they have in managing cloud resources.

- **Infrastructure as a Service (IaaS)**: Infrastructure as a service, or IaaS, delivers on-demand infrastructure resources to organizations via the cloud, such as compute, storage, networking, and virtualization. Customers don’t have to manage, maintain, or update their own data center infrastructure, but are responsible for the operating system, middleware, virtual machines, and any apps or data. 

- **Platform as a Service (PaaS)**: Platform as a service, or PaaS, delivers and manages all the hardware and software resources to develop applications through the cloud. Developers and IT operations teams can use PaaS to develop, run, and manage applications without having to build and maintain the infrastructure or platform on their own. Customers still have to write the code and manage their data and applications, but the environment to build and deploy apps is managed and maintained by the cloud service provider. 

- **Software as a Service (SaaS)**: Software as a service, or SaaS, provides the entire application stack, delivering an entire cloud-based application that customers can access and use. SaaS products are completely managed by the service provider and come ready to use, including all updates, bug fixes, and overall maintenance. Most SaaS applications are accessed directly through a web browser, which means customers don’t have to download or install anything on their devices. 

**Cloud computing offers several important benefits, which are:** 

- **Cost Efficiency:** Eliminates the need for large upfront investments in hardware and reduces ongoing maintenance costs. You only pay for the resources you use.

- **Speed and Agility:** Resources can be provisioned within minutes, enabling faster development, testing, and deployment of applications.

- **Global Scale:** Services can be deployed across multiple geographic regions, allowing you to reach users worldwide with low latency.

- **Reliability:** Built-in redundancy, backup options, and disaster recovery improve system uptime and ensure business continuity.

- **Security:** Cloud providers offer strong security features including encryption, identity and access management, compliance certifications, and threat detection.

- **Elasticity:** Automatically scales resources up or down based on real-time demand, helping optimize performance and cost.

## Task 2: Introduction to AWS and Its Value Proposition

Amazon Web Services (AWS) began offering IT infrastructure services as web services in 2006, which is now known as cloud computing. Today, AWS provides a highly reliable, scalable, and low-cost cloud platform that powers hundreds of thousands of businesses in over 190 countries, delivering more than 200 fully featured services across computing, storage, databases, analytics, machine learning, networking, and more.

1. **AWS Cloud Value Proposition**

   The value proposition of AWS can be summed up in five core benefits that most organizations experience. These benefits demonstrate how AWS enables companies to scale efficiently, innovate faster, and operate more reliably and responsibly.

   The five dimensions of the Cloud Value Framework are:

   - Cost savings, by scaling systems to meet performance requirements while eliminating unnecessary infrastructure and resource waste.

   - Increased staff productivity, by reducing time spent on infrastructure management and enabling teams to focus on high-impact, strategic work.

   - Operational resilience, through a highly available and fault-tolerant infrastructure that protects against hardware failures, natural disasters, and outages.

   - Business agility, by allowing developers to provision resources instantly and accelerate the delivery of new applications and services.

   - Sustainability, by minimizing the environmental impact of business operations through energy-efficient infrastructure and AWS-led green initiatives.

   To help quantify this value, AWS Cloud Economics developed the Cloud Value Framework, a model designed to help organizations build a comprehensive business case for cloud adoption. It enables measurement and tracking of progress across these five dimensions, using insights drawn from over 1,500 public AWS case studies and the analysis of 15 key operational and financial KPIs.

2. **Benefits of AWS Global Infrastructure**

   The AWS Cloud infrastructure is built around **AWS Regions** and **Availability Zones**, offering unmatched advantages through its global network, which is designed for real-world performance, reliability, and geographic scale.

   An **AWS Region** is a physical location in the world where AWS has multiple **Availability Zones**. Availability Zones consist of one or more discrete data centers, each with redundant power, networking, and connectivity, housed in separate facilities. These zones allow customers to operate production applications and databases that are more highly available, fault tolerant, and scalable than would be possible from a single data center.

   Key benefits of the AWS global infrastructure include:

   - **Most Extensive Global Footprint**: AWS operates **37 geographic regions** and **117 Availability Zones**, with over **700 CloudFront edge locations**, along with numerous **Local Zones** and **Wavelength Zones** for ultra-low latency delivery.
  
   - **Security**: AWS infrastructure is built to meet the highest industry standards, with continuous monitoring and encryption of data in transit across its global network.
  
   - **Availability**: Each AWS Region includes multiple, physically separated Availability Zones to ensure that disruptions are isolated and workloads remain highly available.
  
   - **Performance**: AWS delivers low-latency, reliable networking through a redundant **400 GbE fiber backbone**. Services like Local Zones and Wavelength bring compute infrastructure closer to users for ultra-low latency applications.
  
   - **Scalability & Flexibility**: AWS enables customers to quickly scale up or down, provisioning thousands of servers in minutes. It also offers hybrid cloud options like **AWS Outposts**, local responsiveness via **Local Zones**, and consistent APIs across regions.

   - **Global Reach**: With infrastructure deployed across every inhabited continent, AWS allows customers to serve end users globally with low latency while meeting **data residency** and **compliance** requirements.

3. Navigating the AWS Console - Categories of AWS Services

AWS services are grouped into categories to help you navigate the platform efficiently. Each category includes specific services that address common IT needs:

- **Compute**  
  Services that offer scalable computing capacity.  
  - *EC2*: Virtual servers in the cloud  
  - *Lambda*: Serverless compute  
  - *Elastic Beanstalk*: Platform for deploying applications

- **Storage**  
  Scalable and secure data storage solutions.  
  - *S3*: Object storage  
  - *EBS*: Block storage for EC2  
  - *Glacier*: Archival storage

- **Database**  
  Managed database services for structured and unstructured data.  
  - *RDS*: Relational databases  
  - *DynamoDB*: NoSQL database  
  - *Aurora*: High-performance managed database

- **Networking & Content Delivery**  
  Services for secure, high-speed connectivity.  
  - *VPC*: Private network within AWS  
  - *CloudFront*: Content delivery network  
  - *Route 53*: DNS and domain registration

- **Security & Identity**  
  Tools to manage user access and data protection.  
  - *IAM*: User access control  
  - *KMS*: Key management  
  - *Shield*: DDoS protection

- **Developer Tools**  
  Services for continuous integration and deployment.  
  - *CodeCommit*: Source control  
  - *CodeBuild*: Build automation  
  - *CodeDeploy*: Deployment automation

4. Key Features for Managing Resources

AWS Console provides tools and features that simplify the management and customization of your cloud environment:

- **Console Dashboard**  
  Displays an overview of AWS services, shortcuts, and current usage.

- **Service Search and Filtering**  
  Quickly locate services using filters or the global search function.

- **Resource Groups**  
  Create custom views for logically grouping related AWS resources. This is useful for projects or environments spanning multiple regions and services.

- **Tag Editor**  
  Apply, edit, and manage tags across services for cost tracking, automation, and organization.

- **Console Customization**  
  Pin your frequently used services, personalize your homepage layout, and configure default views to enhance productivity.

5. AWS Global Infrastructure – Regions and Availability Zones

AWS offers a global cloud infrastructure that is designed to be secure, highly available, fault-tolerant, and scalable. Understanding how AWS organizes its infrastructure helps in making informed decisions when deploying resources.

5.1 AWS Regions

- **AWS Regions** are separate geographic areas that contain multiple isolated Availability Zones.
- Each Region is physically independent and provides full resource redundancy.
- **Examples:**  
  - `us-east-1` (N. Virginia)  
  - `eu-west-1` (Ireland)  
  - `ap-south-1` (Mumbai)

- How to Choose an AWS Region

  Use the region selector dropdown in the top-right corner of the AWS Management Console to choose your desired Region, based on factors such as

- **Latency**: Choose a Region closer to your end users for better performance.
- **Compliance & Data Residency**: Some data must remain in a specific country/region due to legal or regulatory requirements.
- **Service Availability**: Not all AWS services are available in every Region. Always check the [AWS Regional Services List](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/).
- **Cost**: AWS pricing can vary across Regions. For cost-sensitive workloads, compare pricing using the [AWS Pricing Calculator](https://calculator.aws.amazon.com/).


5.2 Availability Zones (AZs)

- Availability Zones are **physically separate data centers** within a Region.
- Each AZ has independent power, cooling, and networking to avoid correlated failures.
- Using **multiple AZs** enhances fault tolerance and availability.
- Best Practice is to Deploy production workloads across **at least two AZs**.

5.3 Multi-AZ and Multi-Region Deployments

Multi-AZ Deployments

- Used within a single Region to achieve **high availability** and **automatic failover**.
- Examples:
  - **Amazon RDS** with Multi-AZ enabled for database redundancy
  - **EC2** instances placed across AZs with load balancing and auto-scaling

Multi-Region Deployments

- Designed for **disaster recovery (DR)**, **data replication**, and **low latency access** across continents.
- Examples:
  - **S3 Cross-Region Replication** to back up critical data
  - **Route 53 latency-based routing** to direct users to the nearest Region
  - **Active-Active or Active-Passive architectures** for business continuity

5.4 Edge Locations and Regional Edge Caches

- **Edge Locations** are endpoints for AWS content delivery services like **Amazon CloudFront**.
- **Regional Edge Caches** sit between origin servers and edge locations to further cache content and reduce load on the origin.

Benefits

- **Low Latency**: Serve static/dynamic content closer to users.
- **Improved Performance**: Reduce origin fetches and speed up content delivery.
- **DDoS Protection**: Fronting applications with CloudFront adds an additional layer of security.

Use Cases

- Content-heavy websites
- Video streaming platforms
- APIs and web applications requiring global reach

## Task 3: AWS Cloud Design Principles

The **AWS Well-Architected Framework** is a set of best practices designed to guide cloud architects in building secure, high-performing, resilient, efficient, and sustainable systems. Developed based on AWS’s experience with thousands of customers, it helps teams design and continually improve workloads in the cloud by focusing on six key areas called **pillars**.

These pillars—**Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability**—help ensure that cloud architectures align with business goals and can adapt to changing demands.

The Six Pillars

- **Operational Excellence**  Focuses on how to run and monitor systems to deliver business value and to continually improve processes and procedures. Key practices include:
  - Automating operations where possible (infrastructure as code)
  - Monitoring and logging for performance insights
  - Performing regular game days (failure simulations)

- **Security**  Emphasizes protecting data, systems, and assets through risk assessments and mitigation strategies. Core areas include:
  - Identity and access management (IAM)
  - Data encryption at rest and in transit
  - Real-time threat detection and response

- **Reliability**  Ensures workloads perform their intended function correctly and consistently, even when failures occur. Focus areas:
  - Distributed system design
  - Automated recovery from failures
  - Scalability and change management

- **Performance Efficiency**  Focuses on using computing resources efficiently and adapting to changing requirements over time. Key practices:
  - Selecting the right instance types and configurations
  - Monitoring performance metrics
  - Using serverless architectures and autoscaling

- **Cost Optimization**  Involves avoiding unnecessary expenses and using resources efficiently. Key actions:
  - Matching supply with demand (right-sizing)
  - Using Reserved or Spot Instances where applicable
  - Monitoring spend with AWS Cost Explorer and Budgets

- **Sustainability**  Focuses on minimizing the environmental impact of running cloud workloads. Strategies include:
  - Selecting energy-efficient AWS Regions
  - Optimizing resource utilization to reduce carbon footprint
  - Leveraging shared services and serverless technologies

Applying the Pillars in Practice: When designing cloud workloads, trade-offs between pillars often arise. For example:
- Adding redundancy (Reliability) may increase cost.
- Enhanced encryption and logging (Security) could reduce performance.
- Performance improvements may affect sustainability goals if resource usage increases.

AWS provides two main tools to help implement and review these principles:

- **AWS Well-Architected Tool**  A free tool that lets teams review workloads against AWS best practices, identify risks, and receive prioritized improvement plans.

- **AWS Trusted Advisor**  Offers real-time recommendations across categories such as security, cost, performance, and fault tolerance, helping teams fine-tune infrastructure proactively.

## Task 4: AWS Shared Responsibility Model

Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates. The customer assumes responsibility and management of the guest operating system (including updates and security patches), other associated application software as well as the configuration of the AWS provided security group firewall. Customers should carefully consider the services they choose as their responsibilities vary depending on the services used, the integration of those services into their IT environment, and applicable laws and regulations. The nature of this shared responsibility also provides the flexibility and customer control that permits the deployment. As shown in the chart below, this differentiation of responsibility is commonly referred to as Security “of” the Cloud versus Security “in” the Cloud.

- AWS responsibility “Security of the Cloud”

AWS is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.

- Customer responsibility “Security in the Cloud”

Customer responsibility will be determined by the AWS Cloud services that a customer selects. This determines the amount of configuration work the customer must perform as part of their security responsibilities. For example, a service such as Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS) and, as such, requires the customer to perform all of the necessary security configuration and management tasks. Customers that deploy an Amazon EC2 instance are responsible for management of the guest operating system (including updates and security patches), any application software or utilities installed by the customer on the instances, and the configuration of the AWS-provided firewall (called a security group) on each instance. For abstracted services, such as Amazon S3 and Amazon DynamoDB, AWS operates the infrastructure layer, the operating system, and platforms, and customers access the endpoints to store and retrieve data. Customers are responsible for managing their data (including encryption options), classifying their assets, and using IAM tools to apply the appropriate permissions.

This customer/AWS shared responsibility model also extends to IT controls. Just as the responsibility to operate the IT environment is shared between AWS and its customers, so is the management, operation and verification of IT controls shared. AWS can help relieve customer burden of operating controls by managing those controls associated with the physical infrastructure deployed in the AWS environment that may previously have been managed by the customer. As every customer is deployed differently in AWS, customers can take advantage of shifting management of certain IT controls to AWS which results in a (new) distributed control environment. Customers can then use the AWS control and compliance documentation available to them to perform their control evaluation and verification procedures as required. Below are examples of controls that are managed by AWS, AWS Customers and/or both.

- Inherited Controls
  Controls which a customer fully inherits from AWS. Physical and Environmental controls

- Shared Controls

Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services. Examples include:

  Patch Management – AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.
Configuration Management – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.
Awareness & Training - AWS trains AWS employees, but a customer must train their own employees.

  Once a customer understands the AWS Shared Responsibility Model and how it generally applies to operating in the cloud, they must determine how it applies to their use case. Customer responsibility varies based on many factors, including the AWS services and Regions they choose, the integration of those services into their IT environment, and the laws and regulations applicable to their organization and workload.
