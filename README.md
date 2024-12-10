# 🍳 AI Recipe Generator  

**A serverless web application that generates creative recipes using generative AI.**  

This project combines the power of **React**, **AWS Amplify**, **Amazon Bedrock**, and **Lambda functions** to deliver a seamless and intuitive recipe creation experience.  

## 🔑 **Key Features**  
- **AI-Powered Recipe Suggestions:** Generate recipes based on user-provided ingredients using generative AI models.  
- **Serverless Architecture:** Built using AWS Amplify for deployment and backend services.  
- **Authentication:** Secure user login and registration with Amplify Auth.  
- **API Integration:** Backend API created with AWS Lambda to handle AI requests.  
- **Modern UI:** Styled React components for an engaging and user-friendly interface.  

## ⚙️ **Tech Stack**  
- **Frontend:** React.js  
- **Backend:** AWS Lambda  
- **AI Model Access:** Amazon Bedrock  
- **Deployment:** AWS Amplify  

## 🌟 **How It Works**  
1. Users input available ingredients.  
2. The app sends the input to a Lambda function via API.  
3. The Lambda function leverages Amazon Bedrock to access a generative AI model for recipe generation.  
4. Recipes are returned and displayed with a modern and easy-to-navigate UI.  

## 📂 **Project Structure**  
- `/src`: React components for the frontend  
- `/amplify`: Amplify backend setup and configuration  
- `/lambda`: AWS Lambda function code  

## 🚀 **Deployment**  
Easily deploy and scale the application with AWS Amplify.  
