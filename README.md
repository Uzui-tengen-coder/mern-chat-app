# 💬 MERN Chat App

A real-time chat application built using the MERN Stack — MongoDB, Express, React, and Node.js — with Socket.IO for live communication. Users can send text and image messages, see online statuses, and enjoy a clean and responsive UI.

---

## 🚀 Features

- 🔐 User authentication (Login & Signup)
- 💬 Real-time chat with Socket.IO
- 🖼️ Send and receive image messages
- ✅ Seen/unseen message indicators
- 🟢 Online users detection
- 📱 Mobile responsive design
- 🔧 Cloudinary integration for image storage

---

## 🛠️ Tech Stack

- **Frontend**: React, TailwindCSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose)  
- **Real-time**: Socket.IO  
- **Image Uploads**: Cloudinary  
- **Authentication**: JWT

---

## ⚙️ Getting Started (Development)

### 1. Clone the Repository

```bash
git clone https://github.com/Uzui-tengen-coder/mern-chat-app.git
cd mern-chat-app
```

### 2. Install Dependencies

```bash
# For backend
cd server
npm install

# For frontend
cd ../client
npm install
```

### 3. Create `.env` Files

Create a `.env` file inside the `server` folder and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

> ⚠️ Do **not** upload your `.env` file to GitHub! It contains sensitive data.

---

## 🌐 Deployment

- **Frontend**: Vercel  
- **Backend**: Render / Railway / Cyclic (choose any backend host that supports Node.js)  
- Make sure to set your `.env` variables in the deployment dashboard.

---

## 🧪 Testing

- Test by opening two different browsers or incognito tabs  
- Try sending text and images  
- Try refreshing the page to ensure messages persist  
- Check seen/unseen status, and online indicators  

---

## 📝 Notes

- If `.env` file was ever pushed to GitHub by mistake:
  ```bash
  git rm --cached .env
  echo ".env" >> .gitignore
  git add .gitignore
  git commit -m "Remove .env from repo"
  git push
  ```

---

## 📷 Screenshots 
<img width="1920" height="885" alt="quickchat screenshot1" src="https://github.com/user-attachments/assets/9db8ed16-6cfd-44d6-8a9c-e831b2822570" />

<img width="1920" height="970" alt="quickchat screenshot2" src="https://github.com/user-attachments/assets/3264c848-7bc0-4f86-8ee4-487de3605108" />

---

## 👨‍💻 Author

Made with ❤️ by Uzui-tengen-coder
