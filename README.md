📖 Project Overview
This repository contains a comprehensive collection of hands-on cloud computing practicals. It serves as a technical portfolio demonstrating practical knowledge of public cloud infrastructure (AWS, Azure, GCP) and private cloud deployment (OpenStack). The exercises cover core IaaS capabilities, networking, high availability, monitoring, and security best practices.

🎯 Objectives
To gain hands-on experience navigating and utilizing major public cloud provider consoles.

To design, provision, and configure fundamental cloud resources including compute instances, virtual networks, and storage.

To implement scalable architectures using auto-scaling and load balancing.

To establish private cloud environments and manage local virtualized resources.

To apply enterprise-grade security protocols, including IAM, least privilege, and encryption.

🛠️ Tools & Technologies
Public Cloud: Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP)

Private Cloud: OpenStack (Horizon, Nova, Neutron, Glance)

Compute & Storage: Amazon EC2, S3, Azure Blob, GCP Cloud Storage

Networking & Scaling: VPC, NAT Gateway, IGW, Application Load Balancer (ALB), Auto Scaling Groups (ASG)

Security & Monitoring: AWS IAM, Security Groups, CloudWatch, SNS

📂 Folder Structure
Plaintext
📦 Cloud-Computing-Practicals
 ┣ 📂 Practical-01_Cloud_Intro
 ┣ 📂 Practical-02_EC2_Deployment
 ┣ 📂 Practical-03_VPC_Architecture
 ┣ 📂 Practical-04_AutoScaling_ALB
 ┣ 📂 Practical-05_Static_Hosting
 ┣ 📂 Practical-06_CloudWatch_Monitoring
 ┣ 📂 Practical-07_OpenStack_Installation
 ┣ 📂 Practical-08_OpenStack_Instances
 ┣ 📂 Practical-09_OpenStack_Networking
 ┣ 📂 Practical-10_Cloud_Security
 ┗ 📜 README.md
📝 Detailed Practicals
1. Introduction to Cloud Platforms
Objective: Familiarize with AWS, Azure, and GCP interfaces, service catalogs, and cost estimation tools.

Steps: * Created free-tier accounts across AWS, Azure, and GCP.

Explored central dashboards and identified core Compute, Storage, and Networking services.

Navigated and utilized pricing calculators for architectural cost estimation.

2. Launch Your First Amazon EC2 Instance
Objective: Provision and securely connect to a virtual machine in the cloud.

Steps:

Launched an Amazon EC2 instance via the AWS Management Console.

Configured a pre-built Amazon Machine Image (Amazon Linux 2).

Designed a Security Group to securely allow inbound SSH traffic (Port 22).

Authenticated and connected to the instance via SSH terminal.

3. Set Up a Virtual Private Cloud (VPC)
Objective: Architect a secure, isolated network environment.

Steps:

Created a custom VPC containing public and private subnets.

Deployed EC2 instances into both subnets.

Configured an Internet Gateway (IGW) and route tables for public internet access.

Deployed a NAT Gateway to allow secure outbound internet traffic for the private subnet.

4. Configure Auto Scaling and Load Balancing
Objective: Build a highly available, fault-tolerant application tier.

Steps:

Defined a Launch Template and attached it to an Auto Scaling Group (ASG).

Configured dynamic scaling policies (e.g., scale-out when CPU > 70%).

Provisioned an Application Load Balancer (ALB) to distribute incoming web traffic across instances.

Simulated traffic spikes to validate automated scaling and load distribution.

5. Deploying a Static Website on the Cloud
Objective: Host web content utilizing serverless object storage.

Steps:

Created object storage buckets (AWS S3 / Azure Blob / GCP Storage).

Uploaded static web assets (HTML/CSS/JS).

Modified bucket policies and IAM permissions to enable public read access.

Accessed the live website via the generated endpoint URL.

6. Monitor Resources Using AWS CloudWatch
Objective: Implement proactive monitoring and alerting systems.

Steps:

Enabled CloudWatch metrics for deployed EC2 instances (CPU, Network, Disk).

Configured CloudWatch Alarms mapped to specific performance thresholds.

Integrated Simple Notification Service (SNS) to trigger email alerts.

Stressed the system to validate alert triggering and delivery.

7. Install OpenStack
Objective: Deploy a local private cloud environment.

Steps:

Configured local hardware/VM prerequisites.

Installed core OpenStack services using a deployment tool (e.g., DevStack or Packstack).

Verified service health and accessed the Horizon web dashboard.

8. Launch Your First OpenStack Instance
Objective: Provision virtual machines within a private cloud architecture.

Steps:

Configured project quotas and assigned user roles.

Uploaded a base OS image (e.g., CirrOS/Ubuntu) into the Glance image service.

Defined compute flavors (CPU/RAM/Disk templates).

Deployed a VM instance via Horizon and monitored the launch state.

9. OpenStack Networking Configuration
Objective: Establish network connectivity within OpenStack using Neutron.

Steps:

Created internal private networks and external public provider networks.

Deployed a virtual router and connected the respective subnet interfaces.

Allocated and associated a Floating IP to an instance for external SSH access.

10. Cloud Security Best Practices
Objective: Implement foundational enterprise security protocols.

Steps:

Created IAM Roles and Policies using the Principle of Least Privilege (PoLP).

Configured Server-Side Encryption (SSE) for cloud storage buckets.

Designed robust firewall rules (Security Groups/Network ACLs) mapping specific ports to trusted IPs.

🚀 Learning Outcomes
Infrastructure as a Service (IaaS): Mastered the deployment of scalable compute resources.

Network Engineering: Gained proficiency in SDN concepts, VPCs, subnetting, and routing.

High Availability: Learned to build resilient systems capable of handling variable loads automatically.

Private Cloud Management: Developed a deep understanding of OpenStack components and private infrastructure administration.

Cloud Security: Applied identity management and encryption standards to secure cloud workloads.

💡 Future Improvements
Automate infrastructure provisioning using Terraform or AWS CloudFormation.

Containerize applications using Docker and deploy via Kubernetes (EKS/AKS/GKE).

Implement a CI/CD pipeline using GitHub Actions or Jenkins.

👨‍💻 Author
Vishnu Yadav B.Sc. Computer Science

Ramanujan College, University of Delhi
