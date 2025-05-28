# Reduce Ambulance Waiting Time for Manhattan with Optimized Ambulance Dispatches

This repository documents our project from the MIT Sloan Optimization Methods Course (15.093), where we developed a dispatch optimization model for emergency medical services (EMS) in Manhattan.

## Project Overview

We developed three models to improve EMS response times under real-world constraints:
- A **Min-Sum model** that minimizes total response time
- A **Min-Max model** that ensures equity by minimizing the worst-case time
- A **Robust model** that handles demand and capacity uncertainty

We performed sensitivity analysis to provide staffing susgestions to key staions and spotted underserved areas such as China Town and Soho (10013)

The goal: provide actionable, equitable EMS dispatch recommendations to reduce ambulance waiting time in Manhattan, NYC.

## Video Demonstration
https://github.com/user-attachments/assets/6ea1977c-5338-409d-a0c3-3c32deb50dc7

## Methods
- **Min-Sum Model**: Minimizes total response time across all incidents.
- **Min-Max Model**: Minimizes the worst-case response time for equitable distribution.
- **Robust Optimization**: Incorporates demand and capacity uncertainty to improve system resilience.
- **Sensitivity Analysis**: Identifies bottlenecks where increasing capacity improves system performance.

## Key Insights
- The **Min-Sum model** achieves the lowest average response time but lacks equity.
- The **Min-Max model** ensures fairness with longer wait times.
- **Robust models** improve resilience at the cost of slightly higher average times.
- **Sensitivity analysis** reveals that increasing capacity at key nodes significantly improves system efficiency.

## Team
Ellie Yang, Naiqi Zhang, Sneha Sathish Kumar  
Developed as part of MIT Sloan's Optimization Methods Course (15.093)
