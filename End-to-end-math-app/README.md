# End-to-End Math Web App

Serverless on AWS | API-Driven | Cloud-Native

🚀 Overview

A fully serverless web app that calculates baseⁿ (base raised to exponent) using AWS-managed services.
The frontend sends user input to a REST API, and the backend computes and returns results in real time.

Built to demonstrate cloud architecture, serverless computing, and secure AWS integration.

# 🏗️ Architecture
User
 ↓
AWS Amplify (Frontend)
 ↓
API Gateway (REST API)
 ↓
AWS Lambda (Compute)
 ↓
DynamoDB (Optional Storage)

# ⚙️ Tech Stack

Frontend: HTML, JavaScript, AWS Amplify

Backend: AWS Lambda (Python)

API: Amazon API Gateway (REST)

Database: DynamoDB (Optional)

Security: IAM, CORS

# ✨ Features

Real-time baseⁿ calculation

Fully serverless & scalable

Secure API with IAM roles


# 🛠️ How It Works

User enters base & exponent in the web UI

Frontend calls API Gateway endpoint

Lambda computes result

Response is returned as JSON

(Optional) Result stored in DynamoDB

Sample Response:

{
  "base": 2,
  "exponent": 3,
  "result": 8
}

# 🔐 Security

IAM-based permissions for service access

CORS enabled for controlled frontend communication

No public backend exposure

# 🌱 Future Enhancements

User login with Amazon Cognito

Display history from DynamoDB

Support advanced math functions

React frontend with Amplify Hosting

# 🧠 Skills Demonstrated

-Serverless Architecture Design

-REST API Development

-Cloud Security (IAM, CORS)

-Full-Stack AWS Deployment

