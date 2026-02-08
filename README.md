# KantinYuk Application

## Introduction
KantinYuk is a web application designed to make dining more convenient by allowing users to order food from their favorite restaurants.

## Prerequisites
- Node.js version X.X.X
- NPM version X.X.X
- A Render.com account setup.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/TROJANVIRUS-BLACKHAT/KantinYuk.git
   cd KantinYuk
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Create a .env file**:
   Create a `.env` file in the root directory of the project and add the necessary environment variables.
   ```bash
   PORT=3000
   DATABASE_URL=[YourDatabaseURL]
   API_KEY=[YourAPIKey]
   ```

4. **Run the Application Locally**:
   ```bash
   npm start
   ```
   Application will be running at `http://localhost:3000`.

## Deployment Instructions on Render.com
1. **Create a New Web Service**:
   - Sign into your Render.com account.
   - Click on 'New' and select 'Web Service'.

2. **Connect to Your GitHub Repository**:
   - Choose your GitHub account and select the `KantinYuk` repository.

3. **Configure Build Settings**:
   - Set the **Build Command** as:
     ```bash
     npm install
     ```
   - Set the **Start Command** as:
     ```bash
     npm start
     ```

4. **Set Environment Variables**:
   - In Render, go to the 'Environment' section and add the same environment variables as in the .env file:
     - `PORT` (set to 3000)
     - `DATABASE_URL`
     - `API_KEY`

5. **Deploy the Service**:
   - Click on 'Create Web Service' to deploy.
   - Your application will automatically be built and deployed.

6. **Access the Application**:
   - After deployment, Render will provide a URL where your application is live.

## Conclusion
Now your KantinYuk application is set up and hosted on Render.com! Enjoy ordering food with ease!