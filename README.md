Smart Delivery Hub
🔹 Project Description

Smart Delivery Hub is a Salesforce-based CRM application designed to optimize last-mile delivery operations.

The system automates driver assignment, calculates estimated delivery time (ETA), and tracks performance using interactive dashboards.

🧭 Project Overview

Utilizes Salesforce CRM to coordinate delivery hubs, drivers, and deliveries efficiently.

Automatically assigns the nearest available driver to each delivery.

Calculates delivery ETA based on location data.

Provides real-time tracking and analytics through dashboards.

🎯 Project Objectives

Automate driver assignment based on availability and proximity.

Monitor delivery progress and SLA violations.

Visualize operational data using reports and dashboards.

Improve decision-making through Salesforce automation tools.

💻 Technology Stack

Platform: Salesforce Developer Edition

Automation: Flow Builder, Apex Triggers, Process Builder

Programming Languages: Apex, SOQL

Visualization: Lightning Reports and Dashboards

Data Handling: Data Import Wizard

🛠️ System Architecture

Delivery record is created with Status = Scheduled.

Record-triggered Flow calls the NearestDriverService Apex class.

System calculates distance and ETA automatically.

Delivery status progresses through defined lifecycle stages.

Reports and dashboards provide insights to admins and managers.
📊 Reports & Dashboards

Delivery Summary Report: Grouped by delivery status.

Driver Performance Report: Average delivery time per driver.

SLA Breach Report: Identifies delayed or failed deliveries.

Dashboard Metrics

Total Deliveries

On-Time Delivery Percentage

Deliveries by Status

Overdue Deliveries
