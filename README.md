# 🌌 Kinetic Gallery: Gesture-Driven Spatial Experience

![Kinetic Gallery Banner](https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6)

A premium, interactive 3D spatial gallery where you navigate through art and projects using only your hand gestures. Built with cutting-edge web technologies to create a seamless bridge between the physical and digital worlds.

**🚀 Live Demo:** [kinetic-gallery-pink.vercel.app](https://kinetic-gallery-pink.vercel.app)

---

## ✨ Features

- **🤲 Touchless Navigation:** Use hand gestures to rotate, zoom, and explore the 3D image sphere.
- **🖼️ Dynamic 3D Environment:** A high-performance spatial scene built with React Three Fiber and Three.js.
- **📸 Custom Uploads:** Drag and drop or upload your own images to see them instantly integrated into the 3D kinetic sphere.
- **⚡ Real-time Tracking:** Powered by Google MediaPipe for ultra-low latency hand landmark detection.
- **🎨 Premium Aesthetics:** Minimalist, sleek UI with smooth transitions and cinematic lighting.

---

## 🛠️ Tech Stack

- **Core:** [React 19](https://react.dev/)
- **3D Engine:** [Three.js](https://threejs.org/) & [React Three Fiber](https://docs.pmnd.rs/react-three-fiber)
- **AI/Vision:** [MediaPipe Tasks Vision](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Deployment:** [Vercel](https://vercel.com/)

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (Latest LTS recommended)
- A webcam for hand tracking interaction

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Harsh-karn/Kinetic-Gallery.git
   cd Kinetic-Gallery
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Navigate to `http://localhost:3000` (or the port shown in your terminal).

---

## 🎮 How to Use

1.  **Grant Camera Access:** The app requires webcam access to track your hand.
2.  **Wait for Sync:** The "Kinetic Gallery" syncing screen will disappear once your camera and the AI model are ready.
3.  **Rotate:** Move your hand across the frame to rotate the image sphere.
4.  **Zoom:** Bring your thumb and index finger closer or further apart to zoom in and out of the gallery.
5.  **Upload:** Use the "Upload Gallery" button in the top-left to populate the sphere with your own images.

---

## 📦 Deployment

This project is optimized for deployment on Vercel.

```bash
npm run build
```

The build will output to the `dist` folder, which can be served by any static hosting provider.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<div align="center">
  Developed with ❤️ by <a href="https://github.com/Harsh-karn">Harsh Karn</a>
</div>
