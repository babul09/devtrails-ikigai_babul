Here’s a **clean, natural, GitHub-ready README version** (well-structured, polished, and easy to read):

---

# 🟢 Thunai (துணை)

### *So a bad day doesn’t mean no income.*

---

## 📌 Problem

In cities like Chennai, food delivery partners depend entirely on daily work to earn.
However, their income is highly affected by situations outside their control.

* 🌧️ During heavy rain, deliveries slow down or stop due to flooding and traffic
* ⏱️ At restaurants, long waiting times delay order pickups
* 🚧 Local disruptions like curfews or restrictions can prevent them from working

For a delivery partner, **time directly translates to earnings**.
Even losing **30–60 minutes** can significantly impact their daily income.

Despite this, there is **no simple system** that supports them when these disruptions occur.

---

## 💡 Solution

**Thunai** is a simple and practical support system designed for delivery partners.

It helps them recover part of their lost income when:

* 🌧️ Rain affects their ability to deliver
* ⏱️ They spend too much time waiting at restaurants

The system works **automatically in the background**,
without requiring the worker to raise any claim.

---

### 🎯 Core Idea

> A bad day shouldn’t mean no income.

---

## 🎯 Scope & Design Choices

We intentionally focused on two key situations:

* 🌧️ Rain-related disruptions
* ⏱️ Restaurant waiting delays

These are:

* Frequent
* Measurable
* Directly linked to income loss

While other factors like curfews, strikes, or restrictions also affect delivery work,
we chose to prioritize **simple and implementable triggers** for this phase.

This ensures:

* Clarity
* Reliability
* Practical feasibility

---

## 🔄 Workflow

### 🧑‍💼 Worker Flow

1. Delivery partner registers on Thunai
2. Selects a weekly plan
3. Continues working normally (Swiggy/Zomato)
4. System runs in the background

If a disruption occurs:

* 🌧️ Heavy rain
* ⏱️ Long waiting time

➡️ Support is automatically provided

---

### ⚙️ System Flow

The system continuously monitors:

* 🌧️ Weather conditions (rainfall data)
* 📍 Worker location
* ⏱️ Time spent at restaurants

---

### Trigger Conditions

* Rainfall exceeds threshold (e.g., > 50 mm)
* Waiting time exceeds 15 minutes

---

### Processing

1. Trigger is detected
2. Basic validation checks are performed
3. Compensation is calculated
4. Payout is issued automatically

---

## ⚡ Parametric Approach

Thunai follows a **parametric model**.

Instead of requiring manual claims,
support is triggered automatically when predefined conditions are met.


<img width="984" height="892" alt="image" src="https://github.com/user-attachments/assets/36daba05-2782-4233-accf-67cd87a2a587" />


### Examples

* If rainfall exceeds a threshold → support is triggered
* If waiting time crosses a limit → support is triggered


<img width="2043" height="1348" alt="image" src="https://github.com/user-attachments/assets/54695f35-885a-444e-999e-497f0c6d8ded" />


---

### Benefits

* Faster response
* No manual effort
* Transparent and consistent support

---

## 💰 Weekly Pricing Model

| Plan  | Price      | Coverage                    |
| ----- | ---------- | --------------------------- |
| Basic | ₹30 / week | Rain-based support          |
| Pro   | ₹50 / week | Rain + waiting time support |

The weekly model aligns with how delivery partners earn and manage their income.

---

## 🤖 Logic Used (Simple & Practical)

For this phase, Thunai uses **rule-based logic**:

* Rain detection using weather APIs
* Waiting time tracking using order timestamps

---

### Why This Approach?

* Reliable
* Easy to implement
* Transparent

---

### Future Improvements

* Historical data analysis
* Predictive risk models

---

## 🔌 Integration

Thunai integrates simple external signals:

* 🌧️ Weather API → detects rainfall conditions
* 📍 Location data → validates worker’s environment
* ⏱️ Order timestamps → calculates waiting time

---

## 🛡️ Basic Validation

To ensure correctness:

* Weather data is cross-checked
* Location consistency is verified
* Waiting time is calculated based on actual activity

These checks help prevent incorrect or false triggers.

---

## 🧱 Tech Stack

**Frontend**

* React

**Backend**

* Node.js / Express

**Database**

* PostgreSQL

**APIs**

* Weather API (real-time rainfall data)

---

## 🧭 Development Plan

### Phase 1 — Ideation & Design

* Problem definition
* Workflow design
* System architecture

---

### Phase 2 — Core Development

* Registration
* Weekly plan selection
* Tracking system
* Trigger logic
* Payout simulation

---

### Phase 3 — Enhancements

* Improved validation
* Dashboard
* Performance optimization

---

## 🔮 Future Scope

Thunai can be extended to support additional disruptions such as:

* Curfews
* Strikes and local restrictions
* Area-level access limitations

---

### Potential Enhancements

* Demand-based signals (order fluctuations)
* Advanced risk scoring
* Community-based pooling mechanisms

---

## 💬 Why Thunai Matters

Thunai focuses on **real, everyday challenges** faced by delivery partners.

It does not try to solve everything.
Instead, it provides **small, meaningful support when it matters most**.

Even a small support can change how a worker’s day ends.

---

## 🚀 Conclusion

Thunai is not just an insurance idea.
It is a step toward making delivery work more stable and less uncertain.

---



 So a bad day doesn’t mean no income.

