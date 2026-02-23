# 🖐️ Hand-Controlled Particle System

A real-time **WebGL experience** where hand gestures dynamically morph cinematic 3D particle structures using **Three.js** and **MediaPipe Hands**.

🚀 **Live Demo:** https://achuth-webgl-particle-system.netlify.app/  
💡 *Best experienced on desktop with a webcam (Chrome / Edge).*

---

## ✨ What This Project Does

- Renders **15,000+ GPU-accelerated particles** in real time  
- Smoothly morphs between complex 3D structures  
- Uses **hand gestures** for shape switching, zoom, and spatial control  
- Fully client-side — **no backend**

---

## 🌌 Particle Morphing Modes

- **🪐 Ice Saturn**  
  A frozen planetary core with orbiting icy rings.

- **🧬 DNA Helix**  
  A biologically inspired double-helix with vertical motion and rotation.

- **🕳️ Black Hole (Gargantua-inspired)**  
  A dense accretion disk emphasizing depth, gravity, and rotational mass.

All transitions are **procedural, smooth, and calculated in real time**.

---

## ✋ Gesture Controls

### Shape Switching
| Gesture | Mode |
|------|------|
| ☝️ 1 Finger | Ice Saturn |
| ✌️ 2 Fingers | DNA Helix |
| 🖖 3 Fingers | Black Hole |

### Zoom & Interaction
- 🤏 Pinch → Zoom Out  
- 🖐️ Hand Spread → Zoom In  
- Hand movement subtly offsets the particle field for spatial depth

All inputs are smoothed to avoid jitter.

---

## 🧠 Technical Highlights

- Real-time hand landmark tracking  
- Gesture-based state management  
- Smooth morph interpolation via target buffers  
- Camera depth mapped to hand distance  
- Modular shape-generation logic  
- Three.js `THREE.Points` with additive blending, fog, and sprite particles

---

## 🚀 Run Locally

```bash
git clone https://github.com/achuthprince004/hand-controlled-particle-system.git
```

## 🙌 Author

**Achuth Akilesh**  
Product Designer & Data Analyst  
🌐 [Portfolio Website](https://madebyachuth.framer.website/)



