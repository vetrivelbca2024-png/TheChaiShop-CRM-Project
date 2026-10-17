# A CRM APPLICATION FOR THECHAISHOP & CO

## Project Overview
This project is a Salesforce-based Customer Relationship Management (CRM) application developed for "TheChaiShop & Co" to manage customer, employer, and enterprise accounts efficiently, automate billing, generate reports, and improve customer engagement through automated birthday notifications.

## Key Features & Milestones
- **Developer Account Setup:** Configured a free Salesforce Developer Edition.
- **Custom Objects:** Created `Employer Account`, `Customer Account`, and `Enterprise Account` objects.
- **Custom Tabs & Lightning App:** Created a dedicated navigation app named `TheChaiShop&Co`.
- **Global Picklists:** Created reusable picklist value sets for `Gender`, `Items`, and `Payment Mode`.
- **Fields & Relationships:** Added custom fields like `Phone`, `Items`, `Payment Mode`, `Quantity`, `Price`, and a formula field for `Total Bill` (`Quantity * Price`).
- **Validation Rules:** Implemented phone number validation (`LEN(Phone__c) <> 10`).
- **Record Types & Page Layouts:** Separated Retail and Enterprise customer workflows.
- **Email Automation (Flows):** Configured automated birthday wishes using Salesforce Flows and Email Templates.
- **Reports & Dashboards:** Built visual analytics for customer sales monitoring.

## Tech Stack
- **Platform:** Salesforce Lightning Platform
- **Database:** Salesforce Cloud
- **Automation:** Salesforce Flows & Validation Rules
