# Agentic RAG System

### Overview

This project implements a **Retrieval-Augmented Generation (RAG) System** using the **Cohere language model**. It processes **legal and regulatory** documents for the **supply chain** using five specialized agents.

### Agents

1. **Legal Advisor**: Provides legal advice based on the dataset.
2. **Regulations Expert**: Interprets regulations related to supply chain compliance.
3. **Hallucination Checker**: Validates responses to ensure no hallucinated content.
4. **Reference Extractor**: Extracts references from documents supporting responses.
5. **Retrieve Documents**: Fetches relevant documents based on user queries.

### Dataset

The dataset includes legal contracts, laws, and regulations for supply chain management.

---

If proper dataset is provided, we can implement the following agents and enhance our model:

### **Agents and Their Roles**

1. **Supplier Intelligence Agent (SIA)**
    - **Role**: Retrieves supplier performance data, contract terms, and risk factors.
    - **Tools**: ERP systems, procurement databases, vendor portals, contract analysis tools.
    - **Output**: Supplier performance reports, risk assessments, contract term summaries.
2. **Demand Forecasting Agent (DFA)**
    - **Role**: Provides accurate demand forecasts using structured and unstructured data.
    - **Tools**: LLMs, social media analysis tools, weather data, sales history databases.
    - **Output**: Dynamic demand forecasting reports, scenario-based predictions.
3. **Risk Monitoring Agent (RMA)**
    - **Role**: Monitors internal and external risks impacting supply chain operations.
    - **Tools**: Regulatory databases, financial news sources, weather APIs, performance dashboards.
    - **Output**: Risk alerts, disruption reports.
4. **Inventory Optimization Agent (IOA)**
    - **Role**: Manages inventory levels, aligning with demand forecasts.
    - **Tools**: WMS (Warehouse Management Systems), ERP, inventory analytics tools.
    - **Output**: Inventory management dashboards, restocking alerts.
5. **Sustainability Monitoring Agent (SMA)**
    - **Role**: Tracks carbon footprint and energy consumption in logistics.
    - **Tools**: Emissions calculators, transportation logs, sustainability benchmarks.
    - **Output**: Carbon footprint dashboards, eco-efficiency reports.
6. **Real-time Data Aggregation Agent (RTDA)**
    - **Role**: Aggregates data from internal systems and external sources for all agents.
    - **Tools**: Data pipelines, APIs, real-time data aggregation tools.
    - **Output**: Consolidated data streams.
