# Net-Grid-Replacement-Needs

A forecasting and investment strategy model for **net new powerplant build-out in the United States** over the next 20 years.  
This project was developed during a hackathon challenge focused on using **AI Deep Research techniques** to analyze future grid requirements and investment opportunities.  

---

## 🌍 Problem Statement
Future U.S. energy demand can be estimated, but the **net new replacement capacity**, the amount of power that must be added each year to meet new demand and replace retiring assets, remains unclear.  

Our model tackles this challenge by accounting for:
- Growth in regional energy demand  
- Retirement of aging power plants  
- Construction timelines for new generation assets  
- Downtime and reliability reserves  

We package these findings into an **investment strategy** for a large institutional investor with $10B+ in deployable capital.  

---

## 📊 Methodology
### 1. Forecasting Framework
- **Demand Growth**: Estimated from historical regional usage, population trends, industrial shifts, and climate adaptation.  
- **Asset Retirement**: Modeled using in-service dates and expected lifetimes by technology type.  
- **Technology Mix**: Evaluated across solar, wind, nuclear, natural gas, and storage for both ROI and reliability.  
- **Risk Analysis**: Identified risks from policy reversals, economic shocks, and technology disruptions.  

### 2. Quantitative Model
We created a regional and temporal breakdown of net new capacity requirements:  
- **Years 1–5**: Immediate build out to replace coal retirements and stabilize grid reliability.  
- **Years 6–10**: Scaling of renewables and storage with continued gas backup.  
- **Years 11–20**: Long-term growth dominated by nuclear, advanced storage, and next-gen solar/wind.  

---

## 📈 Key Deliverables
1. **Quantitative Forecasting Model**  
   - Net new capacity required by **technology, region, and timeline (1–5, 6–10, 11–20 years)**.  

2. **Asset Retirement Visualization**  
   - Geographic distribution and retirement trajectories.  
   - Interactive tool available here: 👉 [Power Plant Retirements Visualization](https://chp36.github.io/power_plant_retirements/)  

3. **High Potential Investment Categories**  
   - **Utility Scale Solar + Storage**  
   - **Onshore & Offshore Wind**  
   - **Next Gen Nuclear & SMRs**  

   Each includes:
   - Capital deployment timelines  
   - ROI ranges under scenarios  
   - Risk factors and mitigation  
   - Competitive landscape  

4. **Investment Portfolios**

We propose two sample portfolios for a large investor with $10B+ in deployable capital.  

#### **Portfolio A: Transition Backbone Strategy (55% Allocation)**
- **Focus**: Utility-scale generation and storage projects  
- **Expected ROI**: **9.5–12.5%** driven by Solar PV, Storage, and Onshore Wind  
- **Strengths**: Stable returns, core infrastructure focus, scalable projects  
- **Risks**: Technology obsolescence, material supply constraints  

#### **Portfolio B: Distributed Resilience Strategy (45% Allocation)**
- **Focus**: Distributed resources and customer-level (behind-the-meter) storage  
- **Expected ROI**: **11–16%** driven by high-margin consumer technology providers  
- **Strengths**: Faster growth, exposure to consumer adoption trends, higher margins  
- **Risks**: Local regulatory hurdles, uneven adoption rates across regions  


5. **Performance Dashboard**  
   - Built in **Lovable** for real-time portfolio tracking.  
   - Monitors: ROI, grid reliability, capacity growth, retirement coverage.  
   - Live version: 👉 [Grid Performance Lens Dashboard](https://grid-performance-lens.lovable.app/)  

---

## 🗂 Project Structure

├── data/ # Regional demand & retirement datasets
├── notebooks/ # Forecasting & modeling notebooks
├── models/ # Net new build out forecasting logic
├── visualizations/ # Charts, graphs, and dashboard exports
├── README.md # Project overview (this file)


---

## 🚀 How to Use
1. Explore the **retirement visualization**:  
   [Power Plant Retirements](https://chp36.github.io/power_plant_retirements/)  
2. Monitor investment strategy via the **dashboard**:  
   [Grid Performance Lens](https://grid-performance-lens.lovable.app/)  
3. Adapt the model for custom scenarios by modifying assumptions in `/models/`.

 ---
 
## 👥 Team
Developed during the Hackathon Sprint by a cross-functional team of  engineer, analyst and business students.  

---
