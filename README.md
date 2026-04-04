# AI-Powered Parametric Insurance for India’s Gig Delivery Workforce

## Phase 1 – Ideation & Foundation

This project proposes an **AI-powered parametric insurance platform** designed to protect gig delivery partners from **loss of income caused by external disruptions** such as heavy rain, pollution, strikes, or curfews.

Our solution strictly follows the challenge rule:  
This insurance covers **income loss only** — not health, accidents, or vehicle damage.

---

# Problem Overview

Delivery partners working with platforms like Zomato, Swiggy, Zepto, Amazon, etc. are essential to the digital economy. However, they face frequent income disruptions due to:

- Heavy rainfall
- Floods
- Extreme heat
- Pollution
- Strikes
- Sudden curfews
- Traffic shutdowns

These disruptions can reduce their working hours by **20–40%**, causing significant weekly income loss.

Current platform insurance mainly covers:
- Accidents
- Medical emergencies
- Disability

But **income protection during disruptions does not exist**.

---

# Current Insurance Landscape

Industry observations:

Estimated annual insurance spending by delivery companies:  
₹100 crore

Estimated delivery partners covered:  
~500,000 workers

Average insurance cost per worker:  
₹1,800 per year

Which equals approximately:  
₹35 per week per worker

This shows that insurance systems exist, but they do not protect workers from **loss of income due to disruptions**.

---

# The Gap We Are Solving

Problems with the current system:

- No coverage for weather disruptions
- No automated claims
- Slow verification
- Manual processes
- No real-time data integration

Our solution introduces:

- AI-powered risk assessment
- Parametric insurance triggers
- Automatic payouts
- Fraud-resistant architecture
- Weekly micro-insurance model

---

# Delivery Worker Persona

Name: Rahul  
City: Chennai  
Occupation: Food Delivery Partner  

Average earnings:  
₹600 – ₹800 per day  
₹4200 – ₹5000 per week

Common disruptions faced:

- Heavy monsoon rainfall
- Flooded roads
- Extreme heat
- Pollution spikes
- Political strikes

Example income loss:

Normal daily earnings: ₹700  
Rain disruption earnings: ₹300  

Loss:  
₹400 per day

---

# System Workflow

1. Worker registers on the platform.
2. AI generates a risk profile.
3. Weekly premium is calculated.
4. Worker activates insurance coverage.
5. System monitors environmental conditions in real time.
6. If disruption threshold is crossed, claim is triggered automatically.
7. Payout is processed instantly.

---

# Weekly Premium Model

Gig workers operate on weekly income cycles, so our insurance model uses weekly pricing.

Example Plans:

Basic Plan  
Premium: ₹25/week  
Coverage: ₹800

Standard Plan  
Premium: ₹40/week  
Coverage: ₹1500

Pro Plan  
Premium: ₹60/week  
Coverage: ₹2500

---

# Premium Calculation Logic

Weekly Premium =

Base Premium  
+ Rain Risk Score  
+ Pollution Risk Score  
+ Strike Probability  
− Safe Zone Discount

Example:

Base Premium = ₹20  
Rain Risk = ₹10  
Pollution Risk = ₹5  
Strike Risk = ₹8  
Discount = −₹3  

Final Premium = ₹40/week

---

# Parametric Triggers

Claims are triggered automatically when conditions cross thresholds.

Examples:

Heavy Rainfall  
Rainfall > 50 mm in 6 hours

Heatwave  
Temperature > 40°C

Severe Pollution  
AQI > 300

Flood Alerts  
Government alerts detected

Traffic Shutdown  
Traffic activity drops by 60%

Curfews or Strikes  
City operations halted

---

# Chennai Disruption Analysis

Chennai is a high-risk city for delivery disruptions.

Major affected zones include:

Velachery  
OMR  
Tambaram  
Perungudi  

Impact of heavy rainfall:

Delivery volume drops by 30–60%

Estimated income loss:  
₹400 – ₹700 per day

Pollution impact:

₹200 – ₹400 loss per day

Strikes / Curfews:

₹600 – ₹1000 loss per day

---

# AI / Machine Learning Integration

AI is used for three key functions.

## 1. Risk Prediction
Calculates risk level based on location and environmental data.

## 2. Dynamic Premium Pricing
Adjusts weekly premium according to disruption probability.

## 3. Fraud Detection
Identifies suspicious claims and coordinated fraud attacks.

AI inputs include:

Weather forecasts  
Pollution data  
Traffic conditions  
Delivery activity  
Historical disruptions

---

# AI Prototype (Google Colab Demonstration)

For Phase 1, we developed a **proof-of-concept AI simulation using Google Colab**.

The prototype demonstrates:

- Risk scoring system
- Premium calculation
- Fraud detection model
- Market crash simulation
- Suspicious claim detection

The simulation includes a dataset of worker claims and a model identifying fraudulent patterns.

---

# UI / UX Design

The platform includes two interfaces:

Worker Mobile Application  
Insurance Admin Dashboard

---

## Worker App Features

User registration  
Risk score display  
Weekly insurance purchase  
Coverage status tracking  
Disruption alerts  
Automatic claim notifications

Example UI Screen:

Risk Analysis

Location: Chennai  
Zone: Velachery  

Risk Score: 72  

Recommended Premium:  
₹40 per week  

Coverage:  
₹1500

---

## Admin Dashboard

Real-time claim monitoring  
Fraud detection alerts  
Risk analytics  
Disruption tracking

Example dashboard metrics:

Total Claims Today: 520  
Normal Claims: 32  
Suspicious Claims: 488  

Fraud Alert Triggered

---

# Phase 1 – Market Crash Scenario

## Adversarial Defense & Anti-Spoofing Strategy

A coordinated fraud ring involving **500 delivery partners** attempts to exploit the insurance system using GPS spoofing.

Our system uses **multi-layer fraud detection**.

---

# Fraud Detection Layers

Location Integrity Verification  
Movement Behavior Analysis  
Platform Activity Validation  
Environmental Data Verification  
Fraud Ring Detection  
AI Risk Scoring

---

# Fraud Ring Detection Logic

Signals that indicate fraud:

Multiple claims within seconds  
Identical GPS coordinates  
Same device fingerprints  
No delivery activity history  
Claim spikes in one zone

Example attack scenario:

500 claims submitted simultaneously.

System response:

Fraud alert triggered  
Suspicious claims paused  
AI pattern analysis executed  
Verified claims approved

---

# Fraud Risk Score

Fraud Score =

Location anomaly score  
+ Device risk score  
+ Behavior anomaly score  
+ Network cluster score

If Fraud Score > 70

Claim flagged for investigation.

---

# Distinguishing Genuine Workers

Genuine workers show:

Consistent delivery history  
Normal movement patterns  
Verified device activity  
Actual disruption exposure

Fraud accounts show:

GPS spoofing  
Clustered claims  
Unusual behavior  
Identical device signals

---

# Market Crash Protection System

If a mass fraud attack occurs:

Claim spike detected  
Fraud monitoring activated  
Suspicious claims isolated  
AI identifies coordinated fraud  
Genuine workers still receive payouts

This protects the insurance liquidity pool.

---

# Business Model

Example scenario:

10,000 workers join the platform.

Average weekly premium:  
₹40

Weekly revenue:  
₹4,00,000

Monthly revenue:  
₹16,00,000

Annual revenue:  
₹1.92 crore

Estimated payouts:  
40% of revenue

Estimated annual profit:  
~₹83 lakh

---

# Technology Stack

## Frontend (User Interface)

We focus on a simple, accessible, and scalable UI instead of AI-generated interfaces.

### Mobile App
Flutter or React Native

### Design Tools
Figma (UI/UX Design)  
Canva (Visual Prototypes)

### Web Dashboard
HTML  
CSS  
JavaScript  
React.js (optional for dashboard interface)

---

## Backend

Node.js or FastAPI

Handles:
- User management
- Insurance plans
- Claim processing
- Fraud detection integration

---

## AI / Machine Learning

Python

Libraries used:
- Scikit-learn
- Pandas
- NumPy

Used for:
- Risk prediction
- Premium calculation
- Fraud detection model

---

## Database

PostgreSQL

Stores:
- Worker profiles
- Risk scores
- Claims
- Fraud detection logs

---

## Cloud / Hosting

AWS or Firebase

Used for:
- Data storage
- API hosting
- Real-time monitoring

---

## APIs Used

Weather Data API  
Pollution (AQI) API  
Traffic Data API  
Mock Delivery Platform API  

These APIs help detect disruptions that trigger parametric insurance payouts.

---

## Payments (Simulation)

UPI payment simulator  
Razorpay sandbox environment

---

# Development Roadmap

Week 1  
Research and persona study

Week 2  
System design and UI prototypes

Week 3  
User onboarding implementation

Week 4  
Dynamic premium calculation

Week 5  
Fraud detection system

Week 6  
Analytics dashboard and optimization

---

# Phase 1 Deliverables

Idea documentation  
AI architecture plan  
Insurance model design  
Fraud detection strategy  
UI/UX prototypes  
Google Colab AI simulation

Demo Video (2 minutes):  
Explains the problem, solution, AI model, and fraud detection approach.

---

# Vision

Our goal is to build a **scalable parametric insurance infrastructure for the gig economy**, ensuring that delivery workers remain financially protected during unpredictable disruptions while maintaining a fraud-resistant system.



## Phase 2 – Automation & Protection

This phase transforms the Phase 1 concept into a fully working, deployed web application with live API integrations, real-time disruption monitoring, AI-powered risk scoring, zero-touch claims processing, and a complete admin dashboard.

Live Demo: https://farah10101.github.io/GigShield/

Built for Guidewire DEVTrails University Hackathon — Phase 2  
Theme: "Protect Your Worker"

---

# Problem Overview

India's 7.7 million gig delivery workers lose ₹400–₹1000 per day when rain, floods, heat, pollution, or strikes halt operations. Traditional insurance does not cover income loss from environmental disruptions.

Disruption types and their impact:

Rain / Flood  
Delivery volume drops by 30–60%  
Estimated income loss: ₹400–₹700 per day

Extreme Heat  
Delivery volume drops by 20–40%  
Estimated income loss: ₹200–₹400 per day

Severe Pollution  
Delivery volume drops by 15–35%  
Estimated income loss: ₹200–₹400 per day

Strike / Curfew  
Delivery volume drops by 60–100%  
Estimated income loss: ₹600–₹1000 per day

Existing coverage options for income disruption: Zero.

---

# Phase 2 Deliverables

---

## 1. Registration Process

Workers register in under 2 minutes by entering:

- Full name and phone number
- City and delivery zone
- Delivery platform (Swiggy, Zomato, Zepto, Amazon, Blinkit, Dunzo)
- Average daily and weekly income
- Preferred insurance plan

Upon registration, the system instantly fetches live weather data from Open-Meteo API, live AQI data from the AQI API, and live temperature data. It then generates a personalized AI risk score and calculates a dynamic weekly premium based on real-time environmental conditions in the worker's zone.

---

## 2. Insurance Policy Management

Three weekly micro-insurance plans are available:

Basic Plan  
Premium: ₹25/week  
Coverage: ₹800  
Features: Rainfall protection, UPI payout, 24-hour claim processing

Standard Plan  
Premium: ₹40/week  
Coverage: ₹1500  
Features: Rainfall, flood and heat coverage, instant claim processing, UPI and bank payout, AI risk alerts

Pro Plan  
Premium: ₹60/week  
Coverage: ₹2500  
Features: All disruption types, strike and curfew coverage, priority processing, AI risk alerts and forecast

Workers can view their active plan, coverage amount, weekly premium, and live risk score from their personal dashboard at any time.

---

## 3. Dynamic Premium Calculation

The weekly premium is calculated in real time using live environmental data from public APIs.

Premium Calculation Formula:

Base Premium = ₹20  
Rain Risk Score (Live weather data) = ₹10  
Pollution Risk (Live AQI data) = ₹5  
Heat Risk (Live temperature data) = ₹3  
Safe Zone Discount = −₹3  

Final Weekly Premium = ₹40/week

The premium updates dynamically based on the worker's city and zone. A worker registered in a high-risk rain zone pays a higher premium than one in a historically safer zone.

---

## 4. Claims Management

Claims are triggered automatically when live environmental data crosses predefined parametric thresholds. There is no paperwork, no manual filing, and no phone calls required.

Parametric Thresholds:

Heavy Rainfall — Rainfall exceeding 50 mm in 6 hours  
Heatwave — Temperature exceeding 40 degrees Celsius  
Severe Pollution — AQI exceeding 300  
Flood Alert — Government flood alert issued  
Traffic Shutdown — Traffic activity drops by more than 60%  
Strike or Curfew — City operations halted

Automated Claim Flow:

Step 1 — Disruption detected via live API data  
Step 2 — Threshold verified against parametric rules  
Step 3 — Fraud check completed by AI model  
Step 4 — Payout processing initiated  
Step 5 — UPI transfer completed within approximately 4 minutes

Workers can track their claim status live through the Claims page on the platform.

---

# Live API Integrations

Five automated triggers are built using public APIs:

Open-Meteo API  
Used for: Real-time rainfall data  
Triggers: Heavy Rainfall claim

AQI API  
Used for: Live Air Quality Index  
Triggers: Severe Pollution claim

Open-Meteo API  
Used for: Live temperature readings  
Triggers: Heatwave claim

Government Flood Alert Feed  
Used for: Active official flood alerts  
Triggers: Flood claim

Traffic Data API  
Used for: Real-time traffic volume percentage drop  
Triggers: Traffic Shutdown claim

All five triggers are monitored continuously and displayed on both the worker dashboard and the admin panel with live status indicators.

---

# AI and Machine Learning Integration

AI is used for three key functions in Phase 2.

## 1. Live Risk Scoring

On registration, the system fetches real-time data for the worker's zone and generates a risk score from 0 to 100, broken down into:

Rain Risk — based on live rainfall probability  
AQI Risk — based on live air quality index  
Heat Risk — based on live temperature data

## 2. Dynamic Premium Pricing

The premium engine adjusts the weekly premium in real time based on the live risk score. Workers in higher-risk zones pay slightly more, while workers in historically safe zones receive a discount.

## 3. Fraud Detection

Multi-layer AI fraud detection keeps the system fair for genuine workers.

Genuine worker signals:  
- Consistent delivery history  
- Normal movement patterns  
- Verified device activity  
- Real disruption exposure confirmed

Fraud detection signals:  
- GPS spoofing detected  
- Clustered claims from the same coordinates  
- Unusual behavior patterns  
- Identical device fingerprints

Fraud Score Formula:

Fraud Score =  
Location Anomaly Score  
+ Device Risk Score  
+ Behavior Anomaly Score  
+ Network Cluster Score  

If Fraud Score exceeds 70, the claim is flagged for investigation.

---

# Chennai Disruption Analysis

Chennai is a high-risk city for delivery disruptions. The platform tracks four major zones:

Velachery  
Risk Score: 72  
Rain risk: 85%  
Estimated income loss: ₹400–₹700/day

Perungudi  
Risk Score: 65  
Rain risk: 80%  
Estimated income loss: ₹400–₹700/day

OMR  
Risk Score: 58  
Traffic risk: 70%  
Estimated income loss: ₹300–₹600/day

Tambaram  
Risk Score: 55  
Rain risk: 70%  
Estimated income loss: ₹350–₹650/day

---

# Admin Dashboard

The admin dashboard provides a full operations overview for the Chennai region.

Summary metrics:

Total Workers: 10,247  
Active Policies: 8,134  
Claims Today: 520  
Normal Claims: 32  
Suspicious Claims: 488  
Payouts Today: ₹42,000

The dashboard includes a claims trend chart across the week, a disruption type breakdown (Rainfall 60%, Flood 20%, Pollution 10%, Strike 7%, Heat 3%), live fraud alerts with scores and flags, and real-time disruption trigger status across Chennai zones.

---

# Fraud Detection — Example Alerts

Anonymous Cluster A  
Zone: OMR  
Fraud Score: 91 — Confirmed  
Signals: 488 claims from same coordinates, identical device hashes, no delivery history for 72 hours

Suspicious Account D  
Zone: Velachery  
Fraud Score: 82 — Under Investigation  
Signals: GPS spoofing detected, claims submitted within 3 seconds of trigger, device fingerprint matched 14 others

Account X  
Zone: Tambaram  
Fraud Score: 45 — Cleared  
Signals: Unusual claim timing, low delivery volume week

---

# Business Model

Example scenario with 10,000 workers on the platform:

Average weekly premium: ₹40  
Weekly revenue: ₹4,00,000  
Monthly revenue: ₹16,00,000  
Annual revenue: ₹1.92 crore  
Estimated payouts (40% of revenue): ₹76.8 lakh  
Estimated annual profit: approximately ₹83 lakh

---

# Technology Stack

## Frontend

HTML, CSS, JavaScript  
Deployed via GitHub Pages  
Live URL: https://farah10101.github.io/GigShield/

## APIs Used

Open-Meteo API — Live weather and temperature data  
AQI API — Live air quality index  
Traffic Data API — Real-time traffic volume  
Government Flood Alert Feed — Official flood alerts  
UPI Payment Simulator — Instant payout simulation

## AI and Machine Learning

Python-based risk scoring engine  
Dynamic premium calculator  
Multi-layer fraud detection model

## Database

Worker profiles  
Risk scores  
Claims records  
Fraud detection logs

---

# How to Run Locally

Clone the repository:

git clone https://github.com/farah10101/GigShield.git

Open index.html in your browser. No backend setup is required as all APIs are called client-side.

---

# Phase 2 Checklist

Registration Process — Implemented  
Insurance Policy Management — Implemented  
Dynamic Premium Calculation — Implemented with live APIs  
Claims Management — Implemented with zero-touch automation  
AI Risk Scoring — Implemented with live environmental data  
AI Fraud Detection — Implemented with multi-layer scoring  
Automated Triggers (5 public APIs) — Implemented  
Zero-touch claim UX — Implemented with 5-step automated flow  
Admin Dashboard — Implemented  
Executable source code — Available on GitHub  
2-minute demo video — Recorded

---

# Vision

Our goal is to build a scalable parametric insurance infrastructure for the gig economy, ensuring that delivery workers remain financially protected during unpredictable disruptions while maintaining a fraud-resistant, fully automated system.
