# 📊 Interactive Sales Dashboard Project

## 🧩 Project Overview
This project is an **Interactive Sales Dashboard** built using **HTML, JavaScript, and Plotly.js**.  
The dashboard visualizes sales data from JSON files and allows interactive exploration of key business metrics.

---

## 🌟 Features
- 📁 Upload sales data in **JSON format** directly from your local computer.  
- 📈 Interactive visualizations for:  
  - **Total Sales Over Time** (aggregated quarterly/yearly)  
  - **Sales by Region**  
  - **Product Performance**  
  - **Customer Type Distribution**  
  - **Impact of Discounts & Promotions**  
- 💎 Responsive layout with **glassmorphism** styling.  
- ⚙️ Easy to customize and extend for additional metrics.  

---

## 🤖 How AI Was Used
**ChatGPT AI** was used to generate and structure the initial HTML/JavaScript code for this dashboard, including:
- Building the dashboard layout and chart containers.  
- Suggesting best practices for data visualization.  
- Creating Plotly chart templates.  
- Implementing file upload and JSON parsing logic.  

📝 **Note:**  
All data logic, customization, styling improvements, and testing were implemented by the developer.

---

## 🚀 How to Run
1. **Download** the project folder and ensure the file `dashboard.html` is present.  
2. **Open** `dashboard.html` in any modern web browser (e.g., Chrome, Edge, or Firefox).  
3. Click the **“Choose File”** button and upload your sales JSON file.  
4. The dashboard will automatically render all interactive charts.  

---

## 📁 Data Requirements
Your JSON file should follow the structure below:

```json
{
  "Date": "2023-02-23",
  "Region": "East",
  "Product": "Laptop",
  "Quantity": 14,
  "UnitPrice": 163.6,
  "StoreLocation": "Store B",
  "CustomerType": "Wholesale",
  "Discount": 0,
  "Salesperson": "Eva",
  "TotalPrice": 2290.4,
  "PaymentMethod": "Online",
  "Promotion": "FREESHIP",
  "Returned": 0,
  "OrderID": "REG100000
