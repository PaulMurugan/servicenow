# Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Project Title & Team Details
* **Project Name:** Streamlining IT Procurement – Automating Standard Laptop Orders with Flow Designer
* **College / Program:** [Insert College / Institution Name]

### Team Members
* **Paul Murugan A** (Team Leader)
* **Ragunathan S**
* **Haripriya K**
* **Pachaiyammal P**
* **Ramkumar V**

### Mentor Details
* **Mentor Name:** [Insert Mentor Name]
* **Designation:** [Insert Designation / Role]

---

## Project Overview
* **Problem Statement:** Traditional IT procurement processes for laptop requests often suffer from manual approvals, delayed fulfillment, lack of tracking visibility, and inefficient asset management.
* **Project Objective:** Automate end-to-end standard laptop requests using ServiceNow Catalog Items and Flow Designer to ensure rapid approval routing, automated task generation, real-time status tracking, and seamless asset updates.
* **Target Users:** Employees submitting laptop requests, IT Managers approving requests, and IT Service Desk/Fulfillment Teams.

---

## Modules & Features Implemented
* **Custom Tables & Data Model:** Created custom tables/fields to manage laptop catalog details, specifications, and fulfillment stages.
* **Access Control Lists (ACLs):** Configured read, write, and create security rules to ensure sensitive employee and procurement data is accessible only by authorized roles (Users, Approvers, IT Admins).
* **Service Catalog Items:** Designed a user-friendly Service Catalog Item for standard laptop orders with dynamic form variables and validation rules.
* **Flow Designer Workflows:** Built automated flows to handle multi-level approval routing, task assignment for hardware provisioning, and automated notification triggers.
* **Notifications:** Set up automated email notifications for request submission confirmation, approval requests, order updates, and fulfillment completion.
* **Reports & Dashboards:** Designed real-time reports and dashboards for IT leadership to track request volume, average fulfillment time, and pending approvals.

---

## Setup / Installation Steps

Follow these steps to import and commit the Update Set into another ServiceNow instance:

1. **Retrieve the Update Set:**
   * Log in to the target ServiceNow instance as an Administrator.
   * Navigate to **System Update Sets** > **Retrieved Update Sets**.
   * Click **Import Update Set from XML** under *Related Links*.
   * Choose the project's `.xml` file and click **Upload**.

2. **Preview the Update Set:**
   * Open the imported Update Set record from the **Retrieved Update Sets** list.
   * Click the **Preview Update Set** button.
   * Check for any errors or preview problems. Resolve conflicts if prompted (e.g., *Accept Remote Version*).

3. **Commit the Update Set:**
   * Once the preview reaches 100% without unresolved errors, click **Commit Update Set**.
   * Wait for the commit process to finish successfully.

4. **Verification:**
   * Navigate to **Service Catalog** > **Catalog Definitions** > **Items** to confirm the laptop order item is active.
   * Navigate to **Process Automation** > **Flow Administration** > **Flows** to verify that the Flow Designer workflow is active and published.
