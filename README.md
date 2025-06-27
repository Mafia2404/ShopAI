# 🛍️ ShopAI - AI-Powered E-Commerce Platform (MERN + AI + Voice + Payments)

![ShopAI Banner](https://github.com/Mafia2404/ShopAI/blob/main/frontend/logo.png)  
*A modern e-commerce platform with AI-powered recommendations, secure payments, and admin dashboard.*

🔗 **Live Demo:**  
- 👉 User Store: [https://shopai-frontend.onrender.com/](https://shopai-frontend.onrender.com/)  
- 👉 Admin Dashboard: [https://shopai-admin.onrender.com/](https://shopai-admin.onrender.com/)  

---

## 🚀 Key Features
| Feature          | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **AI Recommendations** | Google Gemini-powered personalized product suggestions.                   |
| **Secure Payments**   | Razorpay integration for seamless checkout. (Test mode enabled)          |
| **Admin Dashboard**   | Manage products, orders, users, and sales analytics.                      |
| **Google Auth**       | Firebase authentication for secure user login.                            |
| **Real-time Stock**   | Inventory updates sync across users.                                      |
| **Responsive UI**     | Mobile-friendly design with React.js + TailwindCSS.                       |

---

## 🛠️ Tech Stack
**Frontend**  
- React.js (Vite) 
- TailwindCSS  
- Firebase Authentication
- Web Speech API

**Backend**  
- Node.js + Express  
- MongoDB (Mongoose)
- Cloudinary (Image Storage)
- JWT + bcryptjs (Authentication)


**Integrations**  
- Razorpay Payment Gateway  
- Google Gemini API (AI Recommendations)  

**Deployment**  
- Render (Free Tier)  

---




## 🛠️ Installation Guide

### Prerequisites
- Node.js (v18+)  
- MongoDB Atlas (Free Tier)
- Firebase Authentication  
- Google Gemini API Key ([Get Here](https://ai.google.dev/))  
- Razorpay Test Keys ([Get Here](https://razorpay.com/docs/))  

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/shopai-mern.git
cd shopai-mern
```
### Step 1: Set Up Backend
```bash
  cd backend
```
### Step 3: Set Up Frontend
```bash
cd ../frontend
```
### Create .env file:
```bash
PORT
MONGODB_URL
JWT_SECRET
ADMIN_EMAIL
ADMIN_PASSWORD 
CLOUDINARY_NAME 
CLOUDINARY_API_KEY 
CLOUDINARY_API_SECRET 
RAZORPAY_KEY_SECRET 
RAZORPAY_KEY_ID
GEMINI_API_KEY
VITE_API_BASE_URL
VITE_FIREBASE_API_KEY
```
### Install dependencies & run:
```bash
npm install
npm run dev
```

---
```bash
📂 Project Structure
shopai-mern/
├── backend/
│   ├── controllers/    # API logic
│   ├── models/         # MongoDB schemas
│   ├── routes/         # Express routes
│   └── server.js       # Entry point
├── frontend/
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── pages/      # Next.js-like routing
│   │   └── store/      # Redux slices
├── .gitignore
└── README.md
```
---
🌟 Why This Project?<br>
✔ Interview-Ready - Covers full-stack (MERN + AI + Voice + Payments)<br>
✔ Major Project - Documentation-ready for college submissions<br>
✔ Portfolio Gold - Demonstrates real-world scalability<br>
---
### 🤝 Contributing
  Fork the repository
  
```bash
Create a new branch (git checkout -b feature)

Commit changes (git commit -m 'Add feature')

Push to branch (git push origin feature)

Open a Pull Request
```
---
---
### 👥 Contributors
<table> <tr> <td align="center"> <a href="https://github.com/Sakshi-1224"> <img src="https://avatars.githubusercontent.com/Sakshi-1224" width="80px;" alt="Sakshi's GitHub profile picture"/><br /> <sub><b>Sakshi Solanki</b></sub> </a><br /> 💻 Frontend, Firebase Auth, Razorpay Integration </td> <td align="center"> <a href="https://github.com/Mafia2404"> <img src="https://avatars.githubusercontent.com/Mafia2404" width="80px;" alt="Uddhav's GitHub profile picture"/><br /> <sub><b>Uddhav</b></sub> </a><br /> 🔧 Backend , AI Recommendations System </td> </tr> </table>
---
📜 License
MIT © ShopAI 2025
