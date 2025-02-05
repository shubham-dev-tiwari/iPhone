📱 iPhone 3D Model Viewer

🚀 Welcome to the future of 3D product visualization!
This project brings a realistic, interactive iPhone model to your browser with buttery-smooth animations and seamless camera controls. Built with React Three Fiber, GSAP, and Three.js, this is more than just a model—it’s an experience.

✨ Live Demo: Coming Soon!


🔥 Features That Make It Stand Out

✅ Stunning 3D iPhone Model – Explore every angle with high-quality rendering
✅ Smooth GSAP Animations – Enjoy sleek transitions between views
✅ Interactive Controls – Rotate, zoom, and pan like you own it!
✅ Optimized Performance – Lazy loading & suspense for a seamless feel
✅ Realistic Lighting – Ambient, directional, and point lights for depth

🔽 Check it out in action!
🚀 Quick Start
1️⃣ Clone the Repo

git clone https://github.com/shubham-dev-tiwari/iPhone.git
cd iPhone

2️⃣ Install Dependencies

npm install

3️⃣ Run the Development Server

npm run dev

🚀 Open http://localhost:5173/ in your browser and enjoy!
🔨 Built With

🔹 React + Vite – Fast and modern frontend stack
🔹 Three.js & React Three Fiber – Making 3D easy for the web
🔹 GSAP – For mind-blowing animations
🔹 @react-three/drei – Utilities to make Three.js development easier
🔹 Sentry – To track and squash those pesky errors
📂 Project Structure

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

🎮 Controls

    Rotate: Left-click and drag
    Zoom: Scroll wheel
    Pan: Right-click and drag
    Switch Views: (Coming Soon)

🚀 Deployment
Using Vercel / Netlify

    Build the project

    npm run build

    Deploy the dist/ folder to Vercel or Netlify
    Done! 🚀

🐛 Troubleshooting & Debugging
❓ Model Not Showing?

🔹 Check if the 3D model path is correct
🔹 Run console.log(item); inside ModelView.jsx
❓ Animations Not Working?

🔹 Ensure GSAP timelines are initialized inside useEffect
🔹 Debug GSAP animations using .clear()
📜 License

📄 This project is MIT Licensed – feel free to modify, share, and contribute!
