# Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Project Title & Team Details
* **Project Title:** Streamlining IT Procurement – Automating Standard Laptop Orders with Flow Designer
* **Team Members:**
  * **Paul Murugan A** (Team Leader)
  * **Ragunathan S**
  * **Hari Priya K**
  * **Pachaiyammal P**
  * **Ramkumar V**

---

## Project Overview

### Problem Statement
Manual IT procurement processes often lead to delayed approvals, lack of visibility for requestors, higher error rates in fulfillments, and unnecessary administrative overhead for IT helpdesk teams when handling routine hardware requests like laptop orders.

### Project Objective
To design and deploy an automated, end-to-end IT procurement solution within ServiceNow using Catalog Items and Flow Designer. The objective is to streamline hardware requests, automate approval workflows, assign fulfillment tasks automatically, and send real-time notifications to users and stakeholders.

### Target Users
* **End Users / Employees:** Request standard laptop hardware quickly via the Service Catalog.
* **Approvers / Managers:** Easily review, approve, or reject hardware procurement requests.
* **IT Fulfillment / Service Desk:** Automatically receive structured task assignments for laptop deployment and configuration.

---

## Modules & Features Implemented

* **Service Catalog / Catalog Items:**
  * Created a custom **Standard Laptop Order** Catalog Item with customized variables (e.g., Laptop Model, Department, Delivery Location, Justification).
* **Workflows & Automation (Flow Designer):**
  * Built an automated Flow triggered upon Catalog Item submission.
  * Implemented multi-stage approvals (Manager Approval -> IT Asset Approval).
  * Auto-generation of Catalog Tasks (SCTASK) for hardware setup, provisioning, and delivery.
* **Custom Tables & ACL Security Rules:**
  * Configured table permissions and Access Control Lists (ACLs) ensuring users can only view their own requests while managers and IT fulfillers have appropriate access rights.
* **Notifications:**
  * Configured automated Email Notifications triggered at key milestones (Request Submitted, Approval Needed, Request Approved/Rejected, Laptop Dispatched).
* **Reports & Dashboards:**
  * Developed custom reports tracking total laptop requests, fulfillment SLA completion times, and pending approvals by department.
   * Once previewing completes with zero errors, click **Commit Update Set**.
7. **Verification:** Navigate to **Service Catalog** > **Catalog Definitions** > **Items** and verify that the *Standard Laptop Order* item is published and active.
