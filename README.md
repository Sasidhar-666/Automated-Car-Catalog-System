# 🚗 Automated Car Catalog System

A ServiceNow-based solution to streamline car catalog management and automate customer request workflows for car showrooms and dealerships.

## 🔍 Overview

This project addresses the inefficiencies faced by automotive showrooms in handling car inventories, customer orders, and approval processes. By leveraging ServiceNow's Flow Designer and Service Catalog, the system automates:

- Car listing and catalog visibility
- Customer order placement via service portal
- Managerial approval workflows
- Task assignment and delivery status tracking

## 🛠️ Technologies Used

- **ServiceNow** (App Engine Studio, Flow Designer, Service Catalog)
- **JavaScript** (Catalog client scripts, business rules)
- **Flow Designer** (for workflow automation)
- **Service Portal** (user-friendly UI for ordering cars)

## 📁 Features

- 📋 **Catalog Management**: Add, update, and display available car models in the service catalog.
- ✅ **Approval Flow**: Auto-approval workflow with condition-based actions for faster processing.
- 📦 **Task Automation**: Automatically assigns fulfillment tasks upon approval.
- 🧾 **Delivery Tracking**: View delivery status and request summary post-order.

## 📸 Screenshots

> _Include screenshots of:_
> - Service Catalog item (e.g., "Order Thar")
> - Approval workflow in Flow Designer
> - Submitted request and delivery status

## 🔗 Getting Started

To deploy or demo this project:

1. Clone the repository.
2. Import provided update sets / XMLs into your ServiceNow instance.
3. Activate the app in App Engine Studio.
4. Open the **Service Portal** (`https://your-instance.service-now.com/sp`) and search for the catalog item (e.g., "Thar").

> _Make sure the necessary roles and permissions are assigned to the users._

## 📦 Repository Contents

- `/docs/` – Documentation and screenshots
- `/update-sets/` – Exported update sets or XMLs from the instance
- `/scripts/` – Sample client scripts and business rules used

## ✨ Credits

Developed by **Sasidhar Reddy Tallapureddy** as a solution to enhance showroom operations using the ServiceNow platform.

---

