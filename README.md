
<div align="center">

<img src="https://raw.githubusercontent.com/sachintaji/sachintaji/main/sachin-cloud-banner.png" width="100%" alt="Sachin Taji - AWS Cloud Engineer"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00A8FF&center=true&vCenter=true&width=700&lines=AWS+Cloud+Engineer;Terraform+%7C+Infrastructure+as+Code;Linux+%7C+Cloud+Networking;DevOps+%7C+CI%2FCD+Automation;Building+Cloud+Infrastructure" alt="Typing animation"/>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=3&section=header" width="80%"/>

<h1>☁️ SACHIN TAJI</h1>

<h3>AWS Cloud Engineer • Terraform • Linux • DevOps</h3>

<p>
  <b>Cloud Infrastructure | Infrastructure as Code | Automation | Networking | Monitoring</b>
</p>

<p>
  <i>Building practical cloud solutions, automating infrastructure, and continuously improving my engineering skills.</i>
</p>

<br/>

<a href="https://github.com/sachintaji">
<img src="https://img.shields.io/badge/GitHub-Sachin%20Taji-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/sachin-taji-2b1455288/">
<img src="https://img.shields.io/badge/LinkedIn-Sachin%20Taji-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<img src="https://komarev.com/ghpvc/?username=sachintaji&label=PROFILE+VIEWS&style=for-the-badge"/>

<br/><br/>

<img src="https://img.shields.io/badge/Focus-AWS%20Cloud%20Engineering-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Infrastructure-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/OS-Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Automation-DevOps-00A8FF?style=flat-square"/>

</div>

---

# 🧑‍💻 About Me

Hello! I'm **Sachin Taji**, an aspiring **AWS Cloud Engineer** focused on cloud infrastructure, Infrastructure as Code, Linux administration, and DevOps automation.

I enjoy understanding how cloud services work together to create reliable and scalable infrastructure. My learning is based on hands-on implementation, troubleshooting, and building practical projects.

I am currently developing my skills in AWS, Terraform, Linux, Jenkins, Docker, Git, and cloud networking.

### 👨‍💻 My Engineering Mindset

```text
              LEARN
                │
                ▼
             DESIGN
                │
                ▼
              BUILD
                │
                ▼
           TROUBLESHOOT
                │
                ▼
            AUTOMATE
                │
                ▼
             MONITOR
                │
                ▼
             IMPROVE
                │
                └───────────────↺
```

### 🎯 My Current Focus

- Designing and understanding AWS cloud infrastructure.
- Creating repeatable infrastructure using Terraform.
- Strengthening Linux administration and troubleshooting.
- Learning Jenkins and CI/CD pipeline workflows.
- Practicing Docker application containerization.
- Understanding cloud networking, security, and monitoring.
- Building projects that connect multiple cloud services together.

---

# ☁️ AWS CLOUD ENGINEERING

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="110" alt="AWS"/>

<h3>Amazon Web Services</h3>

<p>
  <i>Compute • Networking • Storage • Databases • Security • Monitoring</i>
</p>

</div>

AWS is my primary cloud platform. I practice creating and understanding cloud infrastructure using different AWS services.

## 🧩 AWS Services

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ Compute

- Amazon EC2
- AWS Lambda
- AMI
- EBS
- Auto Scaling

</td>
<td width="50%" valign="top">

### 🌐 Networking

- Amazon VPC
- Public and Private Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
- Application Load Balancer

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗄️ Storage & Database

- Amazon S3
- Amazon EBS
- Amazon RDS
- MySQL
- Database Connectivity

</td>
<td width="50%" valign="top">

### 🔐 Security & Operations

- AWS IAM
- IAM Roles and Policies
- Security Groups
- Amazon CloudWatch
- Amazon SNS
- Amazon Route 53

</td>
</tr>
</table>

## 🌐 AWS Architecture Concepts

```text
┌───────────────────────────────────────────────┐
│                  AWS REGION                   │
│                                               │
│  ┌─────────────────────────────────────────┐  │
│  │                   VPC                   │  │
│  │                                         │  │
│  │  ┌──────────────┐  ┌─────────────────┐ │  │
│  │  │ PUBLIC       │  │ PRIVATE         │ │  │
│  │  │ SUBNET       │  │ SUBNET          │ │  │
│  │  │              │  │                 │ │  │
│  │  │ ALB          │  │ Application EC2 │ │  │
│  │  │ Bastion      │  │                 │ │  │
│  │  └──────┬───────┘  └────────┬────────┘ │  │
│  │         │                   │          │  │
│  │         ▼                   ▼          │  │
│  │   Internet GW          NAT Gateway     │  │
│  │                             │          │  │
│  └─────────────────────────────┼──────────┘  │
│                                ▼             │
│                             Internet         │
└───────────────────────────────────────────────┘
```

### AWS Topics I Practice

| Category | Topics |
|---|---|
| Compute | EC2, AMI, EBS, Auto Scaling |
| Networking | VPC, CIDR, Subnets, Route Tables |
| Connectivity | IGW, NAT Gateway, Security Groups |
| Availability | Availability Zones, ALB, Auto Scaling |
| Storage | S3, EBS |
| Database | RDS MySQL |
| Security | IAM, Roles, Policies |
| DNS | Route 53 |
| Monitoring | CloudWatch, SNS |

---

# 🏗️ TERRAFORM — INFRASTRUCTURE AS CODE

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" width="100" alt="Terraform"/>

<h3>Define Infrastructure. Automate Deployment. Manage Changes.</h3>

</div>

Terraform is one of my main tools for practicing Infrastructure as Code. I use Terraform concepts to define cloud resources in configuration files and understand how infrastructure can be created consistently.

## 🔧 Terraform Workflow

```text
         TERRAFORM CODE
                │
                ▼
        terraform init
                │
                ▼
        terraform validate
                │
                ▼
         terraform plan
                │
                ▼
         terraform apply
                │
                ▼
          AWS RESOURCES
                │
                ▼
       terraform outputs
                │
                ▼
         Infrastructure
           Management
```

## 🧱 Terraform Skills

- Terraform providers
- Resources and data sources
- Input variables
- Outputs
- Local values
- Resource dependencies
- Terraform modules
- Module inputs and outputs
- Terraform state
- Remote backend
- Infrastructure planning
- Configuration management
- Reusable infrastructure design

## 📁 Infrastructure Project Structure

```text
terraform-infrastructure/
│
├── providers.tf
├── main.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars
│
├── modules/
│   └── vpc/
│       ├── main.tf
│       ├── variables.tf
│       └── outputs.tf
│
└── environments/
    └── dev/
        └── terraform.tfvars
```

### Terraform + AWS

```text
Terraform Configuration
          │
          ▼
     AWS Provider
          │
          ▼
       VPC Module
          │
    ┌─────┼─────┐
    ▼     ▼     ▼
  EC2    ALB    RDS
    │     │     │
    └─────┼─────┘
          ▼
    CloudWatch
```

---

# 🐧 LINUX ADMINISTRATION

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="90" alt="Linux"/>

<h3>Linux • Ubuntu • Amazon Linux</h3>

</div>

Linux is an important foundation for cloud engineering and DevOps. I practice Linux commands, server administration, permissions, networking, services, and troubleshooting.

## 🔍 Linux Areas

<table>
<tr>
<td width="50%" valign="top">

### 📂 File Management

- Files and directories
- `ls`, `cd`, `pwd`
- `cp`, `mv`, `rm`
- `mkdir`, `touch`
- `find`, `grep`
- File permissions
- Ownership

</td>
<td width="50%" valign="top">

### ⚙️ System Administration

- Users and groups
- `chmod`, `chown`
- Processes
- Services
- Package management
- SSH
- Log management

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌐 Networking

- IP configuration
- `ip`
- `ss`
- `ping`
- `curl`
- DNS troubleshooting
- Remote connectivity

</td>
<td width="50%" valign="top">

### 📊 Monitoring

- CPU usage
- Memory usage
- Disk space
- Running processes
- System logs
- Service status
- Troubleshooting

</td>
</tr>
</table>

## 🖥️ Linux Commands I Practice

```bash
# File and directory management
ls -la
pwd
cd /var/log
mkdir project
cp file.txt backup.txt
mv old.txt new.txt
rm file.txt

# Search and text processing
cat file.txt
less file.txt
grep "error" application.log
find /var/log -name "*.log"

# Permissions and ownership
chmod 755 script.sh
chown user:group file.txt

# Processes and services
ps aux
top
systemctl status nginx
journalctl -u nginx

# Disk and memory
df -h
du -sh /var/log
free -m

# Networking
ip addr
ss -tulnp
ping example.com
curl http://localhost

# Remote administration
ssh user@server
scp file.txt user@server:/tmp/
```

---

# 🔄 GIT & GITHUB

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="80" alt="Git"/>

<h3>Version Control • Collaboration • Infrastructure Code</h3>

</div>

I use Git and GitHub to manage project code, Terraform configurations, documentation, and version history.

## 🔁 Git Workflow

```text
       WORKING DIRECTORY
                │
                ▼
          git add
                │
                ▼
          git commit
                │
                ▼
          git push
                │
                ▼
             GitHub
                │
                ▼
         Collaboration
                │
                ▼
         Pull Requests
```

### Git Topics

- Repository creation
- Clone and remote management
- Branches
- Commits
- Push and pull
- Merge
- Pull Requests
- `.gitignore`
- Branch-based workflows
- Conflict resolution
- Tracking infrastructure code

---

# 🔄 JENKINS & CI/CD AUTOMATION

<div align="center">

<img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" width="85" alt="Jenkins"/>

<h3>Automate Repetitive Workflows</h3>

</div>

I'm learning how Jenkins can be used to automate infrastructure workflows and connect source control with Terraform.

## 🚀 CI/CD Pipeline

```text
          DEVELOPER
              │
              ▼
           GITHUB
              │
              ▼
           JENKINS
              │
       ┌──────┴──────┐
       ▼             ▼
   Checkout       Validation
       │             │
       └──────┬──────┘
              ▼
       Terraform Init
              │
              ▼
       Terraform Plan
              │
              ▼
       Approval / Apply
              │
              ▼
          AWS CLOUD
              │
              ▼
         Monitoring
```



# 🐳 DOCKER & CONTAINERIZATION

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="100" alt="Docker"/>

<h3>Package Applications into Portable Containers</h3>

</div>

I'm building practical Docker knowledge by creating Dockerfiles, building images, running containers, exposing ports, and testing applications on Linux servers.

## 📦 Docker Workflow

```text
       APPLICATION CODE
              │
              ▼
          Dockerfile
              │
              ▼
         Docker Build
              │
              ▼
          Docker Image
              │
              ▼
       Docker Container
              │
              ▼
        Exposed Port
              │
              ▼
         Application
```

### Docker Topics

- Dockerfile
- Docker images
- Containers
- Port mapping
- Container lifecycle
- Basic container networking
- Application deployment
- Running containers on EC2/Linux

---

# 📊 CLOUDWATCH & MONITORING

<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="90" alt="AWS"/>

<h3>Observe Infrastructure • Understand Metrics • Troubleshoot</h3>

</div>

Monitoring is important for understanding the health and performance of cloud infrastructure.

### Monitoring Areas

- EC2 CPU utilization
- Memory monitoring concepts
- CloudWatch metrics
- CloudWatch log groups
- Log streams
- Application logs
- CloudWatch agent concepts
- Alarms and notifications
- SNS integration concepts

```text
          AWS RESOURCES
                │
      ┌─────────┼─────────┐
      ▼         ▼         ▼
     EC2        ALB       RDS
      │         │         │
      └─────────┼─────────┘
                ▼
           CloudWatch
                │
       ┌────────┴────────┐
       ▼                 ▼
     Metrics            Logs
       │                 │
       └────────┬────────┘
                ▼
             Alarms
                │
                ▼
               SNS
```

---

# 🚀 FEATURED PROJECT

## AWS Multi-Tier Infrastructure Automation

<div align="center">

<img src="https://img.shields.io/badge/Project-AWS%20Infrastructure-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/IaC-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/Automation-Jenkins- D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>

</div>

A practical infrastructure project focused on designing and managing a structured AWS environment using Terraform.

### Project Goals

- Understand multi-tier infrastructure architecture.
- Create and manage AWS resources using Terraform.
- Practice networking and subnet design.
- Configure compute and database resources.
- Understand load balancing and scalability.
- Practice monitoring and infrastructure automation.

## 🏛️ Architecture

```text
                         🌐 INTERNET
                              │
                              ▼
                       ┌────────────┐
                       │  Route 53  │
                       └─────┬──────┘
                             │
                             ▼
                 ┌──────────────────────┐
                 │ Application Load      │
                 │      Balancer        │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
          ┌─────────────┐       ┌─────────────┐
          │    EC2      │       │    EC2      │
          │ Application │       │ Application │
          └──────┬──────┘       └──────┬──────┘
                 │                     │
                 └──────────┬──────────┘
                            ▼
                    ┌──────────────┐
                    │  Amazon RDS  │
                    │     MySQL    │
                    └──────────────┘

                       AWS VPC
                           │
                   ┌───────┴───────┐
                   ▼               ▼
              Public Subnets   Private Subnets
                   │               │
                   └───────┬───────┘
                           ▼
                      CloudWatch
```

### Project Components

| Component | Purpose |
|---|---|
| VPC | Isolated cloud network |
| Public Subnets | Public-facing infrastructure |
| Private Subnets | Internal application/database resources |
| EC2 | Compute and application hosting |
| ALB | Traffic distribution |
| Auto Scaling | Scalable compute architecture |
| RDS MySQL | Managed relational database |
| Route 53 | DNS management |
| IAM | Access control |
| Security Groups | Network access control |
| CloudWatch | Monitoring |
| Terraform | Infrastructure as Code |
| GitHub | Version control |
| Jenkins | Automation practice |

### Project Learning Outcomes

- Understand how AWS resources interact.
- Build infrastructure through Terraform.
- Understand network traffic flow.
- Practice infrastructure troubleshooting.
- Learn how to structure reusable Terraform code.
- Understand how monitoring supports operations.
- Practice automating infrastructure workflows.

---

# 🔐 CLOUD SECURITY

Security is an important part of cloud infrastructure design.

### Security Concepts

```text
                 CLOUD SECURITY
                       │
       ┌───────────────┼───────────────┐
       ▼               ▼               ▼
      IAM         NETWORK SECURITY   ACCESS
       │               │               │
   Roles &         VPC & SG         SSH Keys
   Policies        Subnets          Restricted Ports
   Least           Route Tables     Private Resources
   Privilege
```

### Areas of Practice

- IAM users, roles, and policies
- Least-privilege access concepts
- Security Groups
- Public/private subnet separation
- Restricted inbound access
- SSH key-based access
- Database network isolation
- Infrastructure security considerations

---

# 🧠 CLOUD TROUBLESHOOTING

Cloud engineering involves understanding why infrastructure does not work as expected.

### Scenarios I Practice

| Scenario | Area |
|---|---|
| EC2 cannot be reached | Security Groups / Networking |
| Private instance cannot access the internet | NAT / Route Tables |
| Application is not reachable | Ports / Services / ALB |
| RDS connection fails | Networking / Credentials |
| Terraform resource fails | Configuration / Dependencies |
| Jenkins pipeline fails | Workspace / Pipeline / Permissions |
| Docker application is not accessible | Port Mapping / Container |
| Linux service is down | `systemctl` / Logs |
| Disk space is full | `df` / `du` / Log Management |
| DNS is not resolving | Route 53 / DNS |

---

# 🛠️ COMPLETE TECHNOLOGY STACK

<div align="center">

## ☁️ CLOUD & INFRASTRUCTURE

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="65"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" width="65"/>

## 🔄 DEVOPS & AUTOMATION

<img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" width="60"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="65"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="60"/>

## 🐧 SYSTEMS & WEB

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="60"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" width="60"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="60"/>

## 🗄️ DATABASE & DEVELOPMENT

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="65"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="60"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="60"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="60"/>

</div>

---

# 📋 SKILLS MATRIX

| Skill Category | Technologies |
|---|---|
| Cloud Platform | AWS |
| Compute | EC2, Lambda |
| Networking | VPC, Subnets, IGW, NAT, ALB |
| Infrastructure as Code | Terraform |
| Operating Systems | Linux, Ubuntu, Amazon Linux |
| CI/CD | Jenkins |
| Containers | Docker |
| Version Control | Git, GitHub |
| Monitoring | CloudWatch, SNS |
| Database | MySQL, RDS |
| DNS | Route 53 |
| Web Servers | Nginx, Apache Tomcat |
| Programming Foundation | Java, HTML, CSS |
| Automation | Terraform, Jenkins |

---

# 📚 CURRENT LEARNING ROADMAP

```text
                  AWS CLOUD
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
    Networking      Security      Monitoring
        │             │             │
        └─────────────┼─────────────┘
                      ▼
                 TERRAFORM
                      │
                      ▼
                    LINUX
                      │
                      ▼
                     GIT
                      │
                      ▼
                   JENKINS
                      │
                      ▼
                    DOCKER
                      │
                      ▼
                   DEVOPS
```

### Current Priorities

- Strengthen AWS fundamentals.
- Improve cloud networking knowledge.
- Practice Terraform modules and state.
- Improve Linux administration.
- Build Jenkins pipelines.
- Learn Docker deployment workflows.
- Practice cloud troubleshooting.
- Build and document infrastructure projects.

---

# 💡 ENGINEERING WORKFLOW

I follow a practical approach when learning or building infrastructure.

```text
01. Understand the requirement
          ↓
02. Design the architecture
          ↓
03. Identify cloud resources
          ↓
04. Write Terraform configuration
          ↓
05. Validate and plan
          ↓
06. Deploy infrastructure
          ↓
07. Test connectivity
          ↓
08. Troubleshoot issues
          ↓
09. Monitor resources
          ↓
10. Document the solution
```

---

# 📈 GITHUB STATISTICS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sachintaji&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sachintaji&layout=compact&theme=tokyonight&theme=tokyonight&hide_border=true" width="40%"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sachintaji&theme=tokyonight&hide_border=true" width="60%"/>

</div>

---

# 🐍 CONTRIBUTION ACTIVITY

<div align="center">

<img src="https://raw.githubusercontent.com/sachintaji/sachintaji/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake animation"/>

</div>

---

# 🎯 CAREER OBJECTIVE

I'm working toward opportunities in:

<div align="center">

### ☁️ AWS Cloud Engineer

### 🏗️ Cloud Infrastructure Engineer

### 🔄 DevOps Engineer

### ⚙️ Infrastructure Automation

</div>

My goal is to develop strong practical skills in designing, deploying, securing, monitoring, and automating cloud infrastructure.

I want to contribute to real-world cloud environments while continuously improving my technical knowledge and problem-solving abilities.

---

# 🌱 MY LEARNING PHILOSOPHY

```text
         Learn the Concept
                │
                ▼
         Build the Project
                │
                ▼
        Face the Problem
                │
                ▼
          Find the Cause
                │
                ▼
          Fix the Issue
                │
                ▼
       Understand the Solution
                │
                ▼
          Document It
                │
                ▼
             Improve
```

> **"Good infrastructure is not just created — it is understood, tested, monitored, and continuously improved."**

---

# 🤝 LET'S CONNECT

<div align="center">

<a href="https://github.com/sachintaji">
<img src="https://img.shields.io/badge/GitHub-Sachin%20Taji-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/sachin-taji-2b1455288/">
<img src="https://img.shields.io/badge/LinkedIn-Sachin%20Taji-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br/><br/>

### ☁️ BUILD • AUTOMATE • DEPLOY • MONITOR • IMPROVE

<br/>

**AWS** • **Terraform** • **Linux** • **Git** • **Jenkins** • **Docker**

<br/>

<i>Thanks for visiting my profile! 🚀</i>

</div>
