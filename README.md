# Handsmen-Thread
# 💼 HandsMen Threads – Salesforce Internship Project

This project is a part of the **Salesforce Smartbridge Virtual Internship**, where we applied Salesforce skills from Trailhead modules to build a fictional business app for **HandsMen Threads**, a men’s fashion brand. The goal was to elevate the customer experience through proper data management, automation, and user access control.

---

## 🚀 Project Highlights

### 🔧 Salesforce Setup
- Created and configured a **Developer Edition org**
- Built a custom **Lightning App** named `HandsMen Threads`

### 📦 Custom Objects
Defined and managed five custom objects:
- `HandsMen Customer`
- `HandsMen Product`
- `HandsMen Order`
- `Inventory`
- `Marketing Campaign`

### 🛠️ Data Management
- Created custom fields (text, number, currency, date, formula)
- Setup **lookup** and **master-detail relationships**
- Implemented **validation rules** to maintain data integrity

### 📂 App Customization
- Created custom **Tabs** for each object
- Added custom objects to the Lightning App
- Built classic **Email Templates** (Order Confirmation, Stock Alert, Loyalty Program)

### 🔄 Automation
#### Salesforce Flows
- **Record-Triggered Flows** for:
  - Sending order confirmation emails
  - Alerting low inventory stock
- **Scheduled Flow** to assign customer loyalty status (Gold, Silver, Bronze)

#### Apex Automation
- **Apex Triggers**:
  - Auto-calculate total order amount
  - Deduct inventory quantity on order confirmation
- **Batch Apex Job**:
  - Bulk processing for inventory management

### 🔐 User Access Control
- Created **Profiles** and **Roles** (Sales, Inventory, Marketing)
- Assigned **Permission Sets** to users based on responsibilities
- Configured **Email Alerts** to notify customers or internal users

---

## 🧪 Key Functional Demonstrations

- Automatically calculate `Total Amount` using Apex trigger.
- Change `Loyalty Status` based on `Total Purchases` with Scheduled Flow.
- Send emails for:
  - Order confirmation
  - Inventory stock alert
  - Loyalty rewards

---

## 📚 Tools & Technologies

- Salesforce Lightning Platform
- Apex Programming
- Flow Builder
- Validation Rules
- Email Templates (Classic)
- Batch Apex

