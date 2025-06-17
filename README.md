# 🚨 Incident Detection System for Public Safety

This project presents an **IoT-based intelligent surveillance system** designed to enhance public safety by automatically detecting **fires, accidents, and theft incidents** in real-time. Using a **Raspberry Pi 3 B+** with a **Raspberry Pi Camera V2**, the system captures images at regular intervals and classifies them using a fine-tuned **VGG16 deep learning model**.

When an incident (fire, accident, or theft) is detected, the system sends **instant SMS alerts** to registered emergency contacts via the **Twilio API**, enabling rapid response and reducing reliance on manual monitoring.

---

## ✅ Key Features

- 🔥 **Fire Detection:** Real-time fire identification with automated notifications.
- 🚗 **Accident Detection:** Detects road accidents and sends immediate alerts.
- 🏃 **Theft Detection:** Recognizes suspicious theft activities for enhanced security.
- 📡 **Low-Cost & Scalable:** Uses affordable hardware for urban and rural deployment.
- 📲 **Instant SMS Alerts:** Sends SMS via Twilio to authorities or managers.
- ⚙️ **Edge Processing:** Runs deep learning locally on Raspberry Pi, reducing cloud dependency.

---

## ⚙️ How It Works

1. **Image Capture:** Raspberry Pi Camera V2 captures images at regular intervals.
2. **Incident Classification:** Captured images are classified as *fire*, *accident*, *theft*, or *normal* by the VGG16 model.
3. **Real-Time Alerts:** If an incident is detected, an SMS with details is sent instantly to registered contacts.

---

## 💡 Innovation Highlights

- Combines **IoT, deep learning, and computer vision** for real-time safety monitoring.
- Cost-effective, low-power, and easily deployable in remote or under-monitored areas.
- Automatically sends alerts without the need for human supervision.
- Can be scaled to monitor multiple areas using multiple Raspberry Pi setups.

---
- [Dataset Used](https://drive.google.com/drive/folders/1jIPBKXk_n3OHwYnqos5j9TrnKuaPn1Vb?usp=sharing)

---

