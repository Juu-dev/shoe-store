# Project Setup

## Start Backend

### Step 1: Create PostgreSQL DB in Render Platform
1. Go to [Render](https://render.com/) and create a new PostgreSQL database.
2. Note down the database URL and credentials.

### Step 2: Update `.env` for Database and Strapi
1. Open the `.env` file in the root of your backend project.
2. Update the database connection details with the credentials from Step 1.
3. Update the Strapi-related environment variables.

### Step 3: Create Cloudinary Account
1. Go to [Cloudinary](https://cloudinary.com/) and create a new account.
2. Note down the Cloudinary cloud name, API key, and API secret.

### Step 4: Update `.env` for Cloudinary
1. Open the `.env` file.
2. Add or update the Cloudinary-related environment variables with the details from Step 3.

### Step 5: Install Dependencies
1. Run the following command to install all dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   npm i
   ```

### Step 6: Start Server
1. Start the development server with:
   ```bash
   npm run dev
   ```

### Step 7: Update Data
1. Update the data using the URL: [Google Sheets Data](https://docs.google.com/spreadsheets/d/1yY7Z7JRUG6-fC94TCFpfafaKboxfChsqeQJ8r-GMzvA/edit?gid=510065035#gid=510065035)

### Step 8: Create Payment with Stripe
1. Go to [Stripe](https://stripe.com/) and create an account.
2. Note down the API key.

### Step 9: Update `.env` with Stripe Key
1. Open the `.env` file.
2. Add or update the environment variable `STRIPE_KEY` with the API key from Step 8.

## Deploy Backend to Render

### Step 1: Create New Web Service
1. Go to [Render](https://render.com/) and create a new Web Service.
2. Connect your repository to Render.

### Step 2: Configure Environment Variables
1. In the Render dashboard, go to the "Environment" tab of your Web Service.
2. Add all the environment variables from your local `.env` file.

### Step 3: Deploy
1. Trigger a deploy from the Render dashboard.
2. Ensure the deployment logs show no errors and the service is running.

## Start Frontend

### Step 1: Create Token in Strapi (Settings)
1. Go to your Strapi admin panel.
2. Navigate to Settings and create a new API token.
3. Note down the token.

### Step 2: Update `.env`
1. Open the `.env` file in the root of your frontend project.
2. Add or update the environment variables with the details from Step 1.

### Step 3: Start Frontend
1. Start the frontend development server with:
   ```bash
   npm run dev
   ```

## Deploy Frontend to Vercel

### Step 1: Create New Project
1. Go to [Vercel](https://vercel.com/) and create a new project.
2. Connect your repository to Vercel.

### Step 2: Configure Environment Variables
1. In the Vercel dashboard, go to the "Settings" tab of your project.
2. Add all the environment variables from your local `.env` file.

### Step 3: Deploy
1. Trigger a deploy from the Vercel dashboard.
2. Ensure the deployment logs show no errors and the application is live.
