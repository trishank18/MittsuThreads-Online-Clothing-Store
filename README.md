# 📌 Project Setup Guide

## 📦 Prerequisites
- **Node.js** (Skip if already installed)  
  1. Visit [Node.js Official Website](https://nodejs.org/en/download/)  
  2. Download the Node.js installer.  
  3. Run the installer and follow the prompts.  

---

## ⚙️ Project Setup Steps

### 1️⃣ Install Dependencies
- **Open Project in VS Code**
- **Backend:**  
  Right-click on the `backend` folder → **Open in Integrated Terminal**  
  ```bash
  npm install
Frontend:
Right-click on the frontend folder → Open in Integrated Terminal

bash
Copy
Edit
npm install
Admin Panel:
Right-click on the admin folder → Open in Integrated Terminal

bash
Copy
Edit
npm install
2️⃣ Configure Environment Variables (backend/.env)
env
Copy
Edit
# Cloudinary Configuration
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

# MongoDB Configuration
MONGODB_URI=your_mongodb_connection_string

# Payment Gateway Keys (Optional)
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_SECRET_KEY=your_razorpay_secret_key
3️⃣ Setup Cloudinary (File Storage)
Create an account at Cloudinary.

Go to Dashboard and copy:

Cloud Name

API Key

API Secret Key

Paste them into backend/.env.

4️⃣ Setup MongoDB (Database)
Go to MongoDB and sign up / log in.

Create a New Project.

Go to Database → Build a Database.

Choose M0, select your Region, and create.

Create Username & Password (Avoid @ in password).

Whitelist IP: 0.0.0.0 → Add Entry.

Click Connect → Choose Compass option → Copy connection string.

Replace <password> in the string with your password.

Paste into backend/.env as:

env
Copy
Edit
MONGODB_URI=your_connection_string
Note: Do not add / at the end.

5️⃣ Payment Gateway Setup (Optional)
Stripe:

Create an account at Stripe.

Get your Secret Key from dashboard → Paste into .env.

Razorpay:

Create an account at Razorpay.

Copy Key ID and Secret Key → Paste into .env.

6️⃣ Run the Project
Start Backend
bash
Copy
Edit
cd backend
npm run server
Keep the backend running.

Start Frontend
bash
Copy
Edit
cd frontend
npm run dev
Open browser → http://localhost:5173

Start Admin Panel
bash
Copy
Edit
cd admin
npm run dev
Open browser → http://localhost:5174

✅ Your project is now fully set up and running!

yaml
Copy
Edit

---

This keeps **everything in one continuous flow** instead of splitting them into separate long blocks.  

If you want, I can now **add a visual architecture diagram** that shows **Backend ↔ Frontend ↔ Admin Panel** with MongoDB, Cloudinary, Stripe, and Razorpay connections — so your GitHub looks next-level. That would make this README shine.








Ask ChatGPT
