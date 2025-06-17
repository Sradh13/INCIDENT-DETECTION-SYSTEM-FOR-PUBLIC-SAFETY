**Incident Detection System for Public Safety**

This project presents an IoT-based intelligent surveillance system designed to enhance public safety by automatically detecting fires, accidents, and theft incidents in real-time. Using a Raspberry Pi 3 B+ equipped with a Raspberry Pi Camera V2, the system captures images at regular intervals and classifies them using a VGG16 deep learning model fine-tuned for multi-class incident detection.

When an incident (fire, accident, or theft) is identified, the system sends instant SMS alerts to registered emergency contacts via the Twilio API, enabling rapid response and minimizing potential losses. This reduces reliance on manual monitoring and ensures faster emergency intervention.







 **Key Features**
 
**.Fire Detection:** Real-time identification of fire incidents with automated alerts.

**.Accident Detection:** Detection of road accidents and immediate notification.

**.Theft Detection:** Recognition of theft activities for enhanced security.

**.Low-cost, scalable IoT solution:** Uses affordable hardware, making it practical for urban and rural areas.

**.Instant Notifications:** SMS alerts to authorities or responsible personnel using Twilio API.

**.Edge Processing:** Runs deep learning models locally on Raspberry Pi, reducing latency and cloud dependency.







**How It Works**

**Image Capture:** Raspberry Pi Camera V2 captures images at set intervals.

**Incident Classification**: Images are processed locally by the VGG16 model to classify them as fire, accident, theft, or normal.

**Real-Time Alerts**: If an incident is detected, an SMS with incident type and (optionally) location coordinates is sent to pre-registered contacts.







**Innovation**

This project demonstrates how IoT, computer vision, and deep learning can be combined to create an automated, cost-effective safety monitoring solution — with applications ranging from street surveillance and smart city safety to rural area monitoring and building security.

