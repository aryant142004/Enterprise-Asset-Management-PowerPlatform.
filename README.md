# Enterprise-Asset-Management-PowerPlatform.
An enterprise-grade Power Platform solution featuring a Canvas app, Model-driven app, and custom Dataverse schema for automated IT asset management and employee requests.
# Asset Management & Employee Request Solution

A comprehensive Microsoft Power Platform solution designed to automate enterprise IT asset tracking and streamline internal employee requests. This solution is built entirely within a Microsoft Dataverse environment, emphasizing security, scalability, and robust Application Lifecycle Management (ALM).

## 🚀 Key Features & Applications

*   **Employee Request Portal (Canvas App):** An intuitive, user-friendly frontend enabling employees to submit requests for hardware devices and track their status in real-time.
*   **Asset Management Admin Hub (Model-Driven App):** A high-density back-office administrative interface allowing IT managers to oversee inventory, fulfill employee requests, and log maintenance activities.
*   **Automated Background Workflows (Power Automate):** Automated cloud flows that handle request status updates, email notifications, and automated approval logic.

## 🗄️ Database Architecture (Microsoft Dataverse)

The solution utilizes a fully relational custom Dataverse schema consisting of the following primary tables:
*   `Devices`: Tracks hardware specifications, serial numbers, and availability status.
*   `Requests`: Manages individual employee submissions, approval states, and relational lookups to devices.
*   `Maintenance Logs`: Chronologically logs repairs, inspections, and lifecycle costs for specific hardware assets.

## 🛡️ Enterprise Concepts Covered

*   **Role-Based Security:** Implementation of tailored security roles ensuring read/write isolation (employees can only manage their requests, while admins hold full CRUD access over the asset inventory).
*   **Application Lifecycle Management (ALM):** The entire solution is bundled into a dedicated Microsoft Power Platform Solution container to support seamless export/import and environment isolation.
*   **Enterprise Integration Ready:** Architected with standard relational structures optimized for future downstream synchronization with major ERP systems like SAP S/4HANA.
