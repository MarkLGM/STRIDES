# STRIDES

**Student-led Tracking & Resource Inventory for Disaster Emergency Simulation**

A VB.NET WinForms simulation and analytics system developed for **COMP 014 - Simulation and Modeling**.

---

## Overview

STRIDES is a simulation-based logistics management system designed to model disaster relief operations under various operational scenarios. The system allows users to run simulations, monitor key performance indicators (KPIs), analyze results, and generate reports for decision-making and performance evaluation.

---

## Features

### Login System

* User authentication interface
* Entry point to the simulation dashboard

### Simulation Dashboard

* Real-time KPI monitoring
* Simulation timer and event tracking
* Dispatch activity logging
* Runtime controls (Start, Pause, Reset)

### Scenario-Based Testing

The system supports multiple simulation scenarios:

* Sudden Donation Volume Surge
* High Volunteer Fatigue Mode
* Perishable Supply Priority
* Limited Storage Capacity Test

### KPI Analytics

Tracks key logistics metrics including:

* Average Drop-off Time
* Throughput
* Inventory Accuracy
* Volunteer Utilization Rate
* Stockout Frequency
* Request-to-Dispatch Time
* Total Received Units
* Total Delivered Units
* Fulfillment Rate

### Results & Analytics

* Final KPI summary
* Performance assessment
* Scenario analysis
* Recommendations based on simulation outcomes

### Report Export

* Export simulation reports as TXT files
* Save simulation results for documentation and review

---

## System Structure

### Form1 - Login System

Handles user authentication and system access.

### Form2 - Simulation Dashboard

Provides the main simulation environment.

Functions:

* KPI Monitoring
* Scenario Selection
* Dispatch Logging
* Runtime Controls
* Report Export

### Form3 - Results & Analytics

Displays final simulation results.

Functions:

* KPI Summary
* Performance Assessment
* Recommendations
* Analytics Export

---

## Installation

### Option 1: Run Prebuilt Release

1. Download the latest release.
2. Extract the ZIP archive.
3. Open the extracted folder.
4. Run:

```text
STRIDES.exe
```

### Option 2: Build from Source

Requirements:

* Visual Studio 2022 or newer
* .NET Windows Desktop Development workload

Steps:

1. Clone or download this repository.
2. Open `STRIDES.sln`.
3. Build the solution.
4. Run the project.

---

## How to Use

### 1. Login

Launch the application and proceed through the login form.

### 2. Select a Scenario

Choose one of the available simulation scenarios:

* Donation Surge
* Volunteer Fatigue
* Perishable Supply Priority
* Limited Storage Capacity Test

### 3. Start the Simulation

Click:

```text
Start / Resume
```

The simulation will begin generating events and updating KPI values.

### 4. Monitor KPIs

Observe system performance through:

* Throughput
* Inventory Accuracy
* Volunteer Utilization
* Fulfillment Rate
* Dispatch Activity Logs

### 5. View Results

Click:

```text
View Results
```

to open the Results & Analytics dashboard.

### 6. Export Reports

Use:

```text
Export Report
```

to save simulation results to a text file.

---

## Academic Purpose

This project was developed as a course requirement for:

**COMP 014 - Simulation and Modeling**

The objective of the project is to simulate disaster-relief logistics operations, evaluate system performance under different operational scenarios, and provide analytical insights for decision-making.

---

## Technologies Used

* VB.NET
* Windows Forms (WinForms)
* .NET
* Visual Studio 2022

---

## Future Improvements

* Database Integration
* Advanced Statistical Analysis
* Graphical KPI Charts
* Multi-User Support
* Additional Disaster Scenarios
* Enhanced Reporting Features

---

## Author

Developed by **Mark, Mariel Inah, Anna Mariel, Josh, Charles, Joan, and Jennylyn** for academic and educational purposes.

---

## License

This project is released for educational and demonstration purposes.
