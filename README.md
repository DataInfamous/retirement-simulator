# 📊 RetireCast  
### Monte Carlo Retirement Forecast Dashboard

An interactive financial modeling dashboard that simulates thousands of possible market outcomes to estimate long-term retirement growth.

This project brings Monte Carlo simulation into a simple, real-time tool that allows users to explore how contributions, market conditions, inflation, and withdrawal strategies affect retirement outcomes.

---

## 🚀 Live App

👉 https://retirecast.netlify.app/

---

## 🧠 Project Overview

Most retirement calculators assume a fixed average return. In reality, markets are unpredictable.

This tool models that uncertainty by running **10,000 simulated market paths** and showing a range of possible outcomes instead of a single number.

Users can interact with the model directly and see how different assumptions impact long-term results.

---

## 🔗 Concept Model

This application is built from a separate modeling-focused repository:

👉 https://github.com/DataInfamous/monte-carlo-retirement-simulator

That repo focuses on:
- The simulation logic  
- Statistical modeling  
- Monte Carlo methodology  

This repo focuses on:
- The interactive dashboard  
- User inputs  
- Visualization of results  

---

## ⚙️ Key Features

### 🔧 Customizable Financial Inputs

Users can adjust:

- Annual contributions  
- Inflation assumptions  
- Safe withdrawal rate  
- Time horizon  

All changes update the simulation instantly in the browser.

---

### 📊 Scenario Selection

Users can switch between different market assumptions:

- Bear  
- Base  
- Bull  
- Optimistic  
- Historical (S&P 500-based)  

Each scenario adjusts expected return (μ) while keeping volatility modeled.

---

### 🔁 Monte Carlo Simulation

- Runs **10,000 simulations**
- Models randomness in market returns
- Captures sequence-of-returns risk
- Includes both:
  - Standard return modeling  
  - Bootstrapped-style sampling  

---

### 📈 Distribution of Outcomes

Instead of a single prediction, the dashboard shows:

- Mean outcome  
- Median outcome  
- 10th percentile (downside)  
- 25th percentile  
- 75th percentile  
- 90th percentile (upside)  

---

### 💸 Annual Withdrawal Capacity

The model includes a **safe withdrawal rate input**:

- Default based on the 4% rule  
- Adjustable by the user  
- Helps estimate sustainable retirement income  

---

### 🧮 Inflation-Adjusted Values

Results are shown in:

- Future (nominal) dollars  
- Inflation-adjusted (real) dollars  

This helps translate results into actual purchasing power.

---

### ⚡ Runs Fully in the Browser

- No backend  
- No data storage  
- Instant recalculation  
- Everything stays local to the user  

---

## 🧪 Example Assumptions (Base Scenario)

- Expected return (μ): 5.8%  
- Volatility (σ): 16%  
- Inflation: ~2.9%  
- Time horizon: 2026–2050  

---

## ⚠️ Limitations

- Tax treatment is simplified across account types  
- Market returns are modeled, not predicted  
- Results are probabilistic, not guarantees  

This tool is meant for **exploration and education**, not financial advice.

---

## 🤖 Development Approach

This project was built using an AI-assisted workflow.

I designed the concept, structure, and modeling approach, and used AI as a tool to help implement, refine, and iterate on the system.

Think of it as working with a teammate — not outsourcing the project.

---

## 🎯 Purpose

This project was created to:

- Explore probabilistic financial modeling  
- Demonstrate Monte Carlo simulation in a real application  
- Build a portfolio project combining data science + UI  
- Create something others can actually use  

---

## 👤 Author

**Benjamyn Wilson**  
Data Science Student  
Financial Modeling & Simulation Projects
