# SwiftShip Tracker

SwiftShip Tracker is a Salesforce Platform Developer project for parcel delivery businesses. It provides a CRM-based workflow for managing the full parcel lifecycle: booking, dispatch, tracking, and delivery confirmation.

## Overview

The solution is designed to help delivery teams centralize parcel records, automate status updates, and improve customer visibility. Customers can book and track parcels, delivery agents can update shipment progress, and support/admin teams can monitor operations through Salesforce reports and dashboards.

## Key Features

- Parcel booking and real-time shipment tracking.
- Delivery status flow from **Booked** to **In Transit**, **Out for Delivery**, and **Delivered**.
- Automated customer notifications and email alerts for delivery updates.
- Salesforce Flow and Apex-based automation for parcel operations.
- Agentforce and Prompt Builder support for AI-assisted parcel status queries.
- Reports and dashboards for parcel trends, delivery performance, and agent activity.
- Role hierarchy, sharing rules, and field-level security for controlled access.

## Salesforce Components

- **Custom Objects:** `Parcel__c`, `Delivery__c`, `Sender__c`, `Receiver__c`
- **Standard Objects:** Account, Contact, Case, Task, EmailMessage, User
- **Automation:** Record-Triggered Flows, Auto-Launched Flows, Apex classes, and Email Alerts
- **User Interface:** Lightning App Page, Dynamic Forms, and the SwiftShip Tracker app
- **Security Model:** Administrator, Delivery Manager, Agent, and Customer roles with profile and record-level access controls


## Documentation

The project documentation is included in `SwiftShip Tracker Documentation.docx` and describes the requirement analysis, Salesforce setup, custom object creation, automation plan, AI integration, reporting, and security design.
