


Project title: **CRM Application for Handling Clients and Property Requirements**
NM Id : 4224582A19853839BBB4409FBE0BD706
This project is a CRM (Customer Relationship Management) application aimed at handling clients and their property-related requirements. It integrates Salesforce with Jotform, defines user roles and profiles, automates approval processes for properties, and includes a Lightning Web Component (LWC) for enhanced user interaction.


Table of Contents
- Getting Started
- Features
- Usage


Getting Started

Prerequisites
- Salesforce Developer Org
- Jotform Account  
- Git for version control

Setup Instructions

1. Jotform Integration
   - Step 1: Create a Jotform to capture customer details (name, phone, email, etc.).  
   - Step 2: Integrate the Jotform with Salesforce to automatically create customer records when the form is submitted.  
   - [Jotform Link](https://form.jotform.com/243133795683061)

2. Salesforce Setup
   - Custom Objects: Create Customer and Property objects using a provided spreadsheet.  
   - Roles & Profiles: Define roles (Sales Executive, Sales Manager, Customer) and manage profile permissions accordingly.  
   - Approval Process: Create an approval process for the Property object, ensuring properties are verified before being shown to clients.

3. Lightning Web Component (LWC) 
   - Step 1: Develop a custom LWC component for improved user interaction.  
   - Step 2: Add the LWC component to the Property Details app page for users to interact with properties based on verification status.

4. Record Trigger Flow  
   - Automate property record submissions for approval using Record Trigger Flow in Salesforce.


Features

- Jotform Integration: Automates data collection from users and syncs it with Salesforce.  
- Custom Objects: Handles client (Customer) and property (Property) data storage.  
- Role & Profile Management: Manages user access and permissions based on their roles (Sales Executive, Sales Manager, Customer).  
- Approval Process: Ensures that properties are approved before being displayed to clients.  
- LWC Component: Allows users to search for and view properties, showing only verified properties to approved customers.  
- Property Details App: A dedicated app within Salesforce to manage and display properties.



Usage

1. Creating and Integrating Jotform 
   - Create a Jotform to collect customer information.  
   - Integrate the form with Salesforce to automatically create customer records in the Customer object.

2. Managing Roles and Profiles
   - Define and assign user roles and profiles, ensuring proper permissions for accessing and managing property information.

3. Using the Property Details App
   - Users can access and manage property-related information through the Property Details App.  

4. Approval Process 
   - Automate the approval process to verify property listings before they are displayed to customers.  

5. LWC Component  
   - Customers can view verified properties, while non-verified customers see a broader property list, thanks to the custom LWC component.


Contributors
Nandhinin T,
Carmal princy A,
Ashiritha S,
Kirthana M



