# 🧠 Motor Cortex Rehabilitation Program
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Unity 2022 LTS](https://img.shields.io/badge/Unity-2022_LTS-black?logo=unity)](https://unity.com/)
[![Platform: Windows x64](https://img.shields.io/badge/Platform-Windows_x64-blue)](#)  
*A camera-based virtual physical-therapy companion that brings the clinic to your living room—entirely **offline**.*

---

## ✨ What It Does
- **Real-time hand-tracking** using any built-in or USB webcam—no extra hardware required.  
- **Guided exercise library** covering range-of-motion, strength, and dexterity drills.  
- **Adaptive difficulty** that scales challenge automatically as your form improves.  
- **Instant visual & audio feedback** to keep you motivated and consistent.  
- **Session analytics** that log reps, hold times, and weekly progress.  

---

## 🛠️ Made with Unity
| Component | Details |
|-----------|---------|
| **Engine** | Unity 2022 LTS (URP) |
| **Build** | Stand-alone **`.exe`** (Windows 10/11, x64) |
| **Internet** | *Not required*—all processing happens locally |
| **Source code** | Full Unity project available for download |

> **🔗 Download the complete Unity project**  
> Grab the latest `.zip` of the project from Google Drive:  
> https://drive.google.com/drive/folders/1T3hHTbLy2oSWz9mkdqWPJFaFSg2ozzPw?usp=sharing

---

## 💡 Who It Helps
| Use-Case             | Examples of Potential Users |
|----------------------|-----------------------------|
| **Orthopaedic rehab** | Post-surgery (carpal tunnel, shoulder repair), fracture recovery |
| **Neurological rehab** | Stroke, TBI, cerebral palsy, multiple sclerosis |
| **Preventive exercise** | Desk workers, seniors maintaining mobility, athletes in off-season |

*(Illustrative, not exhaustive.)*

---

## ⚠️ Medical Disclaimer
> **This software is an assistive tool, *not* stand-alone treatment.**  
> Always consult a licensed physician or physical-therapy professional **before** using, and follow their guidance on exercise selection, intensity, and frequency.  
>  
> Motor Cortex Rehabilitation Program **does not diagnose, treat, or cure** any condition. It has **not been evaluated by the U.S. FDA** or equivalent authorities. Use is **at your own risk**, and the authors accept **no liability** for injury, loss, or damages arising from its use.

---

## 🚀 Quick Start (End Users)
1. **Download** the latest release ZIP from the [Releases](https://github.com/ericosborne97/MotorCortexRehabilitationProgram/releases) page.  
2. **Extract** the archive anywhere (e.g., `C:\Programs\MotorCortexRehab\`).  
3. **Run** `MotorCortexRehab.exe`. The app will open full-screen and guide you through camera setup.  

| Minimum specs | Value |
|---------------|-------|
| OS            | Windows 10 / 11 (64-bit) |
| CPU           | x86-64 with SSE4.1 |
| RAM           | 4 GB |
| Camera        | 720 p @ 30 fps or better |

---

## 🧑‍💻 Building from Source (Developers)
```bash
git clone https://github.com/YourUser/motor-cortex-rehab.git
cd motor-cortex-rehab
# Open the project in Unity 2022 LTS, then Build → Windows x86_64
