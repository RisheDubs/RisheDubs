<p align="center">
  <img src="koi/koi.gif" width="256" alt="My koi" />
</p>

# Hi, I'm Rishekesh 👋

**Graduate Software Engineer · Cloud, backend & infrastructure · Melbourne, Australia**

I build backend services and the AWS infrastructure they run on, and I like owning the whole path: from an empty AWS account to a deployed, monitored production system. I care about systems that are boring to run: tested on every push, rolled back automatically, watched by real alarms, and documented well enough that someone else can pick them up.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rishekesh--b-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rishekesh-b-95641120b)
[![Email](https://img.shields.io/badge/Email-rishekeshris%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:rishekeshris@gmail.com)
![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat&logo=amazonwebservices&logoColor=white)

---

## 🚀 Featured projects

### [AI Resume Analyzer](https://github.com/RisheDubs/ai-resume-analyzer)
An event-driven serverless pipeline on AWS that analyses an uploaded resume and returns an ATS score with feedback. Built entirely as Infrastructure as Code.

- **Architecture:** S3 → Lambda → Textract → Bedrock → DynamoDB, behind API Gateway and CloudFront
- **Security:** least-privilege IAM, private storage, authenticated APIs, CORS controls, throttling and layered file validation that rejects bad uploads before any paid AI call
- **Observability:** CloudWatch metric filters, alarms and a dashboard, which I used to diagnose and fix a real production failure

`Python` `AWS Lambda` `Textract` `Bedrock` `DynamoDB` `API Gateway` `CloudFront` `GitHub Actions`

### [Serverless AI-Powered Cake Ordering Platform](https://github.com/RisheDubs/cake-shop) · *in progress*
An ordering platform for a small cake business, with an AI assistant that answers customer questions using live prices.

- **Foundation:** a secure multi-account AWS setup (Organizations, IAM Identity Center SSO, budget alerts) designed for low latency and low running cost
- **Quality gates:** a test-driven REST API, with a GitHub Actions pipeline running linting, formatting and race-enabled tests on every pull request

`AWS Organizations` `IAM Identity Center` `REST API` `GitHub Actions` `TDD`

---

## 💼 What I've done in production

- **Ploviti:** owned the AWS infrastructure and backend API for a new product, from an empty account to a monitored production system
  - Sustained **99.7% uptime** by investigating every CloudWatch alarm to root cause
  - Kept API responses **under 200 ms** through PostgreSQL schema design and query tuning
  - Built CI/CD in GitHub Actions with containerised services and **automatic rollback**
- **Confidential client:** built, deployed and supported backend services and REST APIs end to end, traced production issues from logs to root cause, and wrote the design, API and deployment docs the team relied on

---

## 🛠️ Tech I work with

**Cloud & infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Languages & backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=sqlite&logoColor=white)

**AWS services I use most:** EC2 · S3 · VPC · IAM · RDS · Lambda · CloudWatch · API Gateway · CloudFront

**Also:** networking fundamentals · load balancing & DNS · hybrid connectivity · observability · cloud security · Git

---

## 🌱 Right now

- Studying for the **AWS Solutions Architect – Associate**
- Open to **graduate and junior roles** in cloud, DevOps, backend and infrastructure engineering

## 🎓 Education

- **M.S. Information Technology**, RMIT University, Melbourne (2025): Cloud Computing, Distributed Systems, Cybersecurity
- **B.E. Computer Science**, Kumaraguru College of Technology, India (2023): Operating Systems, Computer Networks

---

<p align="center"><i>Always happy to talk cloud, infrastructure or a good production bug. Reach out on <a href="https://www.linkedin.com/in/rishekesh-b-95641120b">LinkedIn</a>.</i></p>




<!---
RisheDubs/RisheDubs is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
