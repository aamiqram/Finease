# FinEase 💰

## 🌐 Live Demo
**[Visit FinEase →](https://finese-client.web.app)**

---

## 📝 Project Overview

FinEase is a modern, full-stack personal finance management application designed to help users take complete control of their financial life. Built with the MERN stack, FinEase provides an intuitive platform for tracking income and expenses, analyzing spending patterns, and making data-driven financial decisions.

The application features real-time balance calculations, interactive data visualizations, and comprehensive transaction management. With secure authentication, cloud-based data persistence, and a beautiful responsive interface, FinEase makes personal finance management effortless and engaging.

Whether you're budgeting for the first time or looking to optimize your spending habits, FinEase provides the tools and insights you need to achieve your financial goals.

---

## ⚡ Core Features

### 💳 Smart Transaction Management
- **Add Transactions:** Quickly record income and expense entries with category selection
- **View All Transactions:** Browse complete transaction history with filtering options
- **Update Records:** Edit transaction details including amount, category, and date
- **Delete Entries:** Remove unwanted transactions with confirmation prompts
- **Real-time Balance:** Automatic calculation of current balance based on all transactions
- **Category System:** Organize transactions by customizable categories (Food, Transport, Salary, etc.)

### 📊 Interactive Reports & Analytics
- **Monthly Trends:** Visualize income and expense patterns over time with line charts
- **Category Breakdown:** Pie charts showing expense distribution across categories
- **Income vs Expense:** Bar charts comparing monthly income against expenses
- **Financial Insights:** Quick stats showing total income, expenses, and net savings
- **Custom Date Ranges:** Filter reports by specific time periods
- **Visual Dashboard:** Beautiful charts powered by Recharts library

### 🔐 Secure Authentication
- **Email/Password Login:** Traditional authentication with secure password handling
- **Google Sign-In:** One-click authentication using Google OAuth
- **Password Reset:** Forgot password functionality with email verification
- **Protected Routes:** Secure access to financial data with route guards
- **Session Management:** Persistent login sessions with automatic token refresh
- **User Profiles:** Personalized experience with user information display

### 🎨 Modern UI/UX
- **Dark Mode Support:** Seamless theme switching with persistent preferences
- **Responsive Design:** Optimized layouts for mobile, tablet, and desktop devices
- **Tailwind CSS v4.1:** Latest styling framework with zero-config setup
- **DaisyUI Components:** Pre-built, customizable UI components
- **Smooth Animations:** Subtle transitions for enhanced user experience
- **Intuitive Navigation:** Clean, organized interface with easy access to all features

### 🔄 Advanced Functionality
- **Real-time Sorting:** Sort transactions by date or amount (ascending/descending)
- **Backend Queries:** Server-side sorting and filtering for optimal performance
- **Search Capability:** Find specific transactions quickly with search functionality
- **Data Validation:** Form validation to ensure data accuracy
- **Toast Notifications:** Real-time feedback for user actions
- **Error Handling:** Graceful error messages and fallback UI

### 💾 Cloud Integration
- **MongoDB Atlas:** Reliable cloud database for data persistence
- **Firebase Hosting:** Fast, secure hosting with SSL certificates
- **Automatic Backups:** Cloud-based data safety and redundancy
- **Cross-device Sync:** Access your financial data from any device

---

## 🛠 Technologies Used

### Frontend Stack
![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router_v6-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_v4.1-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Key Frontend Technologies:**
- **React 18** - Modern UI library with concurrent features
- **Vite** - Next-generation frontend build tool
- **React Router DOM v6** - Declarative routing for React applications
- **Tailwind CSS v4.1** - Utility-first CSS framework (zero-config)
- **DaisyUI** - Tailwind CSS component library
- **Firebase Authentication** - Secure user authentication system
- **Recharts** - Composable charting library for React
- **SweetAlert2** - Beautiful, responsive popup boxes
- **React Toastify** - Toast notifications for React
- **React Icons** - Popular icon packs as React components

### Backend Stack
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

**Key Backend Technologies:**
- **Node.js** - JavaScript runtime for server-side development
- **Express.js** - Fast, minimalist web framework
- **MongoDB** - NoSQL database for flexible data storage
- **MongoDB Native Driver** - Official MongoDB driver for Node.js
- **CORS** - Cross-Origin Resource Sharing middleware
- **dotenv** - Environment variable management

---

## 📦 Dependencies

### Client-side Dependencies
```json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-router-dom": "^6.20.0",
  "firebase": "^10.7.0",
  "tailwindcss": "^4.1.0",
  "daisyui": "^4.4.0",
  "recharts": "^2.10.0",
  "sweetalert2": "^11.10.0",
  "react-toastify": "^9.1.0",
  "react-icons": "^4.12.0",
  "axios": "^1.6.0"
}
```

### Server-side Dependencies
```json
{
  "express": "^4.18.0",
  "mongodb": "^6.3.0",
  "cors": "^2.8.5",
  "dotenv": "^16.3.0"
}
```

---

## 🚀 How to Run Locally

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **MongoDB Atlas Account** (for cloud database)
- **Firebase Project** (for authentication)

### Installation Steps

#### 1. Clone the Repository
```bash
git clone https://github.com/aamiqram/Finease.git
cd Finease
```

#### 2. Setup Client (Frontend)
```bash
cd client
npm install
```

Create `.env` file in the client directory:
```env
VITE_APIKEY=your_firebase_api_key
VITE_AUTHDOMAIN=your_firebase_auth_domain
VITE_PROJECTID=your_firebase_project_id
VITE_STORAGEBUCKET=your_firebase_storage_bucket
VITE_MESSAGINGSENDERID=your_firebase_messaging_sender_id
VITE_APPID=your_firebase_app_id
VITE_API_URL=http://localhost:5000
```

#### 3. Setup Server (Backend)
```bash
cd ../server
npm install
```

Create `.env` file in the server directory:
```env
PORT=5000
MONGODB_URI=your_mongodb_atlas_connection_string
```

#### 4. Start Development Servers

**Terminal 1 - Start Backend:**
```bash
cd server
npm start
# or for development with nodemon
npm run dev
```

**Terminal 2 - Start Frontend:**
```bash
cd client
npm run dev
```

#### 5. Access the Application
Open your browser and navigate to:
```
http://localhost:5173
```

Backend API runs on:
```
http://localhost:5000
```

---

## 🔗 Related Links

- **Live Website:** [finese-client.web.app](https://finese-client.web.app)
- **GitHub Repository:** [github.com/aamiqram/Finease](https://github.com/aamiqram/Finease)
- **Firebase Console:** [console.firebase.google.com](https://console.firebase.google.com)
- **MongoDB Atlas:** [cloud.mongodb.com](https://cloud.mongodb.com)

---

## 👨‍💻 Author

**Abu Abdullah Mohammed Iqram**
- **GitHub:** [@aamiqram](https://github.com/aamiqram)
- **LinkedIn:** [aamiqram](https://www.linkedin.com/in/aamiqram/)
- **Email:** aamiqram.dev@gmail.com
- **Portfolio:** [portfolio-aami.vercel.app](https://portfolio-aami.vercel.app)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Firebase for authentication and hosting services
- MongoDB Atlas for cloud database solutions
- Recharts for beautiful data visualization
- Tailwind CSS team for the amazing framework
- Open-source community for valuable packages

---

**⭐ If you find this project helpful, please give it a star on GitHub!**
