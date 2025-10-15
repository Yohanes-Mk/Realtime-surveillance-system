# Real-Time Surveillance and Analytics System

### Origin & Purpose
This project began during my time as a **Public Safety Officer at St. Cloud State University**, where I observed firsthand how manual surveillance and delayed alerts often limited response time in real-world situations.  
I started building this system as a way to **automate incident detection**—reducing monitoring load and improving safety awareness.  
Now, as part of my ongoing work at **Allied Universal**, I’m continuing to refine it into a scalable, AI-assisted surveillance tool that could be adapted to residential or campus security operations.


## Problem
Manual surveillance monitoring is inefficient and prone to human error.  
Existing camera systems rarely provide automatic alerts for falls, crowding, or abandoned objects, which leads to delayed response and safety risks.

## Approach
Develop an AI-driven, multi-camera system that performs:
- Real-time person and posture detection using **OpenCV** and **Mediapipe**
- Object and anomaly tracking through a **Flask** backend
- Data visualization and alerts via **Streamlit** dashboards and automated notifications
- Containerized deployment with **Docker** for scalability

## Tech Stack
`Python`  |  `OpenCV`  |  `Mediapipe`  |  `Flask`  |  `Streamlit`  |  `SQLite`  |  `Docker`

## Expected Outcome
A functional prototype capable of:
- Processing live video feeds at < 1 s latency  
- Sending automatic alerts for posture anomalies and abandoned objects  
- Providing dashboards with heatmaps and trend analytics

## Repository Structure (Initial Phase)
