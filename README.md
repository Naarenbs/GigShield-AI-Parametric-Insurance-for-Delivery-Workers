#  AI-Powered Parametric Insurance for Gig Workers in India
### *Theme: Ideate & Know Your Delivery Worker*

---

## Project Overview

This project proposes an **AI-powered parametric insurance platform** designed to protect gig delivery workers from **income loss caused by environmental disruptions** such as extreme weather, pollution, and natural disasters.

Delivery partners working with platforms like Zomato, Swiggy, Zepto, Amazon, and Dunzo rely on daily work to earn. When disruptions occur, their income drops significantly.

Our solution provides **automatic income protection using AI and parametric triggers**, ensuring financial stability without manual claims.

---

## Problem Statement

Gig workers face frequent disruptions due to:

- Heavy rainfall
- Severe air pollution
- Extreme heat
- Natural disasters

These factors reduce their working hours, causing **20–30% income loss weekly**.

### Current Challenges:
-  No income protection exists
-  No insurance covers environmental income loss
-  Workers bear full financial risk

---

##  Delivery Worker Persona

**Name:** Raj Kumar
**City:** Delhi
**Platform:** Swiggy
**Weekly Income:** ₹5500

### Challenges:
- Pollution reduces working hours
- Rain slows deliveries
- Income is unpredictable

### Scenario:
During high pollution (AQI > 400), Raj works only 3 days instead of 6 days.
He loses around ₹2500 in a week.

Our platform detects this disruption and provides **automatic compensation**.

---

## Application Workflow

1. **Onboarding**
   - User registers via mobile app
   - Inputs basic details (income, location, platform)

2. **Risk Profiling**
   - AI analyzes environmental risks using weather and pollution data

3. **Policy Creation**
   - Weekly insurance plan generated based on income

4. **Trigger Detection**
   - System monitors environmental conditions continuously

5. **Fraud Check**
   - AI validates user activity and location

6. **Payout Processing**
   - Automatic compensation via UPI/bank transfer

---

## Weekly Premium Model

Premium is designed to match **weekly earnings cycle**.

### Pricing Logic:
Premium ≈ **1% of weekly income**

### Sample Plans:

| Plan | Weekly Income Covered | Weekly Premium | Max Payout |
|------|---------------------|---------------|-----------|
| Basic | ₹3000 | ₹30 | ₹600 |
| Standard | ₹5000 | ₹50 | ₹1000 |
| Premium | ₹8000 | ₹80 | ₹1600 |

---

##  Parametric Triggers

Claims are triggered automatically when conditions are met:

| Event | Trigger Condition |
|------|------------------|
| Heavy Rain | Rainfall > 60 mm |
| Extreme Heat | Temperature > 45°C |
| Severe Pollution | AQI > 350 |
| Disaster Alerts | Flood/Cyclone warning |

No manual claims required — **fully automated system**

---

##  Platform Justification (Why Mobile App?)

-  Gig workers primarily use smartphones
-  Quick onboarding and instant access
-  GPS-based verification
-  Real-time notifications for payouts

A mobile-first approach ensures **ease of use and accessibility**.

---

## AI/ML Integration

### 1. Risk Prediction
- Predicts environmental disruption probability
- Models: Random Forest / Gradient Boosting

### 2. Premium Optimization
- Adjusts pricing based on location risk

### 3. Income Loss Estimation

$$
\text{Loss} = \left(\frac{\text{Weekly Income}}{7}\right) \times \text{Disruption Days}
$$

### 4. Fraud Detection
- Detects anomalies using behavior patterns
- Model: Isolation Forest

---

##  How We Built It (Step-by-Step)

1. Problem research and analysis
2. System architecture design
3. Mobile UI development (React Native)
4. Backend APIs (Node.js, Express)
5. Database setup (MongoDB)
6. Environmental data integration
7. AI model implementation
8. Parametric trigger engine
9. Automated payout system
10. Testing and optimization

---

##  Tech Stack

- **Frontend:** React Native
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI/ML:** Python, Scikit-learn, TensorFlow
- **APIs:** Weather API, Pollution API
- **Payments:** Razorpay / UPI
- **Cloud:** AWS / Google Cloud

---

##  Development Plan

### Phase 1: Ideation & Design
- Problem research
- Architecture design

### Phase 2: Prototype
- Basic app (onboarding + policy creation)
- Trigger simulation

### Phase 3: AI Integration
- Risk prediction
- Fraud detection

### Phase 4: Deployment
- Payment integration
- Dashboard

---

##  Analytics Dashboard

### Worker Metrics
- Total insured workers
- Active policies

### Risk Metrics
- High-risk cities
- Environmental alerts

### Financial Metrics
- Weekly premiums collected
- Total payouts
- Claim ratio

---

##  Future Enhancements

-  Integration with gig platforms
-  Real-time risk heatmaps
-  Advanced AI models
-  Expansion across India
-  Dynamic pricing system


## Final Note

This solution bridges the gap between **technology, insurance, and social impact**, ensuring that gig workers are **financially protected even during unpredictable environmental conditions**.
