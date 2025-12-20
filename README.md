# Hand-Controlled Particle System

A real-time WebGL experience built with **Three.js** that renders and animates a large-scale particle system, smoothly morphing between multiple complex spatial structures using hand gestures detected via **MediaPipe Hands**.

---

## 🔷 Rendering & Particle System

At the core of this project is a high-performance **GPU-accelerated particle renderer** built using Three.js.

- Renders **15,000+ particles** using `THREE.Points`
- Additive blending, fog, and sprite-based particles for depth and glow
- Smooth interpolation between particle states for cinematic morphing
- Continuous time-based rotation and motion for organic movement

Each particle maintains a target position and transitions smoothly, creating fluid structural transformations rather than abrupt shape changes.

---

## 🌌 Shape Morphing System

The particle system can dynamically morph between three distinct forms:

- **Ice Saturn**  
  A frozen planetary core surrounded by icy rings, designed using spherical distribution and orbital ring logic.

- **DNA Helix**  
  A double-helix structure with vertical progression, rotational motion, and subtle noise for a biological feel.

- **Black Hole (Inspired by Gargantua)**  
  A dense accretion disk and warped particle field inspired by the visual physics of *Interstellar’s* Gargantua — emphasizing mass, depth, and rotational gravity.

All transitions are procedural and calculated in real time.

---

## ✋ Gesture Controls

Hand gestures are captured using **MediaPipe Hands** and mapped directly to particle behavior and camera movement.

### Shape Switching
| Gesture | Action |
|------|------|
| 1 Finger | Ice Saturn |
| 2 Fingers | DNA Helix |
| 3 or More Fingers | Black Hole |

### Zoom Control
- **Pinch (thumb + finger close)** → Zoom Out  
- **Hand Spread** → Zoom In  

### Spatial Interaction
- Hand movement subtly offsets the particle system, creating a feeling of spatial control and depth.

All interactions are smoothed to avoid jitter and maintain visual stability.

---

## 🧠 Technical Highlights

- Real-time hand landmark tracking
- Gesture-based state switching
- Smooth morph interpolation using target buffers
- Camera depth control mapped to hand distance
- Modular shape calculation logic
- Fully client-side, no backend required

---

## 🚀 Running the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/hand-controlled-particle-system.git
   Open index.html in a modern browser

2. Allow camera access

3. Use your hand to interact with the system

**Best experienced on Chrome or Edge with a webcam.**

---

## 🙌 Author

**Achuth Akilesh**  
Product Designer & Data Analyst  
🌐 [Portfolio Website](https://madebyachuth.framer.website/)

