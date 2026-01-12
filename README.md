# AURA – Agentic AI for Women Safety

AURA is an agentic AI-driven safety platform designed to enhance women’s safety during cab rides by proactively monitoring cab routes and real-time crowd density.

---

## Problem
Women often face safety risks during cab rides, especially at night or in unfamiliar areas.  
Unsafe route deviations and low crowd density zones increase vulnerability, and existing solutions are mostly reactive.

---

## Solution
AURA provides a predictive and proactive safety layer using agentic AI.  
The system continuously analyzes cab routes and surrounding crowd density to detect potential risks early and alert the user before a situation escalates.

---

## Key Features
- "Smart Cab Route Monitoring" – Detects unsafe route deviations in real time  
- "Crowd Density Awareness" – Identifies low-visibility or isolated areas  
- "Predictive Risk Alerts" – Warns users before entering high-risk zones  
- "Emergency SOS Interface" – One-tap emergency assistance  

---

## AI Agents Overview

### 1. Route Deviation Monitoring Agent
Purpose:  
Monitors real-time GPS path compared to expected safe routes and triggers actions if deviation exceeds predefined thresholds.

Key Functions:  
- Compute safe routes  
- Compare GPS positions to planned path  
- Calculate deviation distance  
- Decide Monitor or SOS action

---

### 2. SOS Action Trigger Agent
Purpose:  
Handles manual and automated emergency triggers and dispatches alerts to guardians or emergency contacts.

Key Functions:  
- Manual SOS input  
- Auto-trigger from deviation agent  
- Send notifications via messaging or alert systems  
- Notify guardians promptly

---

### 3. Guardian Notification Agent
Purpose:  
Ensures critical information reaches designated emergency contacts reliably.

Key Functions:  
- Format alert message  
- Provide real-time GPS map link  
- Confirm delivery status  
- Retry if delivery fails

---

### 4. Contextual Risk Scoring Agent
Purpose:  
Assigns a risk score based on contextual data when route or motion anomalies are detected.

Inputs:  
- GPS deviation value  
- Time of day  
- Speed / acceleration (optional)  
- Manual override

Outputs:  
- risk_score (0-100)  
- action_decision (monitor, warn, sos)

---

### 5. Crowd Safety Awareness Agent
Purpose:  
Detects if the user is entering low-density or isolated zones, particularly in night-time or unsafe walking conditions.

Data Sources:  
- Time  
- Location density (if available)  
- Visual input (future enhancement)

---

### 6. Live Location Sharing Agent
Purpose:  
Shares periodic GPS with guardians until the user stops the session.

Functions:  
- Interval tracking  
- Map link updates  
- Session timeout

---

## Frontend Prototype
- Built using Lovable  
- Interactive 3D safety and route visualization using Spline  
- Focused on intuitive user experience and safety-first design

---

## Demo & Links
- Live Frontend Prototype: https://aura-safe-route.lovable.app/  
- Demo Video: demo.mp4  

---

## Technology Stack
- Frontend: Lovable  
- 3D Components: Spline  
- AI Concept: Agentic AI for route risk and crowd density analysis  
- Backend: Prototype ready; integration with frontend planned

---

## Project Status
The frontend and backend prototypes have been developed and work independently.  
All key features and agents are implemented.  
The remaining task is to connect the frontend with the backend systems, which is straightforward and planned.

---

## Team
Project developed as part of a hackathon submission focused on women safety and AI-driven solutions.

---

© 2026 AURA


