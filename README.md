# 🎬 YouTube Clone (React + Redux + Firebase)

A fully responsive **YouTube Clone** built using **React, Redux, Firebase Authentication, and YouTube Data API v3**. This project recreates the core UI and functionality of YouTube such as:

* 🔍 Video Search
* 📺 Video Playback
* 📁 Channel Pages
* 💬 Comments Section
* 🔐 Google Authentication (Login with Google)
* 🏠 Home Feed with Trending Videos

> **Note:** This is a frontend-focused implementation. Features like likes, subscriptions, and history are UI-based and may not persist without a backend database.

---

## 🚀 Tech Stack

| Technology           | Purpose                        |
| -------------------- | ------------------------------ |
| **React JS**         | UI Development                 |
| **Redux**            | State Management               |
| **Firebase Auth**    | Google Login                   |
| **YouTube Data API** | Fetching Videos & Channel Data |
| **Sass (SCSS)**      | Styling                        |

---

## 🖥️ Features

✅ Login with Google (Firebase Authentication)
✅ Display Trending & Category-based Videos
✅ Infinite Scroll & Lazy Loading
✅ Watch Video Page with Comments
✅ Search Videos & Channels
✅ Responsive UI (Mobile Friendly)

💡 *Advanced Features (UI only):*

* Like Button, Subscribe Button (Frontend visuals)
* Sidebar Navigation (Home, Subscriptions, Library)

---

## ⚙️ Setup & Installation

```bash
# Clone the repository
git clone https://github.com/your-username/Youtube_Clone.git
cd Youtube_Clone

# Install dependencies
npm install

# Run the Project
npm start
```

---

## 🔐 Firebase Setup (Google Login)

1. Create Firebase Project at [https://console.firebase.google.com](https://console.firebase.google.com)
2. Enable **Google Authentication**
3. Create `firebase.js` file in `/src` directory
4. Add your Firebase Config:

```js
import firebase from "firebase/app";
import "firebase/auth";

const firebaseConfig = {
  apiKey: "YOUR_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_ID",
};

firebase.initializeApp(firebaseConfig);

export const auth = firebase.auth();
export default firebase;
```

---

## 📡 YouTube API Setup

1. Go to **Google Cloud Console** → Enable **YouTube Data API v3**
2. Create API Key
3. Add API Key to `.env` file:

```
REACT_APP_YOUTUBE_API_KEY=YOUR_API_KEY
```

---

## 🛠 Folder Structure

```
src/
 ├─ components/
 ├─ redux/
 ├─ pages/
 ├─ firebase.js
 └─ App.js
```

---

## 🌍 Deployment

You can deploy this project on:

* 🔹 **Vercel**
* 🔹 **Netlify**
* 🔹 **Firebase Hosting**

```bash
npm run build
vercel deploy
```

---

## 📜 License

This project is created for **educational purposes** and is not intended for commercial use.

---

## ✨ Author

👩‍💻 **Sri Charitha**
📧 GitHub: [https://github.com/sricharitha1](https://github.com/sricharitha1)

---

⭐ *If you like this project, don’t forget to star the repository!* ⭐
