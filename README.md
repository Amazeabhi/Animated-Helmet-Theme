# 🪖 Ultra-Realistic Helmet Design Interface

![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-orange)

An immersive, high-fidelity web visualization tool for next-generation helmet engineering. This project utilizes advanced WebGL techniques to bridge the gap between industrial CAD and interactive web design.

---

## 🚀 Overview

This webpage is a high-performance interactive showcase designed for manufacturers and designers. It allows for the real-time exploration of high-poly helmet models with cinematic visual quality directly in the browser.

### Key Highlights:
* **Physics-Based Rendering (PBR):** Realistic material behavior for carbon fiber, matte resins, and iridescent visors.
* **Real-time Customization:** Dynamic color-way switching and material swapping without reload.
* **Ray-Traced Ambient Occlusion:** High-fidelity shadows in the crevices of the padding and vents.
* **Macro-Detail Zoom:** Specialized camera constraints allowing users to inspect textures down to the millimeter.

---

## 🛠 Tech Stack

* **Core:** React.js + Three.js
* **Rendering:** React Three Fiber (R3F) & Drei
* **Post-Processing:** Selective Bloom, SSAO, and Chromatic Aberration
* **Assets:** GLTF/GLB (Draco Compressed)
* **Styling:** Tailwind CSS

---

## 📦 Features & Functionality

### 1. Interactive 3D Viewer
Fully orbit-controlled camera with damped movement for a premium feel. Includes auto-rotate and "Exploded View" to see internal safety layers.

### 2. Environment Controls
Toggle between different lighting environments:
* **Studio:** Neutral, high-contrast lighting.
* **Trackside:** Warm, natural sunlight simulation.
* **Night:** Neon-influenced city reflections.

### 3. Material Editor
A sidebar UI allows users to modify:
* **Shell:** Carbon, Glossy, or Matte finishes.
* **Visor:** Clear, Smoked, or Gold-Mirror tint.
* **Hardware:** Anodized bolts or stainless steel accents.

---

## ⚙️ Installation

To get the project running on your local machine:

1. **Clone the Repo**
   ```bash
   git clone [https://github.com/yourusername/helmet-design-web.git](https://github.com/yourusername/helmet-design-web.git)
