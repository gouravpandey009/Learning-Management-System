# 🎓 Learning Management System (LMS) Project

Welcome to the **Learning Management System (LMS)** repository! This project is built using the **MERN stack** (MongoDB, Express.js, React, Node.js) alongside **Tailwind CSS**, **DaisyUI** for styling, **Cloudinary** for media management, and **Razorpay** for handling subscriptions.

## 📚 About

This LMS enables the creation and management of courses, media uploads, user enrollments, progress tracking, and subscription management. The project combines powerful technologies to deliver an interactive and efficient learning experience.

### 🛠️ Tech Stack:
- **MongoDB** for database
- **Express.js** for backend services
- **React** for frontend development
- **Node.js** for backend logic
- **Tailwind CSS** & **DaisyUI** for responsive design and UI
- **Cloudinary** for media uploads
- **Razorpay** for managing payments and subscriptions

---

## 🚀 Features

- 🔐 **User Authentication & Authorization**: Secure login and registration.
- 🖊️ **Course Management**: Create, modify, and delete courses.
- 🌩️ **Content Upload**: Manage course content using Cloudinary.
- 🧑‍🏫 **User Enrollment**: Enroll students in courses.
- 🏅 **Progress Tracking**: Track course completion and progress.
- 💻 **Interactive UI**: Dynamic user experience with React, Tailwind CSS, and DaisyUI.
- 💳 **Subscription Management**: Seamless payments and subscription handling with Razorpay.

---

## 🛠️ Prerequisites

Before running the project locally, ensure the following are installed:

- **Node.js** (v14.x or higher) 🟢
- **npm** (v6.x or higher) 📦
- **MongoDB** (v4.x or higher) 🍃
- **Cloudinary account** and API credentials ☁️
- **Razorpay account** and API credentials 💳

---

## ⚙️ Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Sukomal07/learning-management-system.git
   cd learning-management-system
   ```

2. **Install Server Dependencies**:

   ```bash
   cd server
   npm install
   ```

3. **Install Client Dependencies**:

   ```bash
   cd client
   npm install
   ```

4. **Set up Environment Variables**:  
   Create a `.env` file in the `server` directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=<your_mongoDB_URI>
   FRONTEND_URL=http://localhost:5173
   JWT_SECRET=<set_JWT_secret>
   JWT_EXPIRE=<set_JWT_EXP>
   CLOUD_NAME=<your_cloudinary_name>
   API_KEY=<your_cloudinary_api_key>
   API_SECRET=<your_cloudinary_api_secret>
   GMAIL_ID=<mail_id_for_sending_mail>
   APP_PASSWORD=<set_app_password_in_gmail>
   RAZORPAY_API_KEY=<your_razorpay_api_key>
   RAZORPAY_PLAN_ID=<your_subscription_plan_id>
   RAZORPAY_KEY_SECRET=<your_razorpay_key_secret>
   ```

---

## 🚀 Usage

1. **Start the Server**:

   ```bash
   cd server
   npm run dev
   ```

2. **Start the Client**:

   ```bash
   cd client
   npm run dev
   ```

3. **Access the Application**:  
   Open your browser and go to [http://localhost:5173](http://localhost:5173) 🌐

---

## 💳 Subscription Management

Users can purchase subscriptions to access premium content or features. The system is integrated with **Razorpay** for seamless payment handling.

### Features:
- 📅 View available subscription plans.
- 💳 Select and purchase a subscription plan via Razorpay.
- ❌ Cancel an existing subscription at any time.

---

## 📷 Media Management

Content creators can easily upload and manage course materials through **Cloudinary** integration for efficient media handling.

---

## 📈 Future Enhancements

- 🎥 **Live Classes**: Add live video sessions with student-teacher interaction.
- 📊 **Analytics Dashboard**: Detailed insights into user activity and course performance.
- 🛠️ **Admin Panel**: Enhanced admin panel for managing users and courses.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any bugs or suggestions.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgements

Special thanks to all the amazing open-source projects used in this LMS!

---

### 🔗 Useful Links

- **Live Demo**: [LMS Application](https://gouravpandeyvideoconferencing.vercel.app/)
- **GitHub Repository**: [GitHub Repo](https://github.com/gouravpandey009/video-conferencing)

---

With this layout, your `README.md` file will be visually appealing, informative, and well-structured with emojis, making it easy to understand.
