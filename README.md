# Infrastructure Capital Decision Dashboard  
### Repair vs. Replace Framework for Data Center Assets

## Overview
This project is an interactive decision framework designed to help organizations determine when to continue repairing infrastructure assets versus when to replace them.

It combines financial thresholds and reliability signals to identify asset-level “tipping points,” enabling more proactive and cost-effective capital planning.

---

## Live Demo
https://mezd-dev.github.io/infrastructure-replacement-decision-framework/

---

## Problem
Infrastructure teams often fall into reactive repair cycles, continuing to invest in aging equipment without clear thresholds for replacement.

This leads to:
- Rising maintenance costs
- Increased failure risk
- Operational inefficiencies
- Higher likelihood of costly outages

---

## Solution
This framework introduces a structured, data-driven approach to decision-making using two key dimensions:

- **Financial Threshold:**  
  When cumulative repair costs approach a percentage of replacement cost

- **Reliability Signal:**  
  High repair frequency indicating recurring failures and operational strain

---

## Decision Logic
Assets are evaluated using:

- **Repair-to-Replacement Ratio (R/R)**  
  (Cumulative Repair Cost / Replacement Cost)

- **Repair Frequency**

### Core Triggers:
- **Replace:**  
  R/R ≥ 75%

- **Reliability Override:**  
  R/R ≥ 60% AND Repair Count ≥ 8

These rules help identify assets that are no longer cost-effective to maintain.

---

## Key Features
- Portfolio-level asset segmentation (Stable / Monitor / Replace)
- Tipping point visualization (cost vs. repair frequency)
- Replacement prioritization based on capital exposure
- Interactive simulator for adjusting decision thresholds
- Business-focused insights designed for leadership decision-making

---

## Tools & Technologies
- Power BI (dashboard development)
- Python (data preparation and transformation)
- HTML/CSS (interactive simulator)
- GitHub Pages (deployment)

---

## Project Structure

---

## Business Impact
This framework shifts organizations from reactive maintenance to proactive capital planning by:

- Reducing unnecessary repair spend  
- Improving asset reliability  
- Supporting long-term infrastructure investment decisions  
- Minimizing risk of high-cost outages  

---

## Notes
This project uses a representative dataset for demonstration purposes and is designed as a plug-and-play framework that can integrate with real asset management systems.

---

## Author
- Mezmure Dawit
- LinkedIn: https://www.linkedin.com/in/mezd/
