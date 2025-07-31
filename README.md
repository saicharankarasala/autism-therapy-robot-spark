# 🤖 Therapy for Autistic Children Using Robot

**College:** St. Joseph’s College of Engineering  
**Department:** Electronics and Communication Engineering  
**Project Title:** Therapy for Autistic Children Using Robot
**Competition:** IICDC 2019  

---

## 📘 Overview

**SPARK** is a socially assistive robot specifically designed to support children with **Autism Spectrum Disorder (ASD)** through interactive therapy sessions. It incorporates expressive visuals, speech capabilities, motion, and touch interaction to create an engaging and structured therapeutic experience. Unlike other commercially available therapy robots, SPARK integrates key developmental strategies, cloud data analytics, and customizable behavioral modules in a compact and cost-effective form.

---

## 🎯 Project Objectives

- Design an **interactive robot** that helps children with ASD develop social and communication skills.
- Create an **emotionally engaging interface** using visual displays and speech synthesis.
- Integrate **touch sensors**, LED indicators, and motor-driven facial/head movement.
- Enable **cloud connectivity** for session logging and therapist feedback.
- Use **open-source hardware and software platforms** to ensure affordability and customization.

---

## 🧠 Extended Theoretical Foundation

### 🌐 Autism & Robotics: Background

Autism Spectrum Disorder is a developmental condition characterized by:
- Communication and language difficulties
- Impaired social interaction
- Restricted or repetitive behaviors
- Difficulty generalizing learned behaviors to real-world contexts

Robots have been shown to be effective tools in therapy due to:
- Their **predictable behavior**
- **Non-judgmental presence**
- Ability to **repeat tasks consistently**
- Highly engaging sensory feedback (light, sound, movement)

---

### 🤖 What Makes SPARK Unique?

Existing therapy robots like Kaspar, Zeno, and QTrobot have advanced features but suffer from limitations:
- Lack of **expressive facial movement**
- Limited **head movement and gaze tracking**
- High **cost of implementation**
- Little to no **customization for therapist goals**
- Poor **cloud support** for tracking progress

SPARK addresses these challenges through:
- A **facial display module** using LED matrix or OLED screens
- **Rotational motors** for head tilt and nod gestures
- **Cloud-integrated analytics** for behavior tracking
- **Compact, modular design** for easy transport
- Use of **off-the-shelf microcontrollers** and **open-source software**

---

## 💻 Technical Design & Potential Software Architecture

### 👨‍💻 Programming Languages & Frameworks

| Component            | Suggested Tech Stack                             |
|---------------------|---------------------------------------------------|
| Microcontroller      | Arduino IDE (C/C++) or MicroPython (ESP32/RPi Pico) |
| Behavioral Logic     | Python (using FSMs or Behavior Trees)            |
| Speech Interaction   | Python + gTTS / pyttsx3 / Amazon Polly           |
| Display Control      | C++/Python with SSD1306 OLED or LED Matrix APIs  |
| Cloud Logging        | Firebase / Google Sheets API / AWS IoT           |
| Mobile App (optional)| Flutter or React Native                          |
| Motion Programming   | Arduino Servo Library or RPi GPIO Python Control |

### 🔧 Hardware Modules (Suggested)

| Module                 | Description                                     |
|------------------------|-------------------------------------------------|
| MCU                    | ESP32 / Arduino Mega / Raspberry Pi Pico        |
| OLED / LED Display     | For animated facial expressions                 |
| Servo Motors           | For head rotation and gestures                  |
| Touch Sensors          | To detect interactions and guide attention      |
| LEDs                   | Visual feedback and color-based emotion cues    |
| Battery & Solar Panel  | Power management for mobile use                 |
| Wi-Fi Module (ESP32)   | For data syncing with cloud or mobile app       |

---

## 🏗️ System Architecture

### 🟦 Input Subsystem
- Touch sensors detect child’s physical interaction
- Audio input (optional) for simple voice commands
- IR sensors for proximity/gesture detection

### 🟨 Processing Subsystem
- Finite State Machine (FSM) for controlling behavior sequences
- Decision tree based on child’s input
- Timing engine for interaction pacing

### 🟥 Output Subsystem
- OLED screen animates facial expressions (smile, blink, surprise)
- Servo motors rotate head in response to interaction
- Pre-recorded or synthesized voice feedback
- LED lights blink/pulse in sync with robot emotion state

---

## 📊 Cloud Connectivity & Data Logging

- Cloud database (e.g., Firebase) logs:
  - Interaction duration
  - Type of activity performed
  - Child response (via button/touch detection)
  - Timestamped feedback for therapist review
- Option for **real-time dashboards** using Google Sheets API or web portal

---

## 🧪 Use Case Flow

```plaintext
[Child touches robot] → [Robot smiles & says "Hello!"] 
→ [Displays emotion image] → [Prompts child: "Can you say Hi?"] 
→ [Tracks response via touch or time delay] 
→ [Logs session] → [Gives reward signal or next prompt]
```

---

## 📚 Literature & Research References

- Scassellati, B. et al. “Robots for Use in Autism Research”, *Annual Review of Biomedical Engineering*, 2012.  
- Kozima, H., Michalowski, M.P., & Nakagawa, C. (2005). *“Keepon: A Playful Robot for Research, Therapy, and Entertainment”*  
- Dautenhahn, K. (2008). *“Socially intelligent robots: dimensions of human–robot interaction.”* *Philosophical Transactions of the Royal Society B*  
- ZenoR25, QTrobot, Kaspar documentation and case studies  

---

## 🧩 Future Enhancements

- Add **camera-based emotion detection** using OpenCV or MediaPipe  
- Integrate **voice-based Q&A modules** for adaptive conversation  
- Train custom **AI models for therapy personalization** (TensorFlow Lite)  
- Enable **real-time syncing** with therapist dashboards via the cloud  
- Introduce **multi-language support** to increase accessibility  

---

## 📣 Social Impact

SPARK has the potential to be a **transformative tool** in autism therapy, especially in:

- **Low-income and rural communities** with limited therapist availability  
- **Special education centers** seeking interactive, tech-based interventions  
- **Home environments** where parents can reinforce therapy lessons  

Its interactive nature helps children:

- Practice social skills in a **safe, repeatable way**  
- Build confidence through **non-threatening interactions**  
- Engage emotionally via **personalized robot behavior**

---

## 🙏 Acknowledgments

We extend our heartfelt thanks to:

- 🏫 Faculty & lab teams at *St. Joseph’s College of Engineering*  
- 👪 Families and therapists who provided valuable feedback  
- 🏆 IICDC 2019 organizers for the opportunity and platform  

---

## 📬 Contact

For inquiries, collaboration opportunities, or access to schematics and documentation:  
📧 **kvsc1511@gmail.com**
