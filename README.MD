
---

# ** Autonomous Multi-Agent Deal Finder**

An AI-powered system that autonomously detects genuine online deals by combining multi-agent reasoning, real-time data extraction, and intelligent price prediction using a fine-tuned LLaMA-3.2B model.

---

## **1. Introduction**

Online marketplaces are crowded with fluctuating prices, exaggerated discounts, and misleading “offers”.
Users spend time comparing platforms, checking reviews, and verifying whether a listed price is actually a bargain.

This project introduces a fully autonomous multi-agent system that simplifies the entire process.
It operates like a **24/7 intelligent deal hunter**, scanning the web, analyzing products, estimating fair prices, validating discounts, and notifying users of real savings.

---

## ** 2. Problem Statement**

Most existing price trackers simply monitor numerical price changes.
They fail to understand:

* Whether a discount is genuine or artificially inflated
* How a product’s description affects its true value
* Cross-platform inconsistencies and hidden price gaps
* Quality indicators like reviews, sellers, and metadata

**Users need a reliable, AI-driven system that can think, reason, compare, and decide—just like an expert shopper would.**

---

## ** 3. Proposed Solution**

This project provides an **autonomous multi-agent ecosystem** powered by a **fine-tuned LLaMA 3.2B model** that predicts an item’s true market value from its title and description.

The system automatically:

1. Scrapes product data from multiple e-commerce sources
2. Predicts the fair price using a custom fine-tuned model
3. Compares prices across sites
4. Validates authenticity using agent reasoning
5. Detects abnormal discounts
6. Sends user-friendly alerts for genuine deals

All agents collaborate seamlessly, creating an end-to-end intelligent deal analysis pipeline.

---

## ** 4. Key Features**

### ** Autonomous Multi-Agent Workflow**

* Coordinated set of agents handling scraping, validation, price estimation, and notifications
* Continuous, unsupervised operation

### ** Fine-Tuned Price Prediction Model**

* LLaMA 3.2B fine-tuned on product descriptions
* Predicts the fair market price to detect genuine discounts

### ** Smart Deal Detection**

* Uses Actual Price vs Predicted Price scoring
* Includes statistical checks, historical trends, and platform cross-checks

### ** Fraud & Fake Discount Filtering**

* Agents identify inflated MRPs, wrong variants, and misleading listings
* Context-aware validation using LLM reasoning

### ** Real-Time Notifications**

* Delivers concise markdown-based deal summaries
* Triggered only when a strong, validated discount is detected

### ** Extensible Architecture**

* Easy to add new agents, marketplaces, or analysis modules
* Built to scale into a complete shopping intelligence assistant

---

## ** 5. System Architecture**

* **Scraper Agent** → Extracts product data and prices
* **Price Predictor Agent** → Uses LLaMA 3.2B to estimate fair price
* **Comparison Agent** → Checks prices across different marketplaces
* **Validation Agent** → Reviews product metadata & eliminates fake discounts
* **Analyzer Agent** → Computes discount scores and deal confidence
* **Notifier Agent** → Sends alerts upon confirmed deals
* **Coordinator Agent** → Manages workflow and dependencies

---

## **🛠 6. Technology Stack**

* **LLaMA 3.2B** for all language + reasoning tasks
* **Fine-tuning pipeline** using QLoRA
* **Python** for agent logic
* **Multi-agent orchestration** using modular architecture
* **Web scraping tools** (requests / Selenium / Playwright as applicable)
* **Local vector/memory stores** for history tracking
* **Markdown-based reporting & notifications**

---

## ** 7. How It Works**

1. User (or scheduler) triggers scanning
2. Scraper Agent gathers product data
3. Price Predictor estimates fair value
4. Comparison Agent checks competing prices
5. Validation Agent confirms the listing's authenticity
6. Analyzer Agent determines deal score
7. Notifier sends results if the deal qualifies
8. System repeats continuously or at defined intervals

---

## ** 8. Output Example**

* Product title
* Actual price
* Predicted fair price
* Discount percentage
* Confidence score
* Competitor comparison
* Short reasoning summary


---

## ** 9. Future Scope**

* Add support for more marketplaces
* Integrate long-term price trend modeling
* Introduce personalized recommendations
* Upgrade to larger LLaMA variants for deeper reasoning
* Add a UI dashboard for real-time deal tracking

---

## ** 10. Conclusion**

This project demonstrates how a fine-tuned LLaMA model combined with autonomous multi-agent intelligence can transform online shopping into a smarter, data-driven experience.
It brings clarity to pricing, filters out false discounts, and empowers users with trustworthy, AI-verified deal insights.

---


