# 3D Physics Kart Game

A lightweight 3D kart game built on top of a **custom 3D engine wrapper** integrating **Three.js** and **Cannon.js**. It features object-oriented entity architecture, post-processing visuals, dynamic lighting, custom input handling, and 3D positional audio.

🔗 **[Play Live Demo](https://3d-engine-car.vercel.app/)**

---

## ✨ Key Features

* **Custom Engine Wrapper:** Modular abstraction layer (`World`, `BaseEntity`, `AudioManager`, `Camera`) encapsulating low-level Three.js rendering and Cannon.js physics loops into a clean API.
* **Custom Entity System:** Extensible `Entity` class that automatically synchronizes Three.js visual meshes with Cannon.js physics bodies every frame.
* **Custom Input Manager:** Input handler for responsive driving physics, steering angles, drifting, and key bindings.
* **Lighting & Post-Processing:** Dynamic directional lights, real-time shadows, and post-processing pipelines for enhanced visual aesthetics.
* **Real-Time Physics:** 3D vehicle handling, drifting physics, rigid body collisions, and dynamic box stacking powered by `cannon-es`.
* **Interactive Triggers:** Flat ground texture pads (`ImageTrigger`) with sensor volumes that display HTML UI popup links when entered.
* **Spatial Audio Engine:** Dynamic engine RPM pitch adjustments, tire skid audio, horn triggers, and background music.
* **Physics Debug Mode:** Toggleable wireframe collision overlay for runtime debugging.

---

## 🎮 Controls

| Key | Action |
| :--- | :--- |
| **W** | Accelerate |
| **S** | Reverse |
| **A / D** | Steer |
| **Shift** | Drift |
| **Space** | Brake |
| **H** | Horn / Beep |
| **P** | Toggle Physics Debug Wireframes |

---

## 🛠️ Tech Stack

* **Three.js** — 3D Graphics & Post-Processing Pipeline
* **Cannon-es** — 3D Physics Engine
* **Vite** — Development & Build Tool

---