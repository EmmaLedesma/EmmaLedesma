<div align="center">
# Emmanuel Ledesma
### Cloud Engineering · DevOps · Applied AI — Buenos Aires, Argentina
#### Transitioning from 10+ years in IBM → Building in public
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emmanuel_Ledesma-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-ledesmam)
[![GitHub](https://img.shields.io/badge/GitHub-EmmaLedesma-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EmmaLedesma)
 
🇬🇧 English · [🇦🇷 Español](#es)
 
</div>
---
 
## 👨‍💻 About Me
 
I'm a tech professional with 10+ years of IBM experience in IT education, digital transformation and technology adoption across Latin America — currently transitioning into Cloud Engineering and DevOps by building real projects from scratch.
 
I don't just list skills. I build projects that prove them.
 
🎯 **Focus:** Cloud Engineering · DevOps · Applied AI
 
- 🌩️ Provisioning **AWS and GCP infrastructure as code** with Terraform
- 🐳 Containerizing applications with **Docker** and automating deploys with **GitHub Actions CI/CD**
- ⚡ Building **event-driven pipelines** on AWS (Lambda, S3, SQS, SNS) and GCP (Pub/Sub, Cloud Functions)
- 🚀 Deploying **serverless and containerized apps** on AWS (Lambda, ECS Fargate) and GCP (Cloud Run)
- 🤖 Integrating **Generative AI** via AWS Bedrock (Claude) and GCP Vertex AI (Gemini), including RAG over real documents
- 🐍 Writing **Python** for ETL pipelines, automation and backend logic
- 🗄️ Designing **SQL databases** from scratch and writing complex queries
- 🌐 Developing **REST APIs** and full-stack web applications
- 📦 Emulating cloud environments locally with **LocalStack + Docker**
- 📊 Turning data into decisions with **Power BI, DAX and Python** (pandas, Streamlit) — tested like software
---
 
## 🚀 Featured Projects
 
### 🤖 AI on Cloud
 
<table>
<tr>
<td width="50%" valign="top">
#### 🤖 cloud-portfolio-agent
Conversational AI agent deployed on GCP that answers questions about my professional profile using RAG over real portfolio documents.
 
**Highlights:**
- Vertex AI Search (RAG) + Gemini 2.5 Flash
- Cloud Run (Python/FastAPI) + Cloud Functions
- Pub/Sub event-driven document ingestion
- BigQuery conversation analytics
- Workload Identity Federation (keyless CI/CD)
- 100% Terraform IaC — modular ✅
`Python` `GCP` `Vertex AI` `Gemini` `Cloud Run` `Terraform` `GitHub Actions`
 
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://emmaledesma.github.io/cloud-portfolio-agent/)
 
🔗 [Live Demo](https://emmaledesma.github.io/cloud-portfolio-agent/) · [Repo](https://github.com/EmmaLedesma/cloud-portfolio-agent)
 
</td>
<td width="50%" valign="top">
#### 🎬 yt-summarizer
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
</tr>
</table>
### ⚙️ DevOps & Infrastructure
 
<table>
<tr>
<td width="50%" valign="top">
#### 🏗️ terraform-event-pipeline
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
<td width="50%" valign="top">
#### ☁️ cloud-file-api
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
</tr>
<tr>
<td width="50%" valign="top">
#### 🐾 refugia
Operations platform for animal shelters in Buenos Aires — the back-office layer the official city platform doesn't cover. Clinical history per animal, photo uploads and a rule-based adoption-matching engine with an explainable compatibility score. Built end-to-end on AWS, then deliberately **closed** after a real FinOps lesson.
 
**Highlights:**
- Node.js / Express + Sequelize on PostgreSQL (RDS), 8 versioned migrations
- Explainable adoption matching (0–100 score) validated against real data
- Photo upload via S3 presigned URLs (browser → S3 direct)
- Elastic Beanstalk + RDS + S3 + CloudFront + SSM — 100% Terraform IaC ✅
- GitHub Actions CI/CD with keyless OIDC auth
- IAM least-privilege hardening + 8 ADRs, including a real cost incident
- FinOps: Zero-Spend Budget after finding orphaned resources
`Node.js` `Express` `PostgreSQL` `AWS` `Terraform` `GitHub Actions` `S3` `CloudFront`
 
[![Status](https://img.shields.io/badge/status-completed_and_closed-success)](https://github.com/EmmaLedesma/refugia)
[![FinOps](https://img.shields.io/badge/FinOps-zero--spend_budget-blue)](https://github.com/EmmaLedesma/refugia#-cierre-del-proyecto)
 
🔗 [Repo](https://github.com/EmmaLedesma/refugia) · [Architecture decisions (ADRs)](https://github.com/EmmaLedesma/refugia/tree/main/docs/adr)
 
</td>
<td width="50%" valign="top">
#### 🐧 Ubuntu Enterprise Workload Lab
Design and build a professional, reproducible infrastructure lab using Canonical technologies.
 
**Planned scope:**
- Ubuntu Server LTS virtual machines provisioned with Multipass
- Web tier with NGINX hardened with UFW
- Operations node with diagnostic scripts
- Zero-cost, fully local and reproducible
- Built incrementally, documented step by step
`Ubuntu Server` `Multipass` `NGINX` `UFW` `Shell`
 
[![Status](https://img.shields.io/badge/status-coming_soon-orange)](https://github.com/EmmaLedesma)
 
🔜 Coming soon
 
</td>
</tr>
</table>
### 📊 Data & BI
 
<table>
<tr>
<td width="50%" valign="top">
#### 💳 digital-payments-intelligence-bi
BI dashboard on digital payments and financial inclusion in Argentina, built on open data from the Central Bank (BCRA). Power BI star schema + DAX, replicated in Python/Streamlit with tests that verify every figure in the report. Team project (6 people) — my role: **Data Engineer**.
 
**Highlights:**
- Power BI star schema (5 fact tables) + DAX measures, 5-page dashboard
- Python/Streamlit replica reading the model exported as CSV + DAX in plain text
- 23 pytest tests reproduce each published figure — GitHub Actions CI
- From descriptive findings to testable product hypotheses
`Power BI` `DAX` `Power Query` `Python` `pandas` `Streamlit` `Plotly` `pytest` `GitHub Actions`
 
[![CI](https://github.com/EmmaLedesma/digital-payments-intelligence-bi/actions/workflows/ci.yml/badge.svg)](https://github.com/EmmaLedesma/digital-payments-intelligence-bi/actions)
 
🔗 [Repo](https://github.com/EmmaLedesma/digital-payments-intelligence-bi)
 
</td>
<td width="50%" valign="top">
</td>
</tr>
</table>
---
 
## 🛠️ Tech Stack
 
**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![ECS](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![LocalStack](https://img.shields.io/badge/LocalStack-000000?style=flat-square&logo=localstack&logoColor=white)
 
**AI**
![Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
 
**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
 
**Data & BI**
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
 
**Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
 
---
 
## 📚 Learning Roadmap
 
Status: ✅ Completed · 🔨 In progress · 🔜 Next · 📋 Planned
 
| Track | Skill | Status | Project |
|---|---|---|---|
| ☁️ Cloud | AWS ECS Fargate + ECR | ✅ Completed | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| ☁️ Cloud | Serverless & event-driven on AWS | ✅ Completed | [terraform-event-pipeline](https://github.com/EmmaLedesma/terraform-event-pipeline) |
| ☁️ Cloud | GCP (Cloud Run, Pub/Sub, BigQuery) | ✅ Completed | [cloud-portfolio-agent](https://github.com/EmmaLedesma/cloud-portfolio-agent) |
| ⚙️ DevOps | Docker + docker-compose | ✅ Completed | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| ⚙️ DevOps | GitHub Actions CI/CD (keyless OIDC) | ✅ Completed | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| ⚙️ DevOps | Terraform IaC + FinOps | ✅ Completed | [terraform-event-pipeline](https://github.com/EmmaLedesma/terraform-event-pipeline) · [refugia](https://github.com/EmmaLedesma/refugia) |
| 🤖 AI | AWS Bedrock + Generative AI | ✅ Completed | [yt-summarizer](https://github.com/EmmaLedesma/youtube-summarizer) |
| 🤖 AI | GCP Vertex AI + Gemini + RAG | ✅ Completed | [cloud-portfolio-agent](https://github.com/EmmaLedesma/cloud-portfolio-agent) |
| 📊 Data | Power BI, DAX, Python/Streamlit | ✅ Completed | [digital-payments-intelligence-bi](https://github.com/EmmaLedesma/digital-payments-intelligence-bi) |
| 🐧 Linux | Ubuntu Server, Multipass, NGINX, UFW | 🔨 In progress | `Ubuntu Enterprise Workload Lab` — coming soon |
| ☁️ Cloud | Azure fundamentals | 🔜 Next | `azure-labs` |
| ⚙️ DevOps | Kubernetes (EKS / GKE) | 📋 Planned | `kubernetes-labs` |
| ⚙️ DevOps | Jenkins CI/CD | 📋 Planned | `jenkins-pipeline` |
| ☁️ Cloud | IBM Cloud | 📋 Planned | `ibm-cloud-labs` |
| ☁️ Cloud | Multi-cloud (AWS + GCP + Azure) | 📋 Planned | `multicloud-pipeline` |
 
---
 
## 🎓 Background
 
- 💼 **IBM** — 10+ years · IT Education, Digital Transformation, Tech Adoption · LATAM
- 🏫 **IFTS N°18** — Técnico Superior en Análisis de Sistemas (TSAS)
- 🏫 **Universidad de la Ciudad de Buenos Aires** — Licenciatura en Tecnologías Digitales · Articulando
- 🏫 **Universidad de Buenos Aires** — Ingeniería en Informatica · En Curso
- 📍 Buenos Aires, Argentina
---
 
<a id="es"></a>
 
<div align="center">
# Emmanuel Ledesma
### Cloud Engineering · DevOps · IA Aplicada — Buenos Aires, Argentina
#### Transitioning from 10+ years in IBM → Building in public
 
[🇬🇧 English](#) · 🇦🇷 Español
 
</div>
---
 
## 👨‍💻 Sobre mí
 
Soy un profesional técnico con 10+ años de experiencia en IBM en educación IT, transformación digital y adopción tecnológica en América Latina — actualmente en transición hacia Cloud Engineering y DevOps construyendo proyectos reales desde cero.
 
No listo habilidades sin respaldo. Construyo proyectos que las demuestran.
 
🎯 **Foco:** Cloud Engineering · DevOps · IA Aplicada
 
- 🌩️ Provisionando **infraestructura AWS y GCP como código** con Terraform
- 🐳 Containerizando aplicaciones con **Docker** y automatizando deploys con **GitHub Actions CI/CD**
- ⚡ Construyendo **pipelines event-driven** en AWS (Lambda, S3, SQS, SNS) y GCP (Pub/Sub, Cloud Functions)
- 🚀 Deployando **apps serverless y containerizadas** en AWS (Lambda, ECS Fargate) y GCP (Cloud Run)
- 🤖 Integrando **IA Generativa** via AWS Bedrock (Claude) y GCP Vertex AI (Gemini), incluyendo RAG sobre documentos reales
- 🐍 Escribiendo **Python** para ETL, automatización y lógica backend
- 🗄️ Diseñando **bases de datos SQL** y consultas complejas
- 🌐 Desarrollando **REST APIs** y aplicaciones web full-stack
- 📦 Emulando entornos cloud locales con **LocalStack + Docker**
- 📊 Convirtiendo datos en decisiones con **Power BI, DAX y Python** (pandas, Streamlit) — testeado como software
---
 
## 🚀 Proyectos Destacados
 
### 🤖 IA en la Nube
 
<table>
<tr>
<td width="50%" valign="top">
#### 🤖 cloud-portfolio-agent
Agente conversacional deployado en GCP que responde preguntas sobre mi perfil profesional usando RAG sobre documentos reales del portfolio.
 
**Destacado:**
- Vertex AI Search (RAG) + Gemini 2.5 Flash
- Cloud Run (Python/FastAPI) + Cloud Functions
- Ingesta de documentos event-driven via Pub/Sub
- Analytics de conversaciones en BigQuery
- Workload Identity Federation (CI/CD keyless)
- 100% Terraform IaC — modular ✅
`Python` `GCP` `Vertex AI` `Gemini` `Cloud Run` `Terraform` `GitHub Actions`
 
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://emmaledesma.github.io/cloud-portfolio-agent/)
 
🔗 [Demo en vivo](https://emmaledesma.github.io/cloud-portfolio-agent/) · [Repo](https://github.com/EmmaLedesma/cloud-portfolio-agent)
 
</td>
<td width="50%" valign="top">
#### 🎬 yt-summarizer
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
</tr>
</table>
### ⚙️ DevOps e Infraestructura
 
<table>
<tr>
<td width="50%" valign="top">
#### 🏗️ terraform-event-pipeline
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
<td width="50%" valign="top">
#### ☁️ cloud-file-api
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
</tr>
<tr>
<td width="50%" valign="top">
#### 🐾 refugia
Plataforma de gestión operativa para refugios de animales en CABA — la capa de back-office que la plataforma oficial de la Ciudad no cubre. Historia clínica por animal, subida de fotos y un motor de matching de adopción por reglas con score de compatibilidad explicable. Construido de punta a punta en AWS y luego **cerrado** a conciencia tras una lección real de FinOps.
 
**Destacado:**
- Node.js / Express + Sequelize sobre PostgreSQL (RDS), 8 migraciones versionadas
- Matching de adopción explicable (score 0–100) validado con datos reales
- Upload de fotos vía URLs presignadas de S3 (navegador → S3 directo)
- Elastic Beanstalk + RDS + S3 + CloudFront + SSM — 100% Terraform IaC ✅
- CI/CD con GitHub Actions y autenticación keyless vía OIDC
- Hardening IAM de mínimo privilegio + 8 ADRs, incluido un incidente real de costos
- FinOps: Zero-Spend Budget tras detectar recursos huérfanos
`Node.js` `Express` `PostgreSQL` `AWS` `Terraform` `GitHub Actions` `S3` `CloudFront`
 
[![Status](https://img.shields.io/badge/status-completo_y_cerrado-success)](https://github.com/EmmaLedesma/refugia)
[![FinOps](https://img.shields.io/badge/FinOps-zero--spend_budget-blue)](https://github.com/EmmaLedesma/refugia#-cierre-del-proyecto)
 
🔗 [Repo](https://github.com/EmmaLedesma/refugia) · [Decisiones de arquitectura (ADRs)](https://github.com/EmmaLedesma/refugia/tree/main/docs/adr)
 
</td>
<td width="50%" valign="top">
#### 🐧 Ubuntu Enterprise Workload Lab
Diseño y construcción de un laboratorio de infraestructura profesional y reproducible con tecnologías de Canonical.
 
**Alcance previsto:**
- Máquinas virtuales Ubuntu Server LTS aprovisionadas con Multipass
- Capa web con NGINX securizado con UFW
- Nodo de operaciones con scripts de diagnóstico
- Costo cero, 100% local y reproducible
- Construido de forma incremental y documentado paso a paso
`Ubuntu Server` `Multipass` `NGINX` `UFW` `Shell`
 
[![Status](https://img.shields.io/badge/status-próximamente-orange)](https://github.com/EmmaLedesma)
 
🔜 Próximamente
 
</td>
</tr>
</table>
### 📊 Datos y BI
 
<table>
<tr>
<td width="50%" valign="top">
#### 💳 digital-payments-intelligence-bi
Dashboard de BI sobre pagos digitales e inclusión financiera en Argentina, con datos abiertos del BCRA. Modelo estrella en Power BI + DAX, replicado en Python/Streamlit con tests que verifican cada cifra del informe. Proyecto en equipo (6 personas) — mi rol: **Data Engineer**.
 
**Destacado:**
- Modelo estrella en Power BI (5 tablas de hechos) + medidas DAX, dashboard de 5 páginas
- Réplica en Python/Streamlit sobre el modelo exportado a CSV + DAX en texto plano
- 23 tests con pytest reproducen cada cifra publicada — CI con GitHub Actions
- De hallazgos descriptivos a hipótesis de producto testeables
`Power BI` `DAX` `Power Query` `Python` `pandas` `Streamlit` `Plotly` `pytest` `GitHub Actions`
 
[![CI](https://github.com/EmmaLedesma/digital-payments-intelligence-bi/actions/workflows/ci.yml/badge.svg)](https://github.com/EmmaLedesma/digital-payments-intelligence-bi/actions)
 
🔗 [Repo](https://github.com/EmmaLedesma/digital-payments-intelligence-bi)
 
</td>
<td width="50%" valign="top">
</td>
</tr>
</table>
---
 
## 🛠️ Stack Tecnológico
 
**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![ECS](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![LocalStack](https://img.shields.io/badge/LocalStack-000000?style=flat-square&logo=localstack&logoColor=white)
 
**IA**
![Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
 
**Lenguajes**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
 
**Datos & BI**
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
 
**Herramientas**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
 
---
 
## 📚 Roadmap de Aprendizaje
 
Estado: ✅ Completado · 🔨 En progreso · 🔜 Próximo · 📋 Planificado
 
| Track | Skill | Estado | Proyecto |
|---|---|---|---|
| ☁️ Cloud | AWS ECS Fargate + ECR | ✅ Completado | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| ☁️ Cloud | Serverless y event-driven en AWS | ✅ Completado | [terraform-event-pipeline](https://github.com/EmmaLedesma/terraform-event-pipeline) |
| ☁️ Cloud | GCP (Cloud Run, Pub/Sub, BigQuery) | ✅ Completado | [cloud-portfolio-agent](https://github.com/EmmaLedesma/cloud-portfolio-agent) |
| ⚙️ DevOps | Docker + docker-compose | ✅ Completado | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| ⚙️ DevOps | GitHub Actions CI/CD (OIDC keyless) | ✅ Completado | [cloud-file-api](https://github.com/EmmaLedesma/cloud-file-api) |
| ⚙️ DevOps | Terraform IaC + FinOps | ✅ Completado | [terraform-event-pipeline](https://github.com/EmmaLedesma/terraform-event-pipeline) · [refugia](https://github.com/EmmaLedesma/refugia) |
| 🤖 IA | AWS Bedrock + IA Generativa | ✅ Completado | [yt-summarizer](https://github.com/EmmaLedesma/youtube-summarizer) |
| 🤖 IA | GCP Vertex AI + Gemini + RAG | ✅ Completado | [cloud-portfolio-agent](https://github.com/EmmaLedesma/cloud-portfolio-agent) |
| 📊 Datos | Power BI, DAX, Python/Streamlit | ✅ Completado | [digital-payments-intelligence-bi](https://github.com/EmmaLedesma/digital-payments-intelligence-bi) |
| 🐧 Linux | Ubuntu Server, Multipass, NGINX, UFW | 🔨 En progreso | `Ubuntu Enterprise Workload Lab` — próximamente |
| ☁️ Cloud | Azure fundamentals | 🔜 Próximo | `azure-labs` |
| ⚙️ DevOps | Kubernetes (EKS / GKE) | 📋 Planificado | `kubernetes-labs` |
| ⚙️ DevOps | Jenkins CI/CD | 📋 Planificado | `jenkins-pipeline` |
| ☁️ Cloud | IBM Cloud | 📋 Planificado | `ibm-cloud-labs` |
| ☁️ Cloud | Multi-cloud (AWS + GCP + Azure) | 📋 Planificado | `multicloud-pipeline` |
 
---
 
## 🎓 Trayectoria
 
- 💼 **IBM** — 10+ años · Educación IT, Transformación Digital · LATAM
- 🏫 **IFTS N°18** — Técnico Superior en Análisis de Sistemas (TSAS)
- 🏫 **Universidad de la Ciudad de Buenos Aires** — Licenciatura en Tecnologías Digitales · Articulando
- 🏫 **Universidad de Buenos Aires** — Ingeniería en Informatica · En curso
- 📍 Buenos Aires, Argentina
🔗 [LinkedIn](https://www.linkedin.com/in/emmanuel-ledesmam)
 
