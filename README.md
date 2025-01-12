# React App with AWS Amplify (Gen 1), Cognito, and CI/CD
This project is a web application built with React.js, AWS Amplify (Gen 1), and Cognito for authentication. It also includes CI/CD integration with GitHub for seamless deployment and updates.

---

# Features
## Frontend (React.js)
- **User Authentication:** Fully integrated with AWS Cognito to provide secure sign-up, sign-in, and multi-factor authentication.
- **Amplify Integration:** Uses Amplify libraries for seamless communication with backend services.
- **Responsive Design:** Built with modern React practices and responsive UI.

## AWS Amplify (Gen 1)
- **Hosting:** Configured with Amplify for hosting the React application.
- **Backend Integration:** Amplify seamlessly connects the frontend with AWS services like Cognito.

## CI/CD Pipeline (GitHub)
- Automated deployment pipeline set up with GitHub Actions.
- Every commit triggers a build and deploy process to ensure the latest code is live.

---

# Architecture Overview
1. **Frontend:** React.js application.
2. **Authentication:** AWS Cognito for managing users and sessions.
3. **CI/CD:** GitHub Actions for automating deployment to Amplify.

---

# Getting Started

## Prerequisites
- Node.js and npm installed on your machine.
- AWS account with Amplify and Cognito configured.
- GitHub repository for CI/CD integration.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/aws-react-app.git
   cd aws-react-app
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up AWS Amplify:**
   Initialize Amplify in your project directory:
   ```bash
   amplify init
   ```

   Follow the prompts to connect your app to AWS services.

4. **Add Cognito Authentication:**
   ```bash
   amplify add auth
   ```
   Configure the authentication as per your requirements (e.g., email and password).

5. **Push Changes to AWS:**
   Deploy the backend services:
   ```bash
   amplify push
   ```

## Running Locally

1. **Start the Development Server:**
   ```bash
   npm start
   ```

2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

---

# Usage
- Sign up or log in using the authentication flow.
- Explore the application's features.
- CI/CD ensures that any updates to the codebase are automatically deployed.

---

# Images to Attach
1. **Architecture Diagram:** 
-
![image](https://github.com/user-attachments/assets/fe3c6b91-6ac8-49cc-a663-81bc8767482c)

2. **Quiz App!!:**
   - Sign-up and login screens.
![image](https://github.com/user-attachments/assets/7d142c04-9a27-4188-a6ea-85ab16cfe563)
![image](https://github.com/user-attachments/assets/d62cccd8-e8c2-4727-ac3a-ecf4f5f22684)
   - Amplify console showing CI/CD pipeline.
![image](https://github.com/user-attachments/assets/6c6492db-6e18-4b14-9cbc-82d2ec11585b)
   - Quiz Screen
![image](https://github.com/user-attachments/assets/ed14578a-bddb-4d22-9521-352b96038358)
![image](https://github.com/user-attachments/assets/0308ea36-3c4f-4e8e-8aeb-4a45d639030c)

---

# Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your enhancements.
