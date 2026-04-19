# 🏭 SAP Order-to-Cash (O2C) Capstone Project

> **KIIT Capstone Project** | SAP SD + FI Integration | S/4HANA Simulation

[![SAP](https://img.shields.io/badge/SAP-S%2F4HANA-0070F2?style=flat&logo=sap)](https://www.sap.com)
[![HTML5](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=flat&logo=bootstrap)](https://getbootstrap.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 📋 Project Overview

This project simulates the **complete Order-to-Cash (O2C) business process** in SAP S/4HANA for a fictitious company — **KIIT Industries Ltd** (Company Code: K100). The application covers all 7 standard SAP steps from initial customer inquiry through final payment collection and AR clearing.

---

## 🔄 The 7-Step O2C Process

| Step | Description | SAP T-Code | Module |
|------|-------------|------------|--------|
| 1 | Sales Inquiry | VA11 | SD |
| 2 | Quotation | VA21 | SD |
| 3 | Sales Order | VA01 | SD |
| 4 | Outbound Delivery | VL01N | SD/WM |
| 5 | Post Goods Issue | VL02N | MM/FI |
| 6 | Billing Document / Invoice | VF01 | SD/FI |
| 7 | Payment Receipt & AR Clearing | F-28 | FI |

---

## ✨ Key Features

- ✅ **Real SAP T-Code Mapping** — Every screen maps to actual SAP transaction codes
- 📊 **Live KPI Dashboard** — Track Orders, Revenue, Deliveries, Pending AR in real-time
- 📂 **Document Flow Panel** — Visual tracking of all SAP documents created
- 💰 **FI Accounting Entries** — Auto-generated journal postings at PGI and Billing steps
- 🇮🇳 **GST Integration** — CGST + SGST split (9% + 9%) for Indian localization
- 📋 **Activity Log** — Session-based audit trail for all actions
- 🎨 **SAP Fiori-Inspired UI** — Professional design with Bootstrap 5 + custom CSS

---

## 🏢 Company Configuration

| Object | Value | Description |
|--------|-------|-------------|
| Company Code | K100 | KIIT Industries Ltd |
| Sales Org | KS10 | KIIT Sales Organization |
| Distribution Channel | 10 | Wholesale |
| Division | 00 | All Products |
| Plant | KP01 | KIIT Manufacturing Plant |
| Currency | INR | Indian Rupee |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sap-o2c-capstone.git
   cd sap-o2c-capstone
   ```

2. Open `index.html` in any modern browser — **no server required!**

3. Follow the 7-step O2C process from Sales Inquiry to Payment.

---

## 📁 Project Structure

```
sap-o2c-capstone/
├── index.html                        # Main application
├── SAP_O2C_Project_Documentation.pdf # Project report (5 pages)
└── README.md                         # This file
```

---

## 📸 Screenshots

> Add screenshots of each step in the application here after running it.

---

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 5.3
- **Scripting:** Vanilla JavaScript (ES6+)
- **Fonts:** Google Fonts (Space Mono, DM Sans)
- **Icons:** Font Awesome 6.4
- **SAP Modules:** SD, FI, MM/WM (Simulated)

---

## 👤 Author

**Aryan Utsav** | Roll No: 2306335  
Branch: IT | Program: B.Tech | Batch: 2023-2027  
KIIT University | Capstone 2026

---

## 📄 License

This project is submitted as part of the KIIT Capstone Program 2026.  
All SAP process steps are based on SAP S/4HANA standard best practices.
