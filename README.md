Thunai: Support for Delivery Partners

Thunai is a simple, practical support system designed to help food delivery partners recover a portion of their lost income due to unforeseen disruptions. We focus on real, everyday challenges faced by these essential workers, providing meaningful support when it matters most.
The Problem

Delivery partners in cities like Chennai rely entirely on daily earnings. However, their income is highly vulnerable to circumstances beyond their control, such as:

    Heavy Rain: Flooding and traffic congestion significantly slow down or halt deliveries.
    Long Restaurant Wait Times: Extended delays at pickup points directly cut into earning time.
    Local Disruptions: Curfews or restrictions can prevent partners from working altogether.

Even losing 30-60 minutes of work time can substantially impact a partner's daily income. Currently, there's no straightforward system to provide immediate support during these events.
The Solution: Thunai

Thunai addresses this by automatically providing support when delivery partners face:

    🌧️ Rain-related disruptions
    ⏱️ Excessive waiting times at restaurants

The system operates seamlessly in the background, requiring no manual claims from the worker. Our core principle is simple: a bad day doesn't mean no income.
Scope & Design Choices

For this initial phase, we've prioritized two key situations:

    Rain-related disruptions: Frequent, measurable, and directly linked to income loss.
    Restaurant waiting delays: Also frequent, measurable, and a common cause of income reduction.

While other factors like curfews or strikes exist, we focused on these two for clarity, reliability, and practical implementation.
How it Works
Worker Flow

    Register: Delivery partners sign up on Thunai.
    Plan Selection: Choose a weekly plan (Basic or Pro).
    Work as Usual: Continue working on platforms like Swiggy/Zomato.
    Automatic Support: The system runs in the background. If a disruption (heavy rain or long wait time) occurs, support is automatically disbursed.

System Flow

    Monitoring: Continuously tracks weather conditions (rainfall data), worker location, and time spent at restaurants.
    Trigger Evaluation: Checks if predefined thresholds are met (e.g., rainfall > 50 mm, waiting time > 15 minutes).
    Validation: Performs basic checks for location consistency and data accuracy.
    Automatic Payout: Compensation is calculated and issued automatically.

Parametric Approach

Thunai utilizes a parametric model. Instead of manual claims, support is triggered automatically by predefined conditions, ensuring:

    ⚡ Faster Response
    ✅ No Manual Effort
    ⚖️ Transparent & Consistent Support

Pricing Model

We offer flexible weekly plans aligned with delivery partner earnings:

    Frontend: React
    Backend: Node.js / Express
    Database: PostgreSQL
    APIs: Weather API (for real-time rainfall data)

Development Plan

    Phase 1: Idea design, workflow definition, system architecture.
    Phase 2: Core implementation (registration, tracking, trigger logic, payout simulation).
    Phase 3: Enhancements (validation improvements, dashboard, optimization).

Future Scope

Thunai can be extended to support additional disruptions like curfews, strikes, and local restrictions. Future enhancements could include demand-based signals, advanced risk scoring, and community pooling.

Why Thunai Matters

Thunai provides small, meaningful support that can significantly improve a delivery partner's day. It's a step towards making delivery work more stable and less uncertain, ensuring that a bad day doesn't mean no income.
