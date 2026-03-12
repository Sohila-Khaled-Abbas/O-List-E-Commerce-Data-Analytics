<div align="center">
  <img src="images/HRhd2Y0.png" alt="Olist Logo" width="150" style="margin-bottom: 20px;"/>
  <h1>O-List E-Commerce Data Analytics Project</h1>
  <p>A comprehensive Data Engineering and Business Intelligence solution analyzing the Brazilian E-Commerce Public Dataset by Olist.</p>
</div>

---

## 📌 Project Overview
The **O-List E-Commerce Data Analytics** project focuses on analyzing an extensive public dataset of orders made at Olist Store. The objective is to provide actionable insights into e-commerce activities, customer behavior, and sales performance through a structured Data Engineering workflow, resulting in an interactive **Power BI dashboard**.

## 📂 Directory Structure

```text
O-List_Project/
│
├── data/           # Raw datasets (e.g., customers, geolocation, orders, products) [Git ignored]
├── images/         # Image assets for README and presentations
├── presentation/   # Project presentation slides and insights documentation
├── report/         # Power BI dashboards (e.g., `O-List Dashboard.pbix`)
└── sql/            # SQL scripts for data extraction, transformation, and loading (ETL/ELT)
```

## 📊 Key Highlights
- **Data Engineering**: Process and clean a relational dataset spanning 100k+ orders from 2016 to 2018 across multiple dimensions (reviews, payments, products).
- **Business Intelligence**: A centralized Power BI reporting layer (`O-List Dashboard.pbix`) highlighting the KPIs that matter.
- **Data Analytics**: Insights into delivery performance, marketing effectiveness, seller distributions, and revenue trends across multiple product categories.

## 🚀 Getting Started

### Prerequisites
- **Microsoft Power BI Desktop**: Required to interact with the project reports.
- **SQL Environment** *(optional)*: To execute scripts found in the `sql/` directory.

### Quick Start
1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd O-List_Project
   ```
2. **Download the Data**:
   The datasets used in this project are from the [Kaggle Olist Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). Start by downloading the dataset and placing all the downloaded `.csv` files inside the `data/` directory.
3. **Launch the Dashboard**:
   Navigate to the `report/` folder and open `O-List Dashboard.pbix` with Microsoft Power BI Desktop to explore the dashboards and visualizations.
4. **Extend**:
   Add any specific SQL or Python scripts inside their designated folders if you are adapting the ELT/ETL logic locally.

## 💻 Technologies Used
- **Data Visualization**: Microsoft Power BI
- **Data Storage & Transformation**: SQL
- **Version Control**: Git / GitHub
- **Operating System**: Windows / Cross-platform

## 📜 Acknowledgements & License
This dataset has been generously provided by **Olist** and made available under a public domain/CC0 license on Kaggle. For more details on the exact schema and data dictionaries, please refer to the original dataset source.
