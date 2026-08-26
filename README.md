<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,50:0F172A,100:0369A1&text=PRIYANSHU%20PANWAR&fontSize=48&fontColor=38BDF8&fontAlignY=38&desc=CLOUD%20%7C%20DEVOPS%20%7C%20AWS%20%7C%20KUBERNETES&descAlignY=62&descSize=18&animation=fadeIn" width="100%"/>

<br>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=21&duration=2200&pause=700&color=38BDF8&center=true&vCenter=true&width=900&lines=%24+whoami;Cloud+%26+DevOps+Engineer;AWS+%7C+Docker+%7C+Kubernetes+%7C+Terraform;CI%2FCD+%7C+Linux+%7C+Infrastructure+as+Code;Building+Cloud+Infrastructure+that+Actually+Works.;Automate.+Deploy.+Scale.+Observe." />

<br><br>

<a href="https://priyanshu-cloud-engineer.vercel.app/">
<img src="https://img.shields.io/badge/%E2%96%B6%20LIVE%20PORTFOLIO-38BDF8?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/priyanshu-panwar-cloud-devops">
<img src="https://img.shields.io/badge/%E2%96%B6%20LINKEDIN-2563EB?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:priyanshu.panwar841@gmail.com">
<img src="https://img.shields.io/badge/%E2%96%B6%20CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=priyanshupanwar066&style=for-the-badge&color=38BDF8&label=PROFILE+VIEWS"/>

</div>

---

# 🖥️ `terminal@priyanshu:~$ ./about-me`

```bash
┌──(priyanshu㉿cloud-devops)-[~/profile]
└─$ cat about.txt

Name         : Priyanshu Panwar
Role         : Cloud & DevOps Engineer
Speciality   : Cloud Infrastructure & Automation
Cloud        : AWS
Containers   : Docker
Orchestration: Kubernetes / Amazon EKS
IaC          : Terraform
CI/CD        : GitHub Actions / Jenkins
OS           : Linux

Certification:
  AWS Certified Cloud Practitioner

Mission:
  Build it.
  Automate it.
  Deploy it.
  Monitor it.
  Make it better.
```

---

# ☁️ `01 / CLOUD & DEVOPS`

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,githubactions,jenkins,linux,bash&perline=8"/>

<br><br>

<img src="https://img.shields.io/badge/AWS-CLOUD-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/KUBERNETES-ORCHESTRATION-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/DOCKER-CONTAINERS-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/TERRAFORM-INFRASTRUCTURE-844FBA?style=for-the-badge&logo=terraform&logoColor=white"/>

</div>

<br>

| ☁️ Cloud |     🐳 Containers    | ☸️ Platform |  ⚙️ Automation |
| :------: | :------------------: | :---------: | :------------: |
|    AWS   |        Docker        |  Kubernetes | GitHub Actions |
|    EC2   |    Docker Compose    |  Amazon EKS |     Jenkins    |
|    S3    |   Containerization   | Deployments |       Git      |
|    RDS   |   Image Management   |   Services  |      Bash      |
|    ECS   | Multi-container Apps |   Scaling   |     Python     |
|  Lambda  |           —          |    Nginx    |        —       |

---

# 🏗️ `02 / CLOUD ARCHITECTURE`

<div align="center">

### `FROM INTERNET → AWS → KUBERNETES → APPLICATION`

</div>

```mermaid
flowchart TB

    USER["🌍 USERS"] --> DNS["🌐 Route 53"]

    DNS --> LB["⚖️ Load Balancer"]

    LB --> VPC["☁️ AWS VPC"]

    VPC --> PUBLIC["🌐 Public Subnet"]
    VPC --> PRIVATE["🔒 Private Subnet"]

    PUBLIC --> EKS["☸️ Amazon EKS"]

    EKS --> POD1["🐳 Application Pod"]
    EKS --> POD2["🐳 Application Pod"]
    EKS --> POD3["🐳 Application Pod"]

    PRIVATE --> RDS["🗄️ Amazon RDS"]

    EKS --> S3["🪣 Amazon S3"]

    EKS --> CW["📊 CloudWatch"]

    style USER fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style DNS fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style LB fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style VPC fill:#0F172A,stroke:#FF9900,color:#FFFFFF
    style PUBLIC fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style PRIVATE fill:#161b22,stroke:#A855F7,color:#FFFFFF
    style EKS fill:#161b22,stroke:#326CE5,color:#FFFFFF
    style POD1 fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style POD2 fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style POD3 fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style RDS fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style S3 fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style CW fill:#161b22,stroke:#A855F7,color:#FFFFFF
```

<div align="center">

`AWS` → `VPC` → `EKS` → `CONTAINERS` → `APPLICATION`

</div>

---

# ⚙️ `03 / DEVOPS PIPELINE`

<div align="center">

### `COMMIT → BUILD → TEST → SCAN → CONTAINERIZE → DEPLOY → MONITOR`

</div>

```mermaid
flowchart LR

    DEV["👨‍💻 Developer"]
    GIT["🐙 GitHub"]
    CI["⚡ GitHub Actions"]
    QUALITY["🔍 SonarQube"]
    BUILD["🔨 Build"]
    DOCKER["🐳 Docker"]
    REGISTRY["📦 Registry"]
    K8S["☸️ Kubernetes"]
    EKS["☁️ Amazon EKS"]
    APP["🚀 Application"]
    MONITOR["📊 Monitor"]

    DEV --> GIT
    GIT --> CI
    CI --> QUALITY
    QUALITY --> BUILD
    BUILD --> DOCKER
    DOCKER --> REGISTRY
    REGISTRY --> K8S
    K8S --> EKS
    EKS --> APP
    APP --> MONITOR

    style DEV fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style GIT fill:#161b22,stroke:#FFFFFF,color:#FFFFFF
    style CI fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style QUALITY fill:#161b22,stroke:#F59E0B,color:#FFFFFF
    style BUILD fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style DOCKER fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style REGISTRY fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style K8S fill:#161b22,stroke:#326CE5,color:#FFFFFF
    style EKS fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style APP fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style MONITOR fill:#161b22,stroke:#A855F7,color:#FFFFFF
```

---

# 🐳 `04 / CONTAINERIZATION`

<div align="center">

### `BUILD ONCE • RUN ANYWHERE`

</div>

```mermaid
flowchart LR

    CODE["💻 Application Code"]
    FILE["📄 Dockerfile"]
    IMAGE["📦 Docker Image"]
    REGISTRY["☁️ Container Registry"]
    CONTAINER["🐳 Running Container"]
    K8S["☸️ Kubernetes"]

    CODE --> FILE
    FILE --> IMAGE
    IMAGE --> REGISTRY
    REGISTRY --> CONTAINER
    CONTAINER --> K8S

    style CODE fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style FILE fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style IMAGE fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style REGISTRY fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style CONTAINER fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style K8S fill:#161b22,stroke:#326CE5,color:#FFFFFF
```

### Docker Toolkit

`Dockerfile` · `Docker Images` · `Containers` · `Docker Compose` · `Multi-container Applications`

---

# ☸️ `05 / KUBERNETES`

<div align="center">

### `CONTAINER ORCHESTRATION`

</div>

```mermaid
flowchart TB

    CLUSTER["☸️ KUBERNETES CLUSTER"]

    CLUSTER --> NS["📁 Namespace"]

    NS --> DEP["🚀 Deployment"]

    DEP --> RS["🔄 ReplicaSet"]

    RS --> POD1["🐳 Pod"]
    RS --> POD2["🐳 Pod"]
    RS --> POD3["🐳 Pod"]

    INGRESS["🚪 Ingress"] --> SERVICE["🌐 Service"]

    SERVICE --> POD1
    SERVICE --> POD2
    SERVICE --> POD3

    HPA["📈 HPA<br/>Auto Scaling"] --> DEP

    style CLUSTER fill:#0F172A,stroke:#326CE5,color:#FFFFFF
    style NS fill:#161b22,stroke:#A855F7,color:#FFFFFF
    style DEP fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style RS fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style POD1 fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style POD2 fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style POD3 fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style SERVICE fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style INGRESS fill:#161b22,stroke:#F59E0B,color:#FFFFFF
    style HPA fill:#161b22,stroke:#A855F7,color:#FFFFFF
```

<div align="center">

`DEPLOYMENTS` · `SERVICES` · `PODS` · `SCALING` · `INGRESS` · `EKS`

</div>

---

# 🏗️ `06 / INFRASTRUCTURE AS CODE`

<div align="center">

### `TERRAFORM → AWS INFRASTRUCTURE`

</div>

```mermaid
flowchart LR

    TF["📄 Terraform"]
    PLAN["🔎 terraform plan"]
    APPLY["🚀 terraform apply"]

    TF --> PLAN
    PLAN --> APPLY

    APPLY --> VPC["☁️ VPC"]
    APPLY --> EC2["🖥️ EC2"]
    APPLY --> EKS["☸️ EKS"]
    APPLY --> RDS["🗄️ RDS"]
    APPLY --> S3["🪣 S3"]

    style TF fill:#161b22,stroke:#844FBA,color:#FFFFFF
    style PLAN fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style APPLY fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style VPC fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style EC2 fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style EKS fill:#161b22,stroke:#326CE5,color:#FFFFFF
    style RDS fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style S3 fill:#161b22,stroke:#FF9900,color:#FFFFFF
```

### Infrastructure Philosophy

```text
DEFINE
   ↓
PLAN
   ↓
APPLY
   ↓
PROVISION
   ↓
CONFIGURE
   ↓
DEPLOY
   ↓
MANAGE
```

---

# 🚀 `07 / FEATURED PROJECT`

<div align="center">

# 🏠 EstateHub

### `CLOUD-NATIVE DEVOPS DEPLOYMENT`

<a href="https://github.com/priyanshupanwar066/estatehub-devops">

<img src="https://img.shields.io/badge/🚀%20EXPLORE%20PROJECT-181717?style=for-the-badge&logo=github&logoColor=white"/>

</a>

</div>

```mermaid
flowchart LR

    DEV["👨‍💻 Developer"]
    GIT["🐙 GitHub"]
    DOCKER["🐳 Docker"]
    K8S["☸️ Kubernetes"]
    EKS["☁️ Amazon EKS"]
    APP["🏠 EstateHub"]

    DEV -->|Push| GIT
    GIT -->|Build| DOCKER
    DOCKER -->|Deploy| K8S
    K8S -->|Orchestrate| EKS
    EKS -->|Run| APP

    style DEV fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style GIT fill:#161b22,stroke:#FFFFFF,color:#FFFFFF
    style DOCKER fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style K8S fill:#161b22,stroke:#326CE5,color:#FFFFFF
    style EKS fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style APP fill:#161b22,stroke:#22C55E,color:#FFFFFF
```

### 🔧 Project Stack

<div align="center">

<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>

</div>

### DevOps Implementation

* 🐳 Containerized application deployment
* ☸️ Kubernetes orchestration
* ☁️ Amazon EKS deployment
* 📦 Docker image management
* 🚀 Cloud-native deployment workflow
* 📈 Scalability and availability concepts
* 🛠️ Infrastructure and deployment troubleshooting

---

# 💼 `08 / PROFESSIONAL EXPERIENCE`

<div align="center">

## 🔧 DevOps Engineer Intern

### Wyreflow Technologies

`JUN 2026 → SEP 2026`

</div>

```mermaid
flowchart LR

    CODE["💻 CODE"]
    GIT["🐙 GIT"]
    CI["⚡ CI/CD"]
    DOCKER["🐳 DOCKER"]
    QUALITY["🔍 SONARQUBE"]
    DEPLOY["🚀 DEPLOY"]
    TROUBLE["🛠️ TROUBLESHOOT"]

    CODE --> GIT
    GIT --> CI
    CI --> DOCKER
    CI --> QUALITY
    DOCKER --> DEPLOY
    QUALITY --> DEPLOY
    DEPLOY --> TROUBLE

    style CODE fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style GIT fill:#161b22,stroke:#FFFFFF,color:#FFFFFF
    style CI fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style DOCKER fill:#161b22,stroke:#2496ED,color:#FFFFFF
    style QUALITY fill:#161b22,stroke:#F59E0B,color:#FFFFFF
    style DEPLOY fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style TROUBLE fill:#161b22,stroke:#A855F7,color:#FFFFFF
```

### Hands-on Areas

* ⚙️ CI/CD workflows
* 🐳 Docker & Docker Compose
* ⚡ GitHub Actions
* 🔍 SonarQube
* 🐙 Git & GitHub workflows
* 🚀 Application deployment
* 🛠️ Environment troubleshooting
* 🤝 Deployment process improvement

---

# 🧰 `09 / TECHNICAL ARSENAL`

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,githubactions,jenkins,linux,bash,git,github,python&perline=11"/>

<br><br>

<img src="https://skillicons.dev/icons?i=html,css,js,react,nextjs,nodejs,express,mongodb,mysql,postgresql,vscode,postman,figma&perline=13"/>

</div>

<br>

| Category              | Technologies                               |
| --------------------- | ------------------------------------------ |
| ☁️ **Cloud**          | AWS, EC2, S3, RDS, ECS, Lambda, DynamoDB   |
| 🔐 **AWS Security**   | IAM, VPC, Security Groups                  |
| 🌐 **AWS Networking** | Route 53, Load Balancing, Subnets, Routing |
| 🐳 **Containers**     | Docker, Docker Compose                     |
| ☸️ **Orchestration**  | Kubernetes, Amazon EKS                     |
| 🏗️ **IaC**           | Terraform, CloudFormation                  |
| 🔄 **CI/CD**          | GitHub Actions, Jenkins                    |
| 🐧 **Systems**        | Linux, Ubuntu, CentOS, Bash                |
| 🔍 **Quality**        | SonarQube, Selenium                        |
| 💻 **Frontend**       | React.js, Next.js, HTML, CSS, JavaScript   |
| ⚙️ **Backend**        | Node.js, Express.js, REST APIs             |
| 🗄️ **Database**      | MongoDB Atlas, MySQL, PostgreSQL           |
| 🔧 **Tools**          | Git, GitHub, VS Code, Postman, Figma       |

---

# 🌐 `10 / NETWORKING`

```mermaid
flowchart TB

    INTERNET["🌍 INTERNET"]
    DNS["🌐 DNS"]
    LB["⚖️ LOAD BALANCER"]
    VPC["☁️ VPC"]

    INTERNET --> DNS
    DNS --> LB
    LB --> VPC

    VPC --> PUBLIC["🌐 PUBLIC SUBNET"]
    VPC --> PRIVATE["🔒 PRIVATE SUBNET"]

    PUBLIC --> EC2["🖥️ EC2"]
    PRIVATE --> RDS["🗄️ RDS"]

    style INTERNET fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style DNS fill:#161b22,stroke:#38BDF8,color:#FFFFFF
    style LB fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style VPC fill:#0F172A,stroke:#FF9900,color:#FFFFFF
    style PUBLIC fill:#161b22,stroke:#22C55E,color:#FFFFFF
    style PRIVATE fill:#161b22,stroke:#A855F7,color:#FFFFFF
    style EC2 fill:#161b22,stroke:#FF9900,color:#FFFFFF
    style RDS fill:#161b22,stroke:#FF9900,color:#FFFFFF
```

### Networking Knowledge

`TCP/IP` · `DNS` · `HTTP/HTTPS` · `SSH` · `VPN` · `Routing` · `Subnetting` · `Load Balancing` · `Firewalls`

---

# 📊 `11 / GITHUB SYSTEM STATUS`

<div align="center">

### `LIVE PROFILE METRICS`

<br>

<img src="https://img.shields.io/github/followers/priyanshupanwar066?style=for-the-badge&logo=github&label=FOLLOWERS&color=38BDF8"/>

<img src="https://img.shields.io/github/stars/priyanshupanwar066?style=for-the-badge&logo=github&label=TOTAL%20STARS&color=F59E0B"/>

<img src="https://img.shields.io/github/repos/priyanshupanwar066?style=for-the-badge&logo=github&label=PUBLIC%20REPOSITORIES&color=22C55E"/>

<br><br>

<img src="https://img.shields.io/github/last-commit/priyanshupanwar066/priyanshupanwar066?style=for-the-badge&logo=github&label=PROFILE%20LAST%20UPDATE&color=A855F7"/>

<br><br>

### `ENGINEERING ACTIVITY`
 
<img src="https://img.shields.io/github/followers/priyanshupanwar066?style=for-the-badge&logo=github&label=FOLLOWERS&color=38BDF8"/>
<img src="https://img.shields.io/github/stars/priyanshupanwar066?style=for-the-badge&logo=github&label=TOTAL%20STARS&color=F59E0B"/>
<br/><br/>
 
<a href="https://github.com/priyanshupanwar066">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=priyanshupanwar066&theme=github_dark" width="95%"/>
</a>
</div>

---

# 🐍 `12 / CONTRIBUTION MATRIX`

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake" width="95%"/>

</div>

---

# 🧠 `13 / ENGINEERING MINDSET`

<div align="center">

```text
                 ┌─────────────────────┐
                 │     PROBLEM         │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │      AUTOMATE       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │       DEPLOY        │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │       MONITOR       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │       IMPROVE       │
                 └─────────────────────┘
```

### **Make it work → Make it automated → Make it reliable.**

<br>

`AUTOMATION`   `RELIABILITY`   `SCALABILITY`   `SECURITY`   `OBSERVABILITY`

</div>

---

# 🎯 `14 / CURRENTLY BUILDING`

<div align="center">

```text
╔══════════════════════════════════════════════╗
║              CURRENT OBJECTIVES              ║
╠══════════════════════════════════════════════╣
║                                              ║
║  ☁️  AWS Cloud Architecture                  ║
║  ☸️  Advanced Kubernetes / EKS              ║
║  🏗️  Terraform Infrastructure               ║
║  🔄  CI/CD Optimization                      ║
║  📊  Monitoring & Observability              ║
║  🔐  Cloud Security                          ║
║  🐧  Linux Administration                    ║
║                                              ║
╚══════════════════════════════════════════════╝
```

</div>

---

# 🏆 `15 / CERTIFICATION`

<div align="center">

<img src="https://img.shields.io/badge/AWS%20CERTIFIED-CLOUD%20PRACTITIONER-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>

</div>

---

# 🎓 `16 / EDUCATION`

<div align="center">

## 🎓 MCA — Data Science

**Bennett University, Greater Noida**

`2025 → 2027`

<br>

⬇️

<br>

## 🎓 BCA

**Maa Shakumbhari University, Saharanpur**

`2022 → 2025`

</div>

---

# 🟢 `17 / OPEN TO OPPORTUNITIES`

<div align="center">

<img src="https://img.shields.io/badge/CLOUD%20ENGINEER-OPEN-22C55E?style=for-the-badge&logo=amazonaws&logoColor=white"/>

<img src="https://img.shields.io/badge/DEVOPS%20ENGINEER-OPEN-22C55E?style=for-the-badge&logo=kubernetes&logoColor=white"/>

<br><br>

<img src="https://img.shields.io/badge/PLATFORM%20ENGINEERING-INTERESTED-0EA5E9?style=for-the-badge"/>

<img src="https://img.shields.io/badge/CLOUD%20INFRASTRUCTURE-INTERESTED-0EA5E9?style=for-the-badge"/>

</div>

---

# 🤝 `18 / CONNECT`

<div align="center">

### Interested in Cloud, DevOps, Kubernetes or Infrastructure?

### Let's build something that survives production. 🚀

<br>

<a href="https://priyanshu-cloud-engineer.vercel.app/">
<img src="https://img.shields.io/badge/🌐%20PORTFOLIO-VISIT-0EA5E9?style=for-the-badge"/>
</a>

<a href="https://www.linkedin.com/in/priyanshu-panwar-cloud-devops">
<img src="https://img.shields.io/badge/💼%20LINKEDIN-CONNECT-2563EB?style=for-the-badge"/>
</a>

<a href="mailto:priyanshu.panwar841@gmail.com">
<img src="https://img.shields.io/badge/📩%20EMAIL-CONTACT-EA4335?style=for-the-badge"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=priyanshupanwar066&style=for-the-badge&color=38BDF8&label=THANKS+FOR+VISITING"/>

<br><br>

```text
☁️ CLOUD
   ↓
⚙️ AUTOMATE
   ↓
🐳 CONTAINERIZE
   ↓
☸️ ORCHESTRATE
   ↓
🚀 DEPLOY
   ↓
📊 OBSERVE
   ↓
🔁 IMPROVE
```

<br>

### `BUILD • AUTOMATE • DEPLOY • SCALE`

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:0369A1,100:38BDF8&height=140&section=footer" width="100%"/>
