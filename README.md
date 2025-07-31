# **EcoTrack: Real-Time Carbon Footprint Tracker**  

EcoTrack is a web application that helps users monitor and reduce their daily carbon footprint by analyzing transportation, energy usage, and diet choices.  

By combining **machine learning**, **real-time data visualization**, and **personalized recommendations**, EcoTrack empowers users to make greener lifestyle decisions.

---

## **Table of Contents**
1. [Features](#features)  
2. [How It Works](#how-it-works)  
3. [Why It Matters](#why-it-matters)  
4. [Tech Stack](#tech-stack)  
5. [Installation](#installation)  
6. [Usage](#usage)  
7. [Example Output](#example-output)  
9. [Contributors](#contributors)

---

## **Features**
- **Live Carbon Tracking** – Calculates your footprint based on daily habits like commuting and meals.  
- **Data Visualization** – Interactive charts showing weekly and monthly trends.  
- **Personalized Recommendations** – Suggests eco-friendly alternatives to reduce emissions.  
- **Goal Tracking** – Users can set emission reduction targets and track progress.  

---

## **How It Works**
1. **User Input**: Users log their daily activities (commute type, electricity usage, meals).  
2. **Data Processing**:  
   - Python backend calculates approximate CO₂ emissions per activity.  
   - ML model predicts future emissions based on past behavior.  
3. **Visualization**: React frontend displays graphs and personalized advice.  
4. **Recommendations**: Suggests actionable tips like “bike instead of bus twice a week.”  

---

## **Why It Matters**
- **Climate change** is one of the most urgent challenges of our time.  
- Most people **underestimate** their personal carbon footprint.  
- EcoTrack bridges the gap by providing **awareness + actionable steps** to reduce environmental impact.  

---

## **Tech Stack**
- **Frontend:** React, Tailwind CSS  
- **Backend:** Python (Flask)  
- **Database:** PostgreSQL  
- **Machine Learning:** Scikit-learn  
- **Hosting:** Render (backend) & Vercel (frontend)  
- **APIs:** OpenWeather API for real-time conditions affecting emissions  

---

## **Installation**

Clone the repository:  

git clone https://github.com/username/ecotrack.git

## Usage
1. Create an account.
2. Log daily activities.
3. Review your carbon dashboard.
4. Follow personalized tips and adjust goals.

---

## Example Output
**Weekly Carbon Dashboard**

| Activity        | CO2 Emissions (kg) |
|-----------------|--------------------|
| Transportation  | 14.2               |
| Energy Usage    | 8.6                |
| Diet            | 5.3                |
| **Total**       | **28.1**           |

> “Switching two short car rides to biking this week could reduce your footprint by 9%.”

---

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. All contributions are welcome. Start with issues labeled **good first issue**.

---

## Roadmap
- Mobile app wrapper  
- IoT-enabled automatic activity detection  
- Social sharing and eco-challenges  
- Gamified badges for milestones  

---

## License
This project is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for details.

---

## Contributors
- **Aisha Rahman** – Backend & ML  
- **Miguel Hernandez** – Frontend & Design  
- **Priya Kapoor** – API Integration & Data Visualization  
