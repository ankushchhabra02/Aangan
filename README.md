<div align="center">
  
  <h3 align="center">Aangan – Your Ideal Real Estate App</h3>
  <br />
  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logo=react&color=20232A" alt="React Native" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&color=3178C6" alt="TypeScript" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logo=expo&color=000020" alt="Expo" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwindcss&color=06B6D4" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="Appwrite" />
  </div>
</div>

## <a name="introduction">🚀 Introduction</a>

**Aangan** is a React Native real estate app built with **Expo**, **Appwrite**, **Tailwind CSS**, and **TypeScript**.  
It allows users to browse, search, filter, and favorite properties — all wrapped in a modern, smooth mobile experience.

Whether you're looking for houses, condos, villas, or duplexes, Aangan makes it easy and intuitive to explore. The project is built from scratch to showcase clean architecture, real-time data, and professional-level usability.

---

## <a name="tech-stack">⚙️ Tech Stack</a>

| Layer             | Technologies Used                             |
| ----------------- | --------------------------------------------- |
| 🚀 Frontend       | React Native (Expo SDK), TypeScript, Tailwind |
| 🧩 Backend        | Appwrite (database, auth, file storage)       |
| 🛠️ Styling        | NativeWind (Tailwind for RN)                  |
| 📱 Authentication | Google Auth via Appwrite                      |
| 🔀 Data Fetching  | Custom hooks (`useAppwrite`)                  |

---

## <a name="features">🔍 Features</a>

- **Google Authentication**: Secure user login with Appwrite integration
- **Home Screen**: Displays featured and recommended properties
- **Explore Screen**: Browse all property types, with filters
- **Search Bar**: Real-time search across the listings
- **Property Detail**: Gallery, description, price, agent, reviews
- **Profile Screen**: User profile, my bookings, and security settings
- **Favorites**: Save your favorite properties for easy access
- **Notifications**: Appwrite real-time alerts for updates
- **Loading & Error Handling**: Smooth UX with loader screens and alerts

---

## <a name="quick-start">🛠️ Quick Start</a>

**Requirements**

- Node.js & npm/yarn
- Expo CLI (`npm install -g expo-cli`)
- Appwrite account (self-hosted or cloud instance)

**Setup Steps**

```bash
# Clone the repo
git clone https://github.com/ankushchhabra02/Aangan.git
cd aangan-app

# Install dependencies
npm install
# or
yarn

# Create an .env file in the root:
cat <<EOF > .env
APPWRITE_ENDPOINT=https://appwrite.yourdomain/v1
APPWRITE_PROJECT_ID=<your_project_id>
APPWRITE_DATABASE_ID=<your_db_id>
APPWRITE_COLLECTION_PROPERTY=<properties_coll>
APPWRITE_COLLECTION_AGENT=<agents_coll>
APPWRITE_COLLECTION_REVIEW=<reviews_coll>
APPWRITE_COLLECTION_GALLERY=<galleries_coll>
EOF

# Run Expo
npx expo start
```

---

## <a name="quick-start"> 🙏 Why This Project Stands Out</a>

- 📱 **Mobile-first UI** built with **React Native + Tailwind**
- ♻️ **Clean separation** with reusable hooks and components
- ⚡ **Real-time database**, authentication, and file handling via **Appwrite**
- 🚀 **Easy to deploy**, easy to test, and easy to scale

##

## <a name="quick-start">📸 Demo Screenshots</a>

<div style="display: flex; gap: 10px;">
  <img src="assets\screenshots\Screenshot_2025-07-27-12-20-16-89_f73b71075b1de7323614b647fe394240.jpg" alt="Splash Screen" width="32%" />
  <img src="assets\screenshots\Screenshot_2025-07-27-12-19-58-38_f73b71075b1de7323614b647fe394240.jpg" alt="Login Screen" width="32%" />
  <img src="assets\screenshots\Screenshot_2025-07-27-12-19-45-02_f73b71075b1de7323614b647fe394240.jpg" alt="Home  <img src="./assets/screenshots/home.jpg" alt="Home Screen" width="32%" />
  
</div>
<div style="display: flex; gap: 10px;">
<img src="assets\screenshots\Screenshot_2025-07-27-12-19-48-16_f73b71075b1de7323614b647fe394240.jpg" alt="Search Screen" width="32%" />
  <img src="assets\screenshots\Screenshot_2025-07-27-12-19-52-32_f73b71075b1de7323614b647fe394240.jpg" alt="Profile Screen" width="32%" />
  
</div>
