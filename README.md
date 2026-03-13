<div align="center">

# Emmanuel Ledesma
### Cloud Engineering & DevOps · Buenos Aires, Argentina
#### Transitioning from 10+ years in IBM → Building in public

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emmanuel_Ledesma-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-ledesmam)
[![GitHub](https://img.shields.io/badge/GitHub-EmmaLedesma-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EmmaLedesma)

</div>

---

## 👨‍💻 About Me

I'm a tech professional with 10+ years of IBM experience in IT education, digital transformation and technology adoption across Latin America — currently transitioning into Cloud Engineering and DevOps by building real projects from scratch.

I don't just list skills. I build projects that prove them.

- 🌩️ Provisioning **AWS infrastructure as code** with Terraform and SAM/CloudFormation
- 🐳 Containerizing applications with **Docker** and automating deploys with **GitHub Actions CI/CD**
- ⚡ Building **event-driven pipelines** on AWS (Lambda, S3, SQS, SNS)
- 🚀 Deploying **serverless and containerized apps** on AWS (Lambda, ECS Fargate, ECR)
- 🤖 Integrating **Generative AI** via AWS Bedrock (Claude, Converse API)
- 🐍 Writing **Python** for ETL pipelines, automation and backend logic
- 🗄️ Designing **SQL databases** from scratch and writing complex queries
- 🌐 Developing **REST APIs** and full-stack web applications
- 📦 Emulating cloud environments locally with **LocalStack + Docker**

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎬 yt-summarizer
AI-powered YouTube video summarizer — fully serverless on AWS.
Paste a URL, pick a language, and Claude AI returns a structured summary with key points, topics and content type. Results cached in DynamoDB.

**Highlights:**
- AWS Bedrock (Claude 3.5 Haiku) via Converse API
- Lambda + API Gateway + DynamoDB + S3 + CloudFront
- Transcript extraction via Supadata API (browser-side)
- Language selector (ES, EN, PT and more)
- CloudWatch Dashboard + Alarms as code
- GitHub Actions CI/CD: auto deploy on push
- 100% Terraform IaC ✅

`Python` `AWS Bedrock` `Lambda` `DynamoDB` `CloudFront` `Terraform` `GitHub Actions`

[![CI Frontend](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-frontend.yml/badge.svg)](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-frontend.yml)
[![CI Backend](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-backend.yml/badge.svg)](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-backend.yml)
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://d21n43yg7hlxxz.cloudfront.net)

🔗 [Live Demo](https://d21n43yg7hlxxz.cloudfront.net) · [Repo](https://github.com/EmmaLedesma/youtube-summarizer)

</td>
<td width="50%" valign="top">

### 🏗️ terraform-event-pipeline
Event-driven AWS infrastructure provisioned 100% with Terraform.
File upload to S3 triggers a Lambda that fans out to SQS and SNS — destroyed and recreated from scratch with a single command.

**Highlights:**
- Terraform modules: storage, messaging, compute
- Remote state: S3 backend + DynamoDB locking
- GitHub Actions CI/CD: plan on PR, apply on merge
- 11 AWS resources provisioned as code ✅

`Terraform` `AWS Lambda` `S3` `SQS` `SNS` `IAM` `GitHub Actions`

[![Terraform Apply](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-apply.yml/badge.svg)](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-apply.yml)
[![Terraform Plan](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-plan.yml/badge.svg)](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-plan.yml)

🔗 [Repo](https://github.com/EmmaLedesma/terraform-event-pipeline)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ cloud-file-api
Containerized REST API with full CI/CD pipeline to AWS ECS Fargate.
Manages files on S3 with automated build, test and deploy on every change.

**Highlights:**
- Docker multi-stage build
- GitHub Actions CI (lint + test matrix Node 18/20)
- GitHub Actions CD → ECR + ECS Fargate
- Keyless AWS auth via OIDC (no stored credentials)
- LocalStack for zero-cost local development
- Live deployed ✅

`Node.js` `Docker` `GitHub Actions` `AWS ECS` `ECR` `S3` `OIDC`

[![CI](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/ci.yml/badge.svg)](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/ci.yml)
[![CD](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/cd.yml/badge.svg)](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/cd.yml)

🔗 [API](http://3.84.95.162:3000/health) · [Repo](https://github.com/EmmaLedesma/cloud-file-api)

</td>
<td width="50%" valign="top">

### 🔮 Shem 72 – Angel Calculator
Full-stack serverless app deployed on AWS.
Calculates 3 guardian angels using the Kabbalistic method.

**Highlights:**
- AWS Lambda + API Gateway + S3
- SAM / CloudFormation (IaC)
- Custom REST API in Node.js/Express
- Live deployed ✅

`Node.js` `AWS Lambda` `S3` `SAM` `REST API`

🔗 [Live App](http://shem72-app.s3-website-us-east-1.amazonaws.com) · [Repo](https://github.com/EmmaLedesma/calculadora-72-nombres)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![ECS](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![ECR](https://img.shields.io/badge/ECR-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![LocalStack](https://img.shields.io/badge/LocalStack-000000?style=flat-square&logo=localstack&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F00?style=flat-square&logo=amazon-aws&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 📚 Learning Roadmap

| Skill | Status | Project |
|---|---|---|
| Docker + docker-compose | ✅ Completed | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| GitHub Actions CI/CD | ✅ Completed | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| AWS ECS Fargate + ECR | ✅ Completed | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| Terraform IaC | ✅ Completed | [terraform-event-pipeline](https://github.com/EmmaLedesma/terraform-event-pipeline) |
| AWS Bedrock + Generative AI | ✅ Completed | [yt-summarizer](https://github.com/EmmaLedesma/youtube-summarizer) |
| Terraform avanzado (VPC + EC2 + RDS) | 🔨 Next | `terraform-aws-infra` |
| Kubernetes (EKS) | 📋 Planned | `eks-labs` |
| GCP fundamentals | 📋 Planned | `gcp-labs` |
| Multi-cloud (AWS + GCP) | 📋 Planned | `multicloud-pipeline` |

---

## 🎓 Background

- 💼 **IBM** — 10+ years · IT Education, Digital Transformation, Tech Adoption · LATAM
- 🏫 **IFTS N°18** — Técnico Superior en Análisis de Sistemas (TSAS)
- 🏫 **Universidad de la Ciudad de Buenos Aires** — Licenciatura en Tecnologías Digitales · Articulando
- 📍 Buenos Aires, Argentina

---

<div align="center">

# Emmanuel Ledesma
### Cloud Engineering & DevOps · Buenos Aires, Argentina
#### Transitioning from 10+ years in IBM → Building in public

</div>

---

## 👨‍💻 Sobre mí

Soy un profesional técnico con 10+ años de experiencia en IBM en educación IT, transformación digital y adopción tecnológica en América Latina — actualmente en transición hacia Cloud Engineering y DevOps construyendo proyectos reales desde cero.

No listo habilidades sin respaldo. Construyo proyectos que las demuestran.

- 🌩️ Provisionando **infraestructura AWS como código** con Terraform y SAM/CloudFormation
- 🐳 Containerizando aplicaciones con **Docker** y automatizando deploys con **GitHub Actions CI/CD**
- ⚡ Construyendo **pipelines event-driven** en AWS (Lambda, S3, SQS, SNS)
- 🚀 Deployando **apps serverless y containerizadas** en AWS (Lambda, ECS Fargate, ECR)
- 🤖 Integrando **IA Generativa** via AWS Bedrock (Claude, Converse API)
- 🐍 Escribiendo **Python** para ETL, automatización y lógica backend
- 🗄️ Diseñando **bases de datos SQL** y consultas complejas
- 🌐 Desarrollando **REST APIs** y aplicaciones web full-stack
- 📦 Emulando entornos cloud locales con **LocalStack + Docker**

---

## 🚀 Proyectos Destacados

<table>
<tr>
<td width="50%" valign="top">

### 🎬 yt-summarizer
Resumidor de videos de YouTube con IA — serverless end-to-end en AWS.
Pegás una URL, elegís el idioma, y Claude AI devuelve un resumen estructurado con puntos clave, tópicos y tipo de contenido. Resultados cacheados en DynamoDB.

**Destacado:**
- AWS Bedrock (Claude 3.5 Haiku) via Converse API
- Lambda + API Gateway + DynamoDB + S3 + CloudFront
- Extracción de transcript via Supadata API (browser-side)
- Selector de idioma (ES, EN, PT y más)
- CloudWatch Dashboard + Alarms como código
- GitHub Actions CI/CD: deploy automático en push
- 100% Terraform IaC ✅

`Python` `AWS Bedrock` `Lambda` `DynamoDB` `CloudFront` `Terraform` `GitHub Actions`

[![CI Frontend](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-frontend.yml/badge.svg)](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-frontend.yml)
[![CI Backend](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-backend.yml/badge.svg)](https://github.com/EmmaLedesma/youtube-summarizer/actions/workflows/deploy-backend.yml)
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://d21n43yg7hlxxz.cloudfront.net)

🔗 [Demo en vivo](https://d21n43yg7hlxxz.cloudfront.net) · [Repo](https://github.com/EmmaLedesma/youtube-summarizer)

</td>
<td width="50%" valign="top">

### 🏗️ terraform-event-pipeline
Infraestructura event-driven en AWS provisionada 100% con Terraform.
La subida de un archivo a S3 dispara una Lambda que distribuye el evento a SQS y SNS — destruida y recreada desde cero con un solo comando.

**Destacado:**
- Módulos Terraform: storage, messaging, compute
- Estado remoto: S3 backend + DynamoDB locking
- GitHub Actions CI/CD: plan en PR, apply en merge
- 11 recursos AWS provisionados como código ✅

`Terraform` `AWS Lambda` `S3` `SQS` `SNS` `IAM` `GitHub Actions`

[![Terraform Apply](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-apply.yml/badge.svg)](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-apply.yml)
[![Terraform Plan](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-plan.yml/badge.svg)](https://github.com/EmmaLedesma/terraform-event-pipeline/actions/workflows/terraform-plan.yml)

🔗 [Repo](https://github.com/EmmaLedesma/terraform-event-pipeline)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ cloud-file-api
REST API containerizada con pipeline CI/CD completo hacia AWS ECS Fargate.
Gestiona archivos en S3 con build, test y deploy automatizados en cada cambio.

**Destacado:**
- Docker multi-stage build
- GitHub Actions CI (lint + test matrix Node 18/20)
- GitHub Actions CD → ECR + ECS Fargate
- Autenticación AWS keyless via OIDC (sin credenciales almacenadas)
- LocalStack para desarrollo local sin costo
- Deployado y funcionando ✅

`Node.js` `Docker` `GitHub Actions` `AWS ECS` `ECR` `S3` `OIDC`

[![CI](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/ci.yml/badge.svg)](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/ci.yml)
[![CD](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/cd.yml/badge.svg)](https://github.com/EmmaLedesma/cloud-file-api/actions/workflows/cd.yml)

🔗 [API](http://3.84.95.162:3000/health) · [Repo](https://github.com/EmmaLedesma/cloud-file-api)

</td>
<td width="50%" valign="top">

### 🔮 Shem 72 – Calculadora de Ángeles
App serverless full-stack deployada en AWS.
Calcula 3 ángeles guardianes usando el método cabalístico.

**Destacado:**
- AWS Lambda + API Gateway + S3
- SAM / CloudFormation (IaC)
- REST API propia en Node.js/Express
- Deployada y funcionando ✅

`Node.js` `AWS Lambda` `S3` `SAM` `REST API`

🔗 [App en vivo](http://shem72-app.s3-website-us-east-1.amazonaws.com) · [Repo](https://github.com/EmmaLedesma/calculadora-72-nombres)

</td>
</tr>
</table>

---

## 🛠️ Stack Tecnológico

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![ECS](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![ECR](https://img.shields.io/badge/ECR-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![LocalStack](https://img.shields.io/badge/LocalStack-000000?style=flat-square&logo=localstack&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F00?style=flat-square&logo=amazon-aws&logoColor=white)

**Lenguajes**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Herramientas**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 📚 Roadmap de Aprendizaje

| Skill | Estado | Proyecto |
|---|---|---|
| Docker + docker-compose | ✅ Completado | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| GitHub Actions CI/CD | ✅ Completado | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| AWS ECS Fargate + ECR | ✅ Completado | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| Terraform IaC | ✅ Completado | [terraform-event-pipeline](https://github.com/EmmaLedesma/terraform-event-pipeline) |
| AWS Bedrock + IA Generativa | ✅ Completado | [yt-summarizer](https://github.com/EmmaLedesma/youtube-summarizer) |
| Terraform avanzado (VPC + EC2 + RDS) | 🔨 Próximo | `terraform-aws-infra` |
| Kubernetes (EKS) | 📋 Planificado | `eks-labs` |
| GCP fundamentals | 📋 Planificado | `gcp-labs` |
| Multi-cloud (AWS + GCP) | 📋 Planificado | `multicloud-pipeline` |

---

## 🎓 Trayectoria

- 💼 **IBM** — 10+ años · Educación IT, Transformación Digital · LATAM
- 🏫 **IFTS N°18** — Técnico Superior en Análisis de Sistemas (TSAS)
- 🏫 **Universidad de la Ciudad de Buenos Aires** — Licenciatura en Tecnologías Digitales · Articulando
- 📍 Buenos Aires, Argentina

🔗 [LinkedIn](https://www.linkedin.com/in/emmanuel-ledesmam)
