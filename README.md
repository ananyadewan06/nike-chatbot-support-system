# Nike Customer Support Assistant — CX & Consumer Strategy

## Overview
This project explores the design of a scalable customer support system for Nike by analyzing consumer needs across the digital commerce journey. The objective is to improve customer experience by enabling faster, clearer, and more intuitive self-service support while reducing dependency on human agents for repetitive and predictable queries.

The solution proposes a dual-framework chatbot architecture that combines a rule-based chatbot for high-frequency tasks with an AI-powered chatbot for complex, policy-driven inquiries. Together, the system balances speed, accuracy, and scalability in a manner consistent with real-world enterprise e-commerce environments.

---

## Problem Statement
Nike customers frequently seek support related to product discovery, sizing and fit, membership benefits, shipping, returns, order management, and Nike By You customization. Existing support systems often struggle to handle this range efficiently, leading to friction, longer resolution times, and inconsistent user experiences.

A single chatbot approach is insufficient:
- Rule-based systems lack flexibility for nuanced questions  
- AI-only systems may sacrifice speed and clarity for simple tasks  

This project examines how a hybrid support model can better align with consumer behavior and operational realities.

---

## Approach & System Design

### Dual-Framework Architecture

#### Rule-Based Chatbot (Fixed Flow)
- Designed for predictable, high-volume customer queries  
- Uses structured navigation menus and visual category cards  
- Mirrors Nike’s retail journey (Shoes, Apparel, Sizing, Orders, Returns, Customization)  
- Reduces cognitive load and enables rapid self-service  

#### AI-Powered Chatbot
- Designed for open-ended and policy-heavy queries  
- Interprets natural-language input to determine intent  
- Trained on authenticated Nike help-center and policy resources  
- Provides contextual, brand-aligned responses for complex inquiries  

Together, these components address both efficiency-driven and explanation-heavy support needs.

---

## Consumer Journey Analysis
The chatbot structure was informed by analysis of common customer journeys, including:
- Product exploration and category navigation  
- Sizing and fit uncertainty  
- Order tracking and shipping timelines  
- Return eligibility and refund processes  
- Membership benefits and customization rules  

These journeys were translated into structured support flows to align with real consumer expectations.

---

## Evaluation & Key Insights
- High-frequency queries benefit most from structured, rule-based navigation  
- Policy-driven questions require flexible, natural-language interpretation  
- A hybrid model provides a better balance than single-system designs  
- Reducing cognitive load is critical for successful e-commerce self-service  

The project also considers practical constraints such as data freshness, content maintenance, and system integration.

---

## Limitations
- No integration with real-time inventory or order management systems  
- AI responses depend on the accuracy and recency of training data  
- Visual navigation elements require ongoing manual updates  
- No live deployment or operational performance metrics included  

These limitations were intentionally acknowledged to maintain realism.

---

## Future Enhancements
Potential future improvements include:
- Integration with live APIs for order and inventory tracking  
- Multilingual support  
- Automated content refresh pipelines  
- Personalization using member-level data  

---

## Disclaimer
This project is a conceptual and academic exercise intended to reflect real-world customer experience and support system design. It does not represent an official Nike product or implementation.

---

## Project Focus
This project demonstrates consumer journey analysis, CX system design, and practical tradeoff evaluation within a large-scale digital commerce context.
