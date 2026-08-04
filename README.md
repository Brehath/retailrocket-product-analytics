# Retailrocket Product Analytics: Customer Journey & Conversion Analysis

## Overview

This project presents an end-to-end product analytics case study using the **Retailrocket E-Commerce Dataset**, comprising over **2.7 million user interactions** collected across a four-and-a-half-month period. The objective is to analyze customer behaviour throughout the purchase journey, identify the key drivers of conversion and abandonment, and develop data-driven recommendations to improve business performance.

The project combines data transformation, session modeling, behavioural analytics, funnel analysis, customer segmentation, repeat interaction analysis, and experiment design to demonstrate how clickstream data can be transformed into actionable product insights.

---

## Business Problem

Understanding why customers abandon the purchase journey is a fundamental challenge in e-commerce. Although platforms generate millions of behavioural events, identifying meaningful patterns that influence purchasing decisions requires structured analysis of customer interactions.

This project addresses the following business questions:

- How does user engagement vary across purchase funnel outcomes?
- Which behavioural signals indicate stronger purchase intent?
- How does repeated engagement influence conversion?
- Which customer segments generate the highest business value?
- What product improvements can increase conversion and customer engagement?

---

## Dataset

The analysis uses the **Retailrocket Recommender System Dataset**, containing anonymized behavioural events collected from a real-world e-commerce platform.

### Dataset Statistics

- **2.7+ million** behavioural events
- **1.4+ million** unique users
- Approximately **235,000** products
- **4.5 months** of customer activity

### Event Types

- Product View
- Add to Cart
- Transaction (Purchase)

---

# Project Workflow

## 1. Data Processing & Analytics Pipeline

An analytical data pipeline was developed to transform raw clickstream events into structured datasets suitable for behavioural analysis.

Key processes include:

- Data cleaning and preprocessing
- Event timestamp parsing and ordering
- Session reconstruction using a 30-minute inactivity threshold
- Session-level and user-level feature engineering
- Optimized storage using Apache Parquet
- Local analytical querying using DuckDB

---

## 2. Funnel Analysis

The customer purchase journey was reconstructed to evaluate progression through the conversion funnel.

The analysis includes:

- View → Cart → Purchase funnel
- Funnel conversion rates
- Drop-off analysis
- Cart abandonment behaviour
- Session outcomes
- Purchase timing patterns

---

## 3. Behavioural Segmentation

Users were grouped into behavioural segments based on browsing and purchasing patterns to understand differences in engagement and buying intent.

Segment profiling includes:

- Browsing intensity
- Repeat product views
- Cart behaviour
- Purchase frequency
- Session characteristics

---

## 4. Repeat Interaction & Customer Behaviour Analysis

Customer behaviour was analysed to understand repeat engagement and purchasing activity.

The analysis includes:

- Repeat product interaction
- Return frequency analysis
- Repeat purchase behaviour
- Returning customer contribution
- Customer activity patterns

---

## 5. Product Recommendations

Behavioural insights were translated into practical product recommendations aimed at improving customer engagement and conversion.

Key recommendations include:

- Personalised reminders after repeated product views
- Cart recovery interventions
- Improved product discovery experiences
- Retention initiatives for repeat purchasers

---

## 6. Experiment Design

An A/B testing framework was proposed to evaluate the effectiveness of the highest-impact product recommendation.

The framework includes:

- Business hypothesis
- Target audience
- Success metrics
- Sample size estimation
- Minimum Detectable Effect (MDE)
- Estimated experiment duration

---

# Key Findings

- A substantial proportion of users leave the platform without progressing beyond product browsing.
- Repeated interaction with the same product is a strong behavioural indicator of purchase intent.
- Returning customers contribute disproportionately to completed purchases despite representing a smaller share of users.
- Behavioural features derived from clickstream activity provide valuable signals for customer targeting and product optimization.
- Data-driven interventions focused on high-intent users have the potential to improve conversion efficiency.

---

# Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Processing | Pandas |
| Analytical Database | DuckDB |
| Query Language | SQL |
| Storage | Apache Parquet |
| Visualization | Matplotlib |
| Development Environment | Jupyter Notebook |

---

# Skills Demonstrated

- Product Analytics
- Customer Journey Analysis
- Funnel Analysis
- Behavioural Segmentation
- Repeat Interaction & Return Frequency Analysis
- Data Transformation & Session Modeling
- Feature Engineering
- SQL Analytics
- DuckDB
- Apache Parquet
- Python Data Analysis
- Experimentation & A/B Test Design (Hypothesis Framework)
- Business Insight Generation

---

# Conclusion

This project demonstrates an end-to-end product analytics workflow, from transforming raw clickstream data into structured analytical datasets to generating actionable business recommendations. By combining behavioural analytics, session modeling, SQL-based analysis, and experimentation principles, the project illustrates how customer interaction data can be leveraged to identify conversion opportunities, understand user behaviour, and support evidence-based product decisions.

---

# Author

**Brehath Subramaniam**

M.Sc. Business Analytics

