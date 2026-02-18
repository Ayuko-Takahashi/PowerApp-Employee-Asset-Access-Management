# 🚀 Employee Asset & Access Management App

Enterprise-grade internal request management solution built using Microsoft Power Apps, SharePoint Online, Power Automate, and Power BI.  
This application centralizes employee asset and system access requests with structured data capture, automated notifications, role-based visibility, and analytics reporting.

## 📌 Project Summary
Traditional email-based IT request handling creates inconsistent formats, limited tracking visibility, and manual overhead.  
This solution modernizes the process by introducing a structured Power Platform application that ensures governance, automation, and scalability.

## 🏗 Solution Architecture
Power Apps (User Interface)  
↓  
SharePoint Online (Data Storage)  
↓  
Power Automate (Notification Engine)  
↓  
Power BI (Reporting & Analytics)

## ✨ Features
### 🔹 Structured Request Submission
- Asset requests (laptops, monitors, peripherals)
- System access requests (Microsoft 365, VPN, internal systems)
- Profile update submissions
- Conditional field visibility based on request type

### 🔹 Status Lifecycle Management
- Default status assignment ("Pending")
- Automated status updates
- Administrative status control
- Historical tracking of all requests

### 🔹 Automated Notifications
- Email confirmation upon submission
- Status change notifications
- Administrative alerting for new requests

### 🔹 Role-Based Access
- Employee dashboard ("My Requests")
- Administrative management view
- Controlled data visibility

### 🔹 Data Governance
- Structured choice columns
- Required field validation
- Consistent schema enforcement
- Timestamp logging for audit readiness

### 🔹 Analytics Integration
- Power BI dashboard integration
- Request volume tracking
- Status distribution reporting
- Department-level insights

## 🗂 SharePoint Data Model
| Column Name      | Type                |
|------------------|--------------------|
| Request ID       | Auto-generated     |
| Employee Name    | Single line text   |
| Department       | Choice             |
| Request Type     | Choice             |
| Asset Type       | Choice             |
| Access Type      | Choice             |
| Justification    | Multiple lines     |
| Urgency          | Choice             |
| Status           | Choice             |
| Created Date     | System-generated   |

## 🛠 Technologies Used
- Microsoft Power Apps (Canvas App)
- SharePoint Online
- Microsoft Power Automate
- Microsoft Power BI
- Microsoft 365

## 🎯 Skills Demonstrated
- Low-code enterprise application development  
- SharePoint data architecture design  
- Microsoft 365 integration  
- Role-based interface design  
- Workflow automation  
- Data governance implementation  
- Business process modernization  

## 📷 Screenshots
Screenshots will be added after full implementation:
- Home Screen  
- Request Submission Form  
- Employee Dashboard  
- Admin Management View  
- SharePoint Backend Structure  
- Power BI Dashboard  

## 📈 Business Impact
- Standardized internal request handling  
- Improved visibility and tracking  
- Reduced manual administrative effort  
- Scalable and extensible architecture  
- Enhanced reporting and governance control  
