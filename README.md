# 🚀 Next.js + AWS DynamoDB Contact Form

This is a mini full-stack project where a contact form built using Next.js stores user data in AWS DynamoDB.

## 📌 Project Overview

This project demonstrates how to:
- Build a frontend form using Next.js
- Handle API requests using server-side logic
- Integrate AWS DynamoDB for data storage
- Store user-submitted contact form data in a scalable NoSQL database

## 🛠️ Tech Stack

- Frontend: Next.js
- Backend: Next.js API Routes / AWS Lambda
- Database: AWS DynamoDB
- Cloud Services: AWS (IAM, DynamoDB)

## ⚙️ Features

- Simple contact form UI
- Form validation
- API integration
- Data stored in DynamoDB table
- Scalable and serverless architecture

## 📂 Project Structure


├── pages/
│ ├── index.js # Contact form UI
│ ├── api/ # API routes
│
├── components/ # Reusable components (if any)
├── utils/ # AWS config or helper functions
├── styles/ # CSS files
├── package.json


## 🔑 Environment Variables

Create a `.env.local` file in the root directory:


AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_REGION=your_region
DYNAMODB_TABLE_NAME=your_table_name


## 🚀 Getting Started

### 1. Clone the repository


git clone https://github.com/Yt-Anas/nextjs-aws-dynamodb-form.git

cd nextjs-aws-dynamodb-form


### 2. Install dependencies


npm install


### 3. Run the development server


npm run dev


Visit: http://localhost:3000

## ☁️ AWS Setup

### DynamoDB Table

- Create a DynamoDB table
- Set a primary key (e.g., `id`)
- Make sure your IAM user has permission to:
  - PutItem
  - GetItem

## 📬 API Workflow

1. User fills out the contact form
2. Form data is sent to Next.js API route
3. API processes the request
4. Data is stored in DynamoDB
5. Success response is returned


## ⚠️ Notes

- Never commit `.env.local` file
- Use IAM roles with minimal permissions
- Use validation before storing data

## 📄 License

This project is for learning purposes.
