# SAP Order-to-Cash (O2C) Project
## Croma Case Study

## Project Overview
This project demonstrates the complete **Order-to-Cash (O2C)** business cycle in SAP using a retail business case study based on **Croma**, a leading electronics retail company.

The objective of this project is to explain how SAP helps automate and integrate customer sales operations starting from customer inquiry to final payment collection.

The project is prepared as part of the **KIIT SAP Capstone Project Submission**.

---

# About O2C Process
Order-to-Cash (O2C) is one of the most important business processes in SAP Sales and Distribution (SD). It manages the full customer order lifecycle.

The O2C cycle begins when a customer shows interest in purchasing a product and ends when the company receives payment.

---

# Business Scenario – Croma
Croma sells products such as:

- Mobile Phones
- Laptops
- Refrigerators
- Televisions
- Washing Machines
- Accessories

Since Croma handles a large number of daily transactions, manual order handling can create:

- Delays
- Billing errors
- Inventory mismatch
- Poor customer experience
- Payment tracking issues

SAP solves these problems through an integrated O2C workflow.

---

# Objectives
- Understand the complete SAP O2C cycle
- Explain business process integration
- Demonstrate SAP SD transaction flow
- Improve efficiency through automation
- Show integration of SD, FI, and Inventory modules

---

# SAP Modules Used
## SAP SD (Sales and Distribution)
Used for:
- Inquiry
- Quotation
- Sales Order
- Delivery
- Billing

## SAP FI (Financial Accounting)
Used for:
- Customer payment posting
- Accounting entries
- Financial reconciliation

## Inventory / Logistics Integration
Used for:
- Stock availability
- Goods movement
- Delivery execution

---

# O2C Process Flow

Customer Inquiry  
↓  
Quotation Creation  
↓  
Sales Order Creation  
↓  
Availability Check  
↓  
Delivery Creation  
↓  
Post Goods Issue (PGI)  
↓  
Billing / Invoice  
↓  
Payment Receipt  
↓  
Completion

---

# Detailed Process Steps

## 1. Customer Inquiry
A customer visits Croma and asks for a laptop with required specifications.

SAP stores the inquiry details for follow-up.

**Example T-Code:** `VA11`

---

## 2. Quotation Creation
Croma prepares a quotation containing:

- Product Name
- Price
- Quantity
- Discount
- Validity Date

**Example T-Code:** `VA21`

---

## 3. Sales Order Creation
After customer confirmation, a sales order is created in SAP.

It includes:

- Customer details
- Material details
- Quantity
- Delivery date
- Pricing

**Example T-Code:** `VA01`

---

## 4. Availability Check
SAP checks whether stock is available in inventory.

If available:
- Order proceeds

If unavailable:
- Backorder / procurement may be required

---

## 5. Delivery Creation
Delivery document is generated for shipping or store handover.

Includes:

- Delivery quantity
- Shipping point
- Dispatch details

**Example T-Code:** `VL01N`

---

## 6. Post Goods Issue (PGI)
Goods are issued from inventory.

Effects:

- Stock reduces
- Goods movement recorded
- Delivery status updated

**Example T-Code:** `VL02N`

---

## 7. Billing / Invoice Generation
Invoice is created for the customer.

Includes:

- Product amount
- Taxes
- Final payable amount

**Example T-Code:** `VF01`

---

## 8. Payment Receipt
Customer completes payment through:

- Cash
- Card
- UPI
- Net Banking

Payment is posted in SAP FI.

**Example T-Code:** `F-28`

---

# Benefits to Croma

- Faster order processing
- Real-time stock visibility
- Accurate invoices
- Better customer satisfaction
- Reduced manual errors
- Integrated finance records
- Improved operational efficiency
- Better reporting and analytics

---

# Unique Points of This Project

- Real retail case study
- Practical business example
- End-to-end process coverage
- Multi-module SAP integration
- Easy to understand workflow

---

# Files Included in Repository

- `O2C_Report.pdf` – Final project report
- `O2C_Source.docx` – Editable report file
- `screenshots/` – Supporting images
- `README.md` – Project overview

---

# Future Scope

- E-commerce website integration
- Real-time delivery tracking
- Customer loyalty management
- AI-based demand forecasting
- Automated returns management
- Advanced dashboards using SAP Analytics

---

# Conclusion
The SAP O2C process is essential for managing customer sales operations efficiently. Through this project, the complete lifecycle from inquiry to payment has been demonstrated using the Croma retail business example.

This project shows how SAP improves accuracy, speed, coordination, and customer satisfaction in modern business environments.

---

# Submitted By
**Your Name:** Salini Satpathy 
**Roll Number:** 23052259  
**Batch / Program:** CSE  
**Institute:** KIIT

---
