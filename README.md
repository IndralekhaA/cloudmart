# 🛒 CloudMart – AI-Powered, Multi-Cloud E-Commerce Transformation

**CloudMart** is a full-stack modernization project that transitions a traditional retail company into a scalable, AI-powered e-commerce platform hosted on the cloud. This project demonstrates multi-cloud deployment, intelligent automation, and real-time customer experience enhancements using modern DevOps, AI, and ML technologies.

---

## 🌟 Project Highlights

- 🚀 **Modernized Architecture**: Migrated legacy retail systems to a cloud-native microservices architecture.
- ☁️ **Multi-Cloud Deployment**: Deployed services across **AWS**, **Azure**, and **Google Cloud Platform (GCP)** for resilience and cost efficiency.
- 🤖 **AI & ML Integration**:
  - ChatGPT for smart customer support and product recommendation.
  - Azure ML for demand forecasting and personalized marketing.
- ⚙️ **CI/CD & Automation**: Used **AWS CodeBuild**, **Docker**, **Kubernetes**, and **Terraform** for infrastructure provisioning and seamless deployment pipelines.
- 🛍️ **Frontend Experience**: Built a responsive, fast-loading UI using **Vite** and **Tailwind CSS**, deployed via Kubernetes.

---


## 📂 Project Structure

```bash
.
├── src/                          # Frontend source code
├── public/                       # Static assets
├── cloudmart-frontend.yaml      # Kubernetes deployment for frontend
├── Dockerfile                   # Container configuration
├── .env                         # Environment variables
├── package.json                 # Project metadata and dependencies
├── tailwind.config.js           # Tailwind CSS configuration
├── vite.config.js               # Vite bundler configuration
└── ...

```
---

## 🧰 Tech Stack

### ☁️ Cloud & DevOps
- **AWS** – EC2, S3, CodeBuild, IAM
- **Azure** – Azure Machine Learning, App Services
- **GCP** – Compute Engine, Cloud Run
- **Docker** – Containerization
- **Kubernetes** – Orchestration
- **Terraform** – Infrastructure as Code

### 🧠 AI/ML
- **ChatGPT (OpenAI)** – Conversational AI integration
- **Azure ML** – Forecasting models for demand and sales

### 💻 Frontend
- **Vite**, **React**, **JavaScript**
- **Tailwind CSS**
- **PostCSS**, **ESLint**

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cloudmart.git
cd cloudmart
```
## Install Dependencies
```bash
npm install
```

## Create .env File
```bash
VITE_API_URL=https://your-api-endpoint
VITE_CHATGPT_API_KEY=your_chatgpt_api_key
# Add other relevant secrets
```
## Run the App Locally
```bash
npm run dev
```
## 🐳 Docker Instructions
### Build Image
```bash
docker build -t cloudmart-frontend .
```
### Run Container
```bash
docker run -p 3000:3000 cloudmart-frontend
```
## ☸️ Kubernetes Deployment
Ensure your kubectl context is set to the correct cluster:
```bash
kubectl apply -f cloudmart-frontend.yaml
```
## 🤖 AI Integration
ChatGPT: Connected to the frontend via secure API for real-time product Q&A and recommendation.

Azure Machine Learning: Models trained for inventory optimization and customer behavior analysis.

## 📸 Screenshots
![BedrockAI](https://github.com/user-attachments/assets/540de2c7-ef4c-432f-990b-6453af1c8e65)

## 📊 Features
🔍 AI-powered search and recommendations

🧠 Predictive analytics for demand forecasting

☁️ Deployed on multi-cloud environment

⚙️ Fully automated CI/CD pipeline

📱 Mobile-first responsive design

## 👤 Author
CloudMart AI Retail Transformation
Created by: EC2 Default User
📧[indrarwork888@gmail.com]

## 📄 License
This project is licensed under the MIT License.

## 🙏 Acknowledgments
OpenAI – for ChatGPT API

Microsoft Azure – for ML Services

Amazon Web Services – for infrastructure and automation

Google Cloud Platform – for scalable compute.

