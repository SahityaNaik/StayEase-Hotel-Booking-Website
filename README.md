# StayEase 🏨 – Hotel Booking Website  

StayEase is a **full-stack hotel booking platform** that connects **travelers** with **hotel owners**.  
Users can explore and book rooms seamlessly, while owners can manage listings, availability, and bookings with ease.  

---

## 🌐 Link  

🔗 **Live Demo:** [stayease-hotel-booking.vercel.app](https://stayease-hotel-booking.vercel.app/)  

---

## ✨ Features  

### 👤 For Users
- Browse hotels & rooms with filtering and sorting  
- View detailed room information with images and ratings  
- Secure booking flow with Stripe integration  
- Booking history & management in "My Bookings"  
- Instant booking confirmation via email  

### 🏨 For Owners
- Owner dashboard with booking stats  
- Add & manage room listings
- Toggle room availability  
- View and manage bookings for their hotels  

### 🔐 Authentication
- Powered by **Clerk** for sign-in/sign-up  
- Role-based access: Users and Owners  
- Secure API with JWT validation in backend  

---

## 🛠 Tech Stack  

**Frontend (Client):**  
- React (Vite) – Fast and modern frontend  
- Clerk – Authentication & role management  
- Axios + Context API – Data fetching & state management  
- Tailwind CSS – Modern styling  

**Backend (Server):**  
- Node.js + Express – RESTful API server  
- MongoDB + Mongoose – Database & models  
- Stripe – Payments & webhooks  
- Cloudinary – Image storage  
- Nodemailer – Email notifications  

---

## 🚀 Getting Started  

### Prerequisites
- Node.js v16+  
- MongoDB instance  
- Cloudinary account  
- Clerk project (for auth)  
- Stripe account (for payments)  

### Installation  

Clone repository:  
    git clone https://github.com/SahityaNaik/StayEase-Hotel-Booking-Website.git  

Install client dependencies:  
    cd client  
    npm install  

Install server dependencies:  
    cd ../server  
    npm install  

### Environment Variables  

Create a `.env` file in the **server** folder with:  

    MONGO_URI=your_mongodb_uri  
    CLERK_SECRET_KEY=your_clerk_secret  
    STRIPE_SECRET_KEY=your_stripe_secret  
    CLOUDINARY_CLOUD_NAME=your_cloudinary_name  
    CLOUDINARY_API_KEY=your_cloudinary_key  
    CLOUDINARY_API_SECRET=your_cloudinary_secret  
    EMAIL_USER=your_email  
    EMAIL_PASS=your_email_password  

### Running the Project  

Run client:  
    cd client  
    npm run dev  

Run server:  
    cd ../server  
    npm run dev  
