# SmartVoice Hub – Privacy-Focused Smart Home Voice Dashboard
**Team Name:** Apex

---

## Problem Statement

Current smart home interfaces often depend on cloud services, multiple disconnected apps, and complex menus. Users do not receive instant visual confirmation of voice commands, and privacy is compromised because voice data is frequently sent to external servers.

**Our problem statement:** *Current smart home interfaces lack an intuitive, privacy-focused voice dashboard that provides instant, unified visual feedback for local natural language commands.*

---

## Proposed Solution

**SmartVoice Hub** is a privacy-first smart home dashboard that understands natural language voice commands locally and instantly displays unified visual feedback.

Example commands:

* “Turn on bedroom light”
* “Set fan speed to 3”
* “Switch off all lights”
* “Show living room status”

The system processes commands locally, updates device states in real time, and displays the result on a single dashboard.

---

## Key Features

* 🎙️ Natural language voice commands
* 🔒 Local/offline command processing
* ⚡ Instant visual feedback dashboard
* 🏠 Unified control for multiple devices
* 🌐 Multilingual-ready interface
* 📊 Real-time device status monitoring
* 📱 Responsive web interface for desktop and mobile

---

## Target Users

* Home owners
* Elderly users
* Users with limited technical knowledge
* Privacy-conscious smart home users
* Small offices and hostels

---

## Use Case

1. User speaks: **“Turn on kitchen light.”**
2. Voice is converted to text locally.
3. Command is interpreted by the local controller.
4. Device state changes.
5. Dashboard instantly shows **Kitchen Light: ON**.

This removes confusion and confirms that the command was executed successfully.

---

## Technology Stack

| Layer                | Technology                     |
| -------------------- | ------------------------------ |
| Frontend             | HTML, CSS, JavaScript          |
| Backend              | Python, FastAPI                |
| Voice Processing     | Speech Recognition / Local STT |
| Device Communication | MQTT / REST API                |
| Database             | SQLite                         |
| Deployment           | Localhost / Edge Device        |

---

## System Architecture

```text
User Voice
    ↓
Local Speech-to-Text
    ↓
Command Parser (NLP)
    ↓
Device Controller
    ↓
Smart Devices / Simulator
    ↓
Visual Dashboard Feedback
```

All major processing is designed to run locally to improve privacy and reduce latency.

---

## Prototype

### Dashboard

Add screenshot here.

### Voice Command Demo

Add screenshot or GIF here.

**Demo Video:** Add YouTube or Drive link here.

**Live Demo:** Add local or hosted link here.

---

## Innovation

What makes our solution different?

* Privacy-first local processing
* Instant visual confirmation after every command
* Single dashboard instead of multiple apps
* Designed for low-cost hardware deployment
* Simple interaction for non-technical users

---

## Expected Impact

* Improved accessibility for elderly users
* Better trust in smart home systems
* Reduced dependence on cloud services
* Faster command response time
* Enhanced privacy and data security

---

## Scalability

The prototype can be extended to support:

* Smart bulbs, fans, ACs, and sensors
* Energy monitoring
* Home security alerts
* Edge AI assistants
* Integration with Home Assistant and IoT platforms

---

## Future Scope

* Wake-word detection (“Hey Home”)
* Offline multilingual speech model
* Mobile application
* User authentication and role management
* AI-based automation routines
* Energy optimization recommendations

---

## Repository Structure

```text
project/
│── frontend/
│── backend/
│── assets/
│── screenshots/
│── README.md
```

---

## How to Run

### Backend

```bash
pip install -r requirements.txt
uvicorn app:app --reload
```

### Frontend

Open `index.html` in a browser or serve the frontend folder locally.

---

## Project Status

**Stage 2 Functional Prototype – Project Viksit Bharat 2026**

Core features implemented and ready for demonstration.
