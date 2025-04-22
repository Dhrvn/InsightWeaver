# InsightWeaver

**InsightWeaver** is an intelligent, multi-agent system that automatically processes and generates insights from tabular data like CSV, Excel, and JSON files.

---

## 🚀 Features

- Load and understand structured datasets
- Extract KPIs, trends, and anomalies
- Generate summary reports with visualizations
- Modular, extendable multi-agent architecture

---

## 🧠 Agent Roles

| Agent | Responsibility |
|-------|----------------|
| `DataLoaderAgent` | Reads and standardizes data |
| `InsightAgent` | Extracts key metrics and insights |
| `ChartAgent` | Generates visualizations (bar, line, etc.) |
| `SummaryAgent` | Writes human-readable summaries |
| `ReportAgent` | Compiles everything into a final report |

---

## 🗂️ Project Structure

insightweaver/
├── agents/
│   ├── data_loader.py          # Loads and preprocesses input data
│   ├── insight_agent.py        # Extracts KPIs, aggregates, anomalies
│   ├── chart_agent.py          # Generates charts using matplotlib or plotly
│   ├── summary_agent.py        # Creates human-readable insights
│   └── report_agent.py         # Compiles output into markdown/pdf
├── core/
│   └── utils.py                # Helper functions for agents
├── data/
│   └── sample_customer_data.csv
├── outputs/
│   └── sample_report.md
├── main.py                     # Agent orchestrator / entry point
└── requirements.txt

---

## 📥 Example Input (CSV)

customer_id,age,gender,purchase_amount  
1001,29,F,120  
1002,35,M,340  
1003,31,F,290  
1004,22,M,160  

---

## 📤 Example Output

### Summary:
- Total customers: 4  
- Average purchase amount: ₹227.5  
- Top spending age group: 30–40  
- Gender distribution: 50% Male, 50% Female  

### Visualizations:
- Bar chart of purchases by age  
- Pie chart of gender distribution  


