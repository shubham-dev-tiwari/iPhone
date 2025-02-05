
# **📱 iPhone 3D Model Viewer**  
🚀 **A stunning, interactive 3D iPhone model—right in your browser!**  
Built with **React Three Fiber, GSAP, and Three.js**, this project brings **smooth animations, realistic lighting, and full interactivity** to 3D product visualization.  

<div align="center"> <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" width="80%" alt="Dark Theme 3D iPhone Demo"> </div> 

![GitHub stars](https://img.shields.io/github/stars/shubham-dev-tiwari/iPhone?style=for-the-badge)  
![GitHub forks](https://img.shields.io/github/forks/shubham-dev-tiwari/iPhone?style=for-the-badge)  
![GitHub license](https://img.shields.io/github/license/shubham-dev-tiwari/iPhone?style=for-the-badge)  

---

## **✨ Features**  
✅ **Realistic 3D iPhone Model** – Explore every angle  
✅ **Smooth GSAP Animations** – Eye-catching transitions  
✅ **Interactive Camera Controls** – Rotate, zoom, and pan freely  
✅ **Optimized Performance** – Lazy loading & suspense  
✅ **Realistic Lighting** – Ambient, directional, and soft shadows  

---

## **🚀 Quick Start**  
### **1️⃣ Clone the Repo**  
```sh
git clone https://github.com/shubham-dev-tiwari/iPhone.git
cd iPhone
```
### **2️⃣ Install Dependencies**  
```sh
npm install
```
### **3️⃣ Run the Development Server**  
```sh
npm run dev
```
🔗 Open `http://localhost:5173/` in your browser and experience the magic!  

---

## **🎮 Controls**  
🖱️ **Rotate** → Left-click and drag  
🔍 **Zoom** → Scroll wheel  
📍 **Pan** → Right-click and drag  

---

## **📂 Project Structure**  
```
📦 iPhone
 ├── 📁 public          # Static assets
 ├── 📁 src
 │   ├── 📁 components  # Reusable 3D components
 │   │   ├── Lights.jsx
 │   │   ├── IPhone.jsx
 │   │   ├── Loader.jsx
 │   │   ├── ModelView.jsx
 │   ├── 📁 styles      # Styling (CSS/Tailwind)
 │   ├── App.jsx        # Main Application
 │   ├── main.jsx       # React Entry Point
 ├── .gitignore
 ├── package.json
 ├── README.md
 └── vite.config.js
```

---

## **🛠️ Built With**  
🚀 **React + Vite** – Fast and modern frontend stack  
🎨 **Three.js & React Three Fiber** – 3D rendering made easy  
🌀 **GSAP** – Smooth animations  
🔦 **@react-three/drei** – Helper utilities for Three.js  
🔍 **Sentry** – Error tracking & debugging  

---

## **🌎 Live Demo**  
📌 **[Coming Soon!]**  

---

## **📸 Screenshots**  

(https://github.com/user-attachments/assets/f0a3517c-698e-46ad-84c5-6bc5f64c44d6)


---

## **🚀 Deployment**  
### **Deploy on Vercel / Netlify**  
```sh
npm run build
```
Then, upload the `dist/` folder to **Vercel** or **Netlify** for instant hosting.  

---

## **🐛 Troubleshooting & Debugging**  
### ❓ **Model Not Showing?**  
🔹 Check if the 3D model path is correct  
🔹 Run `console.log(item);` inside `ModelView.jsx`  

### ❓ **Animations Not Working?**  
🔹 Ensure GSAP timelines are initialized inside `useEffect`  
🔹 Debug GSAP animations using `.clear()`  

---

## **🤝 Contributing**  
💡 Want to improve this project?  
1. **Fork** this repo  
2. **Create a new branch**: `git checkout -b feature-branch`  
3. **Commit your changes**: `git commit -m "Added a cool feature"`  
4. **Push your branch**: `git push origin feature-branch`  
5. **Open a Pull Request**  

---

## **📜 License**  
📄 This project is **MIT Licensed** – feel free to modify, share, and contribute!  



