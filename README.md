HEAD
# Real-World DevOps/Cloud Projects For Learning by ProDevOpsGuy Tech Community ♐

![DevOps-Projects](https://imgur.com/5czbYqE.png)

## DevOps Real World Projects for Aspiring DevOps Engineers [Beginner to Advanced]

[![Forks][forks-shield]][forks-url] [![Stargazers][stars-shield]][stars-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[forks-shield]: https://img.shields.io/github/forks/NotHarshhaa/DevOps-Projects?style=for-the-badge&logo=github&logoColor=white&color=orange
[forks-url]: https://github.com/NotHarshhaa/DevOps-Projects/network/members
[stars-shield]: https://img.shields.io/github/stars/NotHarshhaa/DevOps-Projects.svg?style=for-the-badge&logo=github&logoColor=white&color=brightgreen
[stars-url]: https://github.com/NotHarshhaa/DevOps-Projects/stargazers

_*Welcome to the ultimate resource for **learning DevOps through hands-on projects!** This repository is designed to cater to aspiring **DevOps engineers** of all skill levels, from beginners taking their first steps in the field to advanced users looking to deepen their knowledge and expertise.*_

## Repository Contents for DevOps Projects from Beginner to Advanced Levels

> [!IMPORTANT]
>
> _This repository contains a comprehensive collection of DevOps projects, each meticulously crafted to provide a hands-on learning experience. The projects are categorized into different skill levels to ensure that everyone, regardless of their current expertise, can find a suitable starting point and progressively enhance their skills._
>
> - **Beginner Projects:** Simple, foundational projects that introduce basic DevOps concepts and tools.
> - **Intermediate Projects:** More complex projects that require a good understanding of DevOps fundamentals.
> - **Advanced Projects:** Challenging projects designed to push your limits and deepen your understanding of sophisticated DevOps practices.

## Integration of DevOps Technology with Other Technologies

> [!NOTE]
> _In the modern tech landscape, DevOps doesn't exist in isolation. It intersects with a variety of other technologies, enhancing and being enhanced by them. This repository includes projects that integrate DevOps with several key technologies, allowing you to see how these integrations work in real-world scenarios._
>
> - **Machine Learning:** Implement DevOps practices to manage and deploy machine learning models efficiently.
> - **Version Control with Git & GitHub:** Learn how to manage code versions and collaborate with others using Git and GitHub.
> - **CI/CD Pipelines:** Set up continuous integration and continuous deployment pipelines to automate the testing and deployment of your applications.
> - **Cloud Platforms (AWS, Azure, GCP):** Deploy applications on cloud platforms and leverage their services for scalability and reliability.
> - **Containerization (Docker, Kubernetes):** Use container technologies to ensure that your applications run consistently across different environments.

## Project Scope

> [!IMPORTANT]
> The projects span a wide array of topics within the DevOps domain, each designed to provide practical experience and insights into real-world scenarios. Here’s a detailed look at the areas covered:
>
> - **Automated Deployment:** Learn how to automate the deployment process to ensure that your applications are deployed quickly and reliably.
> - **Continuous Integration & Continuous Deployment (CI/CD):** Understand how to set up and manage CI/CD pipelines to automate the testing and deployment of your code.
> - **Infrastructure as Code (IaC):** Use tools like Terraform and CloudFormation to manage your infrastructure through code, ensuring consistency and scalability.
> - **Monitoring & Logging:** Implement monitoring and logging solutions to keep track of your applications’ performance and troubleshoot issues.
> - **Security & Compliance:** Learn how to incorporate security practices into your DevOps workflows to ensure that your applications are secure and compliant with regulations.
> - **Scalability & Performance Optimization:** Understand how to scale your applications and optimize their performance to handle increasing loads.

## Why Explore This Repository?

> [!NOTE]
> This repository is a treasure trove of learning opportunities, tailored to help you grow in the DevOps field. Here's why you should dive in:
>
> - **Hands-on Experience:** Each project is designed to provide you with practical, hands-on experience. You'll work through real-world challenges and gain the skills you need to succeed in the industry.
> - **Skill Enhancement:** Whether you're just starting or looking to build on existing skills, the projects are structured to guide you through a learning path that will enhance your capabilities.
> - **Industry Relevance:** Stay up-to-date with the latest trends and technologies in DevOps. The projects reflect current industry practices, ensuring that what you learn is relevant and applicable.
> - **Community Engagement:** Join a community of like-minded learners and professionals. Share your projects, seek feedback, and collaborate on exciting DevOps initiatives.

## Code of Conduct

> [!CAUTION]
>
> We are committed to fostering a welcoming and respectful environment for all contributors. Please take a moment to review our [Code of Conduct](./CODE_OF_CONDUCT.md) before participating in this community.

## Contribute and Collaborate

> [!TIP]
> This repository thrives on community contributions and collaboration. Here’s how you can get involved:
>
> - **Fork the Repository:** Create your own copy of the repository to work on.
> - **Submit Pull Requests:** Contribute your projects or improvements to existing projects by submitting pull requests.
> - **Engage with Others:** Participate in discussions, provide feedback on others’ projects, and collaborate to create better solutions.
> - **Share Your Knowledge:** If you’ve developed a new project or learned something valuable, share it with the community. Your contributions can help others in their learning journey.

## Join the Community

> [!IMPORTANT]
> We encourage you to be an active part of our community:
>
> - **Join Our Telegram Community:** Connect with fellow DevOps enthusiasts, ask questions, and share your progress in our [Telegram group](https://t.me/prodevopsguy).
> - **Follow Me on GitHub:** Stay updated with new projects and content by [following me on GitHub](https://github.com/NotHarshhaa).

## Hit the Star! ⭐

**If you find this repository helpful and plan to use it for learning, please give it a star. Your support is appreciated!**

### Author

![Author Image](https://imgur.com/f4rBnpK.gif)
# Deploy Java Application on AWS 3-Tier Architecture

![AWS](https://imgur.com/b9iHwVc.png)

## Table of Contents

1. [Goal](#goal)
2. [Pre-Requisites](#pre-requisites)
3. [Pre-Deployment](#pre-deployment)
4. [VPC Deployment](#vpc-deployment)
5. [Maven (Build)](#maven-build)
6. [3-Tier Architecture](#3-tier-architecture)
7. [Application Deployment](#application-deployment)
8. [Post-Deployment](#post-deployment)
9. [Validation](#validation)

---

![3-tier application](https://imgur.com/3XF0tlJ.png)

---

# Project Overview

## Goal

The primary objective of this project is to deploy a scalable, highly available, and secure Java application using a 3-tier architecture. The application will be hosted on AWS, utilizing various services like EC2, RDS, and VPC to ensure its availability, scalability, and security. The application will be accessible to end-users via the public internet.

## Pre-Requisites

Before starting the deployment, ensure you have the following:

1. **AWS Free Tier Account**:
   - Sign up for an [Amazon Web Services (AWS) Free Tier account](https://aws.amazon.com/free/).
   - Set up the AWS CLI on your local machine.
   - Configure your CLI with `aws configure`.

2. **GitHub Account and Repository**:
   - Create a [GitHub account](https://github.com/join) if you don't have one.
   - Fork the Java source code from the [Java-Login-App repository](https://github.com/NotHarshhaa/DevOps-Projects/blob/master/DevOps-Project-01/Java-Login-App) to your GitHub account.

3. **SonarCloud Account**:
   - Create an account on [SonarCloud](https://sonarcloud.io/) for static code analysis and code quality checks.
   - Generate a SonarCloud token for integration with your GitHub repository.

4. **JFrog Cloud Account**:
   - Sign up for a [JFrog Cloud account](https://jfrog.com/start-free/).
   - Set up a Maven repository in JFrog to store your build artifacts.

## Pre-Deployment

### Create Global AMI (Amazon Machine Image)

Creating a Global AMI involves installing necessary agents and software on an EC2 instance, which will be used to create custom AMIs for different components.

1. **Install AWS CLI**:
   - Install AWS CLI by following the instructions [here](https://aws.amazon.com/cli/).

   ```bash
   curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
   sudo installer -pkg AWSCLIV2.pkg -target /
   aws --version
   ```

2. **Install CloudWatch Agent**:
   - Install CloudWatch Agent to monitor your EC2 instances.

   ```bash
   sudo yum install amazon-cloudwatch-agent
   sudo /opt/aws/amazon-cloudwatch-agent/bin/amazon-cloudwatch-agent-ctl -a start
   ```

3. **Install AWS Systems Manager (SSM) Agent**:
   - The SSM Agent is necessary for managing EC2 instances via AWS Systems Manager.

   ```bash
   sudo yum install amazon-ssm-agent
   sudo systemctl start amazon-ssm-agent
   sudo systemctl enable amazon-ssm-agent
   ```

### Create Golden AMIs

Golden AMIs will be created for the different tiers (Nginx, Tomcat, Maven) of the architecture.

1. **For Nginx**:
   - Launch an EC2 instance and install Nginx:

   ```bash
   sudo amazon-linux-extras install nginx1.12
   sudo systemctl start nginx
   sudo systemctl enable nginx
   ```

   - Create a custom CloudWatch metric for memory usage:

   ```bash
   #!/bin/bash
   while true; do
     memory_usage=$(free | grep Mem | awk '{print $3/$2 * 100.0}')
     aws cloudwatch put-metric-data --metric-name MemoryUsage --namespace Custom --value $memory_usage --dimensions InstanceId=$(curl http://169.254.169.254/latest/meta-data/instance-id)
     sleep 60
   done &
   ```

2. **For Apache Tomcat**:
   - Launch another EC2 instance and install Apache Tomcat:

   ```bash
   sudo yum install java-11-openjdk-devel
   wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.53/bin/apache-tomcat-9.0.53.tar.gz
   sudo tar -xvzf apache-tomcat-9.0.53.tar.gz -C /opt/
   sudo ln -s /opt/apache-tomcat-9.0.53 /opt/tomcat
   sudo sh /opt/tomcat/bin/startup.sh
   ```

   - Configure Tomcat as a systemd service:

   ```bash
   sudo nano /etc/systemd/system/tomcat.service
   ```

   Add the following content:

   ```ini
   [Unit]
   Description=Apache Tomcat Web Application Container
   After=network.target

   [Service]
   Type=forking

   Environment=JAVA_HOME=/usr/lib/jvm/jre
   Environment=CATALINA_PID=/opt/tomcat/temp/tomcat.pid
   Environment=CATALINA_HOME=/opt/tomcat
   Environment=CATALINA_BASE=/opt/tomcat
   Environment='CATALINA_OPTS=-Xms512M -Xmx1024M -server -XX:+UseParallelGC'
   Environment='JAVA_OPTS=-Djava.awt.headless=true -Djava.security.egd=file:/dev/./urandom'

   ExecStart=/opt/tomcat/bin/startup.sh
   ExecStop=/opt/tomcat/bin/shutdown.sh

   User=tomcat
   Group=tomcat
   UMask=0007
   RestartSec=10
   Restart=always

   [Install]
   WantedBy=multi-user.target
   ```

   - Enable and start the Tomcat service:

   ```bash
   sudo systemctl daemon-reload
   sudo systemctl start tomcat
   sudo systemctl enable tomcat
   ```

3. **For Apache Maven Build Tool**:
   - Install Maven, Git, and JDK 11 on a separate EC2 instance:

   ```bash
   sudo yum install git
   sudo yum install java-11-openjdk-devel
   wget https://mirrors.ocf.berkeley.edu/apache/maven/maven-3/3.8.4/binaries/apache-maven-3.8.4-bin.tar.gz
   sudo tar -xvzf apache-maven-3.8.4-bin.tar.gz -C /opt/
   sudo ln -s /opt/apache-maven-3.8.4 /opt/maven
   ```

   - Update the system PATH:

   ```bash
   echo "export M2_HOME=/opt/maven" | sudo tee -a /etc/profile.d/maven.sh
   echo "export PATH=\$M2_HOME/bin:\$PATH" | sudo tee -a /etc/profile.d/maven.sh
   source /etc/profile.d/maven.sh
   ```

   - Verify the installation:

   ```bash
   mvn -version
   ```

## VPC Deployment

### Network Setup

1. **Create VPCs**:
   - Create two VPCs for the application architecture:

   ```bash
   aws ec2 create-vpc --cidr-block 192.168.0.0/16 --region us-east-1
   aws ec2 create-vpc --cidr-block 172.32.0.0/16 --region us-east-1
   ```

2. **NAT Gateway and Internet Gateway**:
   - Set up a NAT Gateway in the public subnet and an Internet Gateway for outbound access:

   ```bash
   aws ec2 create-nat-gateway --subnet-id subnet-xxxx --allocation-id eipalloc-xxxx
   aws ec2 create-internet-gateway
   aws ec2 attach-internet-gateway --vpc-id vpc-xxxx --internet-gateway-id igw-xxxx
   ```

3. **Transit Gateway**:
   - Create a Transit Gateway to allow communication between the VPCs:

   ```bash
   aws ec2 create-transit-gateway
   aws ec2 attach-transit-gateway-vpc-attachment --transit-gateway-id tgw-xxxx --vpc-id vpc-xxxx
   ```

4. **Route Tables**:
   - Update route tables for the private and public subnets to route traffic through the NAT Gateway and Internet Gateway:

   ```bash
   aws ec2 create-route-table --vpc-id vpc-xxxx
   aws ec2 create-route --route-table-id rtb-xxxx --destination-cidr-block 0.0.0.0/0 --gateway-id igw-xxxx
   ```

### Bastion Host Setup

1. **Deploy Bastion Host**:
   - Launch an EC2 instance in the public subnet as a Bastion Host:

   ```bash
   aws ec2 run-instances --image-id ami-xxxx --count 1 --instance-type t2.micro --key-name MyKeyPair --security-group-ids sg-xxxx --subnet-id subnet-xxxx --associate-public-ip-address
   ```

2. **Security Groups**:
   - Create

 a security group allowing SSH access from your IP:

   ```bash
   aws ec2 create-security-group --group-name BastionSG --description "Security group for Bastion Host" --vpc-id vpc-xxxx
   aws ec2 authorize-security-group-ingress --group-id sg-xxxx --protocol tcp --port 22 --cidr YOUR_IP/32
   ```

## Maven (Build)

### EC2 Instance for Maven Build

1. **Launch EC2 Instance Using Maven AMI**:
   - Launch an EC2 instance using the Maven Golden AMI:

   ```bash
   aws ec2 run-instances --image-id ami-maven --count 1 --instance-type t2.micro --key-name MyKeyPair --security-group-ids sg-maven --subnet-id subnet-maven
   ```

2. **Clone the Repository**:
   - Connect to the instance and clone your GitHub repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   ```

3. **Update `pom.xml`**:
   - Update `pom.xml` with SonarCloud and JFrog deployment details.

4. **Build the Application**:
   - Run the Maven build command to compile the project:

   ```bash
   mvn clean install -s settings.xml
   ```

5. **SonarCloud Integration**:
   - Integrate SonarCloud with Maven:

   ```bash
   mvn sonar:sonar -Dsonar.projectKey=YOUR_PROJECT_KEY -Dsonar.organization=YOUR_ORGANIZATION -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=YOUR_SONAR_TOKEN
   ```

## 3-Tier Architecture

### Database Tier (RDS)

1. **Deploy MySQL RDS**:
   - Create a MySQL RDS instance in the private subnet:

   ```bash
   aws rds create-db-instance --db-instance-identifier mydbinstance --db-instance-class db.t2.micro --engine mysql --allocated-storage 20 --master-username admin --master-user-password password --vpc-security-group-ids sg-db --db-subnet-group-name mydbsubnetgroup
   ```

### Backend Tier (Tomcat)

1. **Network Load Balancer**:
   - Create a private-facing Network Load Balancer:

   ```bash
   aws elbv2 create-load-balancer --name private-nlb --subnets subnet-xxxx subnet-yyyy --type network
   ```

2. **Auto Scaling Group**:
   - Set up an Auto Scaling Group for the Tomcat instances:

   ```bash
   aws autoscaling create-auto-scaling-group --auto-scaling-group-name tomcat-asg --launch-configuration-name TomcatLC --min-size 1 --max-size 3 --vpc-zone-identifier subnet-xxxx,subnet-yyyy
   ```

### Frontend Tier (Nginx)

1. **Public Network Load Balancer**:
   - Create a public-facing Network Load Balancer:

   ```bash
   aws elbv2 create-load-balancer --name public-nlb --subnets subnet-xxxx subnet-yyyy --type network
   ```

2. **Auto Scaling Group**:
   - Set up an Auto Scaling Group for the Nginx instances:

   ```bash
   aws autoscaling create-auto-scaling-group --auto-scaling-group-name nginx-asg --launch-configuration-name NginxLC --min-size 1 --max-size 3 --vpc-zone-identifier subnet-xxxx,subnet-yyyy
   ```

## Application Deployment

### Deploying Artifacts

1. **User Data Scripts**:
   - Use user data scripts to deploy artifacts during the EC2 instance launch. Ensure the script fetches the `.war` file from JFrog and places it in the Tomcat `webapps` directory.

2. **Database Setup**:
   - Log into the MySQL database from the Tomcat server and create the database schema:

   ```bash
   mysql -h mydbinstance.123456789012.us-east-1.rds.amazonaws.com -u admin -p
   CREATE DATABASE mydatabase;
   USE mydatabase;
   SOURCE /path/to/schema.sql;
   ```

## Post-Deployment

### Logging and Monitoring

1. **Cron Job for Logs**:
   - Set up a Cron job to push Tomcat logs to an S3 bucket:

   ```bash
   crontab -e
   ```

   Add the following entry:

   ```bash
   0 0 * * * /usr/bin/aws s3 cp /path/to/tomcat/logs s3://mybucket/tomcat-logs/ --recursive --region us-east-1 && rm -rf /path/to/tomcat/logs/*
   ```

2. **CloudWatch Alarms**:
   - Set up CloudWatch alarms to monitor database connections:

   ```bash
   aws cloudwatch put-metric-alarm --alarm-name "DBConnectionsHigh" --metric-name DatabaseConnections --namespace AWS/RDS --statistic Average --period 300 --threshold 100 --comparison-operator GreaterThanOrEqualToThreshold --evaluation-periods 1 --alarm-actions arn:aws:sns:us-east-1:123456789012:MySNSTopic
   ```

## Validation

1. **EC2 Access**:
   - Verify SSH access to EC2 instances via the Bastion Host and Systems Manager.

2. **Application Accessibility**:
   - Ensure the application is accessible from a public internet browser.

## Final Note

> [!Important]
>
> _If you find this repository useful for learning, please give it a star on GitHub. Thank you!_

---

## **Author by:**

![](https://imgur.com/2j6Aoyl.png)

> [!Note]
> **Join Our** [Telegram Community](https://t.me/prodevopsguy) // [Follow me](https://github.com/NotHarshhaa) **for more DevOps & Cloud content.**
a20ef9ac0556037ba710c2e1338e6704c9146cab
