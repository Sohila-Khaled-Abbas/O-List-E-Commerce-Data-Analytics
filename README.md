<div align="center">
  <img src="images/HRhd2Y0.png" alt="Olist Logo" width="150" style="margin-bottom: 20px;"/>
  
  <h1>O-List E-Commerce Data Analytics Project</h1>
  
  <p><em>A comprehensive Data Engineering and Business Intelligence solution analyzing the Brazilian E-Commerce Public Dataset by Olist.</em></p>

  <!-- Badges -->
  <p>
    <a href="https://powerbi.microsoft.com/"><img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black" alt="Power BI" /></a>
    <a href="https://www.mysql.com/"><img src="https://img.shields.io/badge/SQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" /></a>
    <a href="https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Kaggle" /></a>
    <a href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

## 📌 Project Overview
> [!NOTE]
> The **O-List E-Commerce Data Analytics** project focuses on analyzing an extensive public dataset of orders made at Olist Store. The objective is to provide actionable insights into e-commerce activities, customer behavior, and sales performance through a structured Data Engineering workflow, resulting in an interactive **Power BI dashboard**.

## 📂 Directory Structure

<details>
<summary><b>Click to expand the project directory structure</b></summary>
<br>

```text
O-List_Project/
│
├── data/           # Raw datasets (e.g., customers, geolocation, orders, products) [Git ignored]
├── images/         # Image assets for README and presentations
├── presentation/   # Project presentation slides and insights documentation
├── report/         # Power BI dashboards (e.g., `O-List Dashboard.pbix`)
└── sql/            # SQL scripts for data extraction, transformation, and loading (ETL/ELT)
```
</details>

## 📊 Key Highlights

| Area | Description |
| :--- | :--- |
| 🛠️ **Data Engineering** | Process and clean a relational dataset spanning **100k+ orders** from 2016 to 2018 across multiple dimensions (reviews, payments, products). |
| 📈 **Business Intelligence** | A centralized Power BI reporting layer (`O-List Dashboard.pbix`) highlighting the KPIs that matter. |
| 🔍 **Data Analytics** | Insights into delivery performance, marketing effectiveness, seller distributions, and revenue trends across multiple product categories. |

## 🚀 Getting Started

### Prerequisites
- **Microsoft Power BI Desktop**: Required to interact with the project reports.
- **SQL Environment** *(optional)*: To execute scripts found in the `sql/` directory.

### Quick Start

<details open>
<summary><b>Step-by-step installation guide</b></summary>

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

</details>

## 💻 Technologies Used

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black" alt="Power BI"/><br><b>Data Visualization</b>
      </td>
      <td align="center" width="25%">
        <img src="https://img.shields.io/badge/SQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/><br><b>Data Storage</b>
      </td>
      <td align="center" width="25%">
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/><br><b>Version Control</b>
      </td>
      <td align="center" width="25%">
        <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/><br><b>Operating System</b>
      </td>
    </tr>
  </table>
</div>

## 📜 Acknowledgements & License
> [!IMPORTANT]
> This dataset has been generously provided by **Olist** and made available under a public domain/CC0 license on Kaggle. For more details on the exact schema and data dictionaries, please refer to the original dataset source.

<div align="center">
  <p><em>Crafted with ❤️ for Data Engineering & Analytics</em></p>
</div>
