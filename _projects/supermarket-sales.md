---
layout: page
title: Dynamic Sales Prediction Engine
description: End-to-end decision intelligence platform combining Meta's Prophet forecasting and PuLP linear optimization for retail inventory.
importance: 1
category: "Machine Learning & Dashboards"
github: Pablo-Santana-MX/supermarket-sales-prediction
---

## 🛒 End-to-End Decision Intelligence
Supermarket branches generate massive volumes of daily data but often fail to translate historical information into actionable commercial strategies. This project applies the Scientific Method to business operations, answering a critical research question: *How can we mathematically project 30-day demand and utilize that prediction to maximize inventory ROI, subject to real-world physical and financial constraints?*

## 📊 Live Interactive Dashboard
*Experience the dynamic inference engine in real-time. Forecasts are recalculated instantly based on dimensional filters (branch, gender, customer type):*

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <iframe src="https://dynamic-sales-engine.streamlit.app/" width="100%" height="750px" frameborder="0" style="border-radius: 8px; border: 1px solid #ddd; background-color: #ffffff;"></iframe>
    </div>
</div>

## 🔬 Analytical Pipeline & Methodology
The hypothesis tested is that sequentially integrating time-series modeling with linear programming automates inventory decisions, significantly outperforming traditional human intuition.

*   **Phase 1: Descriptive Analytics & EDA:** Conducted rigorous ETL processes. Distribution analysis revealed 100% data integrity (zero nulls) but a strong positive (right-skewed) asymmetry in financial variables, indicating high-value outlier transactions.
*   **Phase 2: Predictive Analytics:** Deployed **Meta's Prophet** algorithm to forecast future demand. This specific model was architected to robustly handle the outliers and skewness discovered during the exploratory phase.
*   **Phase 3: Prescriptive Analytics:** Implemented a mathematical optimization engine using **PuLP** (Linear Programming). The algorithm prescribes the exact purchasing allocation to maximize profit while strictly adhering to budget ($) and warehouse volumetric capacity (m³) constraints.

## 🚀 Strategic Impact
The model demonstrates the capability to allocate capital with mathematical precision, finding the absolute global maximum of projected profitability in milliseconds. This bridges the gap between raw transactional data and automated, optimal resource allocation.
