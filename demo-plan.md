# Demo Plan for Multi-Cloud Interoperability

## Step 1: Launch Frontend on AWS
- Start EC2 Ubuntu instance
- Host React app
- Access via public IP

## Step 2: Launch Backend on Azure
- Start Azure VM
- Run Node.js API (GET /health, POST /data)
- Open firewall ports (3000)

## Step 3: Test API from AWS Frontend
- React app sends request to Azure backend
- Use browser/Postman to validate

## Step 4: Show Logs or Console
- Show API logs on Azure VM
- Show frontend console on AWS

## Optional:
- Record a short video
- Upload to GitHub or YouTube
