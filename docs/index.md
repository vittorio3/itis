<p align="center">
    <img src="media/cloud.png" alt="cloud" width="75%"/>
</p>

<br>

---

## **What is Cloud Computing?**

<br>

---

- **Definition**: Cloud computing is the delivery of computing services—such as servers, storage, databases, networking, software, and more—over the internet (“the cloud”).
- **Key Characteristics**:
  - **On-demand access**: Resources are available whenever needed.
  - **Scalability**: Services can scale up or down based on demand.
  - **Remote Access**: Resources are accessible from anywhere with an internet connection.

<br>

---

## **Cloud Service Models**

<br>

---

- **Models Covered**: 
  - **IaaS** (Infrastructure as a Service)
  - **PaaS** (Platform as a Service)
  - **SaaS** (Software as a Service)

<br>

---

## **IaaS - Infrastructure as a Service**

<br>

---

- **Definition**: IaaS provides virtualized computing resources over the internet.
- **Features**:
  - Access to servers, storage, and networks.
  - High control over the infrastructure.

<br>

---

## **PaaS - Platform as a Service**

<br>

---

- **Definition**: PaaS provides a framework for developers to build, test, and deploy applications.
- **Features**:
  - Simplifies app development with built-in infrastructure management.
  - Offers tools for collaborative development and testing.

<br>

---

## **SaaS - Software as a Service**

<br>

---

- **Definition**: SaaS delivers software applications over the internet on a subscription basis.
- **Features**:
  - Accessible from any device with internet.
  - Reduces need for software installation and maintenance.

<br>

---

<img src="media/aas.jpg" alt="aas" width="100%"/>

<br>

---

## **Cloud Deployment Models**

<br>

---

- **Objective**: Understand the deployment options in cloud computing.
- **Models Covered**: 
  - **Public Cloud**
  - **Private Cloud**
  - **Hybrid Cloud**

<br>

---

## **Private Cloud**

<br>

---

- **Definition**: Exclusive infrastructure dedicated to a single organization.
- **Features**:
  - Greater control over security and compliance.
  - Often hosted on-premises or with a private provider.
- **Examples**: IBM Cloud Private, VMware Private Cloud.

<br>

---

## **Public Cloud**

<br>

---

- **Definition**: Services are delivered over the internet and shared among multiple customers.
- **Features**:
  - Cost-effective with scalable resources.
  - Managed by third-party providers.
- **Examples**: Amazon Web Services (AWS), Google Cloud, Microsoft Azure.

<br>

---

## **Hybrid Cloud**

<br>

---

- **Definition**: A combination of public and private cloud resources.
- **Features**:
  - Flexibility to run workloads across different environments.
  - Balances cost efficiency and control.
- **Examples**: AWS Outposts, Azure Arc.

<br>

---

## **Content Delivery Network (CDN)**

<br>

---

- **Definition**: A network of servers that deliver content based on user location.
- **Benefits**:
  - Reduces latency by caching data closer to the user.
  - Enhances content delivery speed and reliability.
- **Examples**: AWS CloudFront, Azure CDN, Cloudflare.
- **Use Case**: Ideal for websites with global user bases or media-heavy applications.

<br>

---

<img src="media/cdn.png" alt="cdn" width="100%"/>

<br>

---

## **Data Centers and Virtualization**

<br>

---

- **Data Centers**:
  - Physical facilities that host cloud infrastructure.
  - Use redundancy and failover mechanisms for reliability.
- **Virtualization**:
  - Abstracts physical resources into virtual machines (VMs).
  - Enables efficient resource allocation and scalability.

<br>

---

<img src="media/virt.png" alt="virt" width="100%"/>

<br>

---

## **Virtual Machines (VMs)**

<br>

---

- **Definition**: Software emulations of physical computers, running on a host machine.
- **Features**:
  - Isolated operating system instances.
  - Full control over configuration and resource allocation.
- **Use Case**: Ideal for running traditional applications and full-stack environments.

<br>

---

## **Containers**

<br>

---

- **Definition**: Lightweight, standalone packages of code and dependencies.
- **Benefits**:
  - More efficient and portable than VMs.
  - Consistent environment across different platforms.
- **Tools**: Docker (for creating containers).
- **Use Case**: Cloud-native applications requiring high portability.

<br>

---

## **Container Orchestration with Kubernetes**

<br>

---

- **Definition**: Kubernetes automates the deployment, scaling, and management of containers.
- **Features**:
  - Manages containerized applications across multiple hosts.
  - Enables easy scaling, load balancing, and updates.
- **Use Case**: Microservices-based applications and scalable deployments.

<br>

---

## **Types of Cloud Storage**

<br>

---

- **Object Storage**: Stores data as objects (e.g., AWS S3).
  - **Best for**: Media files, backups, big data analytics.
- **File Storage**: Organizes data as files and folders (e.g., Amazon EFS).
  - **Best for**: Shared storage, legacy applications.
- **Block Storage**: Low-latency storage for VMs (e.g., Amazon EBS).
  - **Best for**: Databases, transactional applications.

<br>

---

## **Cloud Storage Cost Considerations**

<br>

---

- **Cost Factors**:
  - **Data Storage**: Cost based on the amount of data stored.
  - **Data Transfer**: Charges for data moved between regions.
  - **Access Frequency**: Different costs for hot (frequent access) vs. cold (rare access) storage.

<br>

---

## **SQL vs. NoSQL Databases**

<br>

---

- **SQL Databases**: Structured data, uses SQL (e.g., Amazon RDS, Azure SQL).
  - **Best for**: Relational data, complex queries, financial data.
- **NoSQL Databases**: Unstructured or semi-structured data (e.g., MongoDB, DynamoDB).
  - **Best for**: Real-time data, IoT, and dynamic schema requirements.

<br>

---

## **Managed Database Services**

<br>

---

- **Definition**: Fully managed databases handled by cloud providers.
- **Benefits**:
  - Automatic backups, scaling, and maintenance.
  - Security and compliance features.
- **Examples**: Amazon RDS, Google Firestore, Azure Cosmos DB.

<br>

---

## **Virtual Machines in the Cloud**

<br>

---

- **Cloud VMs**: AWS EC2, Azure VMs, GCP Compute Engine.
- **Configuration Options**: CPU, RAM, storage, network configurations.

<br>

---

## **Autoscaling and Load Balancing**

<br>

---

- **Autoscaling**: Automatically adjusts resources based on demand.
- **Load Balancing**: Distributes traffic across multiple instances.
- **Benefits**: Ensures reliability, optimizes cost.

<br>

---

## **Virtual Private Cloud (VPC)**

<br>

---

- **Definition**: Isolated virtual network in the cloud.
- **Components**: Subnets, IP ranges, gateways.

<br>

---

## **Security Essentials**

<br>

---

- **Firewalls**: Control inbound and outbound traffic.
- **Security Groups**: Define access permissions for instances.
- **Best Practices**: Regular audits, use of encryption.

<br>

---

## **Data Security**

<br>

---

- **Encryption**: At rest and in transit.
- **Identity Access Management (IAM)**: Control access based on roles and permissions.

<br>

---

## **Compliance Standards**

<br>

---

- **GDPR**: Data privacy regulations in the EU.
- **HIPAA**: Healthcare data regulations in the U.S.

<br>

---

## **CI/CD in the Cloud**

<br>

---

- **CI/CD Pipelines**: Automates testing and deployment.
- **Benefits**: Faster releases, fewer errors.
- **Examples**: AWS CodePipeline, GitHub Actions.

<br>

---

## **Infrastructure as Code (IaC)**

<br>

---

- **Definition**: Managing infrastructure using code.
- **Tools**: Terraform, AWS CloudFormation.
- **Benefits**: Consistency, ease of scaling, reproducibility.

