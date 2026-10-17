# 01 – Business Analysis

## Overview

The first phase of the ASML project focused on understanding the existing Accounts Payable (AP) process and identifying the main inefficiencies affecting invoice handling.

I reviewed the ASML case documentation and information from the client interview to understand how invoices move between suppliers, the Purchasing Department, Warehouse, Accounts Payable, and Accounting.

The goal was to identify the root causes of inefficiencies and analyse the existing workflow before designing an improved process.

## Business Analysis Activities

### 1. [Fishbone Analysis](https://github.com/patritsia-marinova/ASML-Accounts-Payable-Process-Automation/blob/main/01%20%E2%80%93%20Business%20Analysis/ASML%20FishBone%20.pdf)

I created a Fishbone diagram to investigate the potential root causes of inefficiencies in the Accounts Payable process.

The analysis categorised the causes into **Process, People, Data/Information, Suppliers, Technology, and Management/Organisation**.

I identified issues such as manual invoice entry into the ERP system, missing purchase order numbers, inconsistent supplier invoice formats, multiple approval steps, limited automation, and insufficient process monitoring.

This helped me understand how problems across different departments, systems, and activities contribute to an inefficient invoice processing workflow.

### 2. [IST Process Model & Bottlenecks](https://github.com/patritsia-marinova/ASML-Accounts-Payable-Process-Automation/blob/main/01%20%E2%80%93%20Business%20Analysis/BPMN%20ASML%20(2).pdf)

I developed a BPMN model representing the existing Accounts Payable process, including the activities performed by suppliers, Purchasing, Warehouse, Accounts Payable, and Accounting.

The model shows how invoices are received, matched against purchase orders and delivery information through three-way matching, approved for payment, or returned to suppliers when corrections are required.

I also identified bottlenecks and process wastes, including manual invoice verification, delays in delivery confirmation, waiting for approvals, repeated matching activities, and supplier correction delays.

This helped me understand where unnecessary manual work and waiting occur and which activities could benefit from process improvement and automation.

## Outcome

This phase provided a structured understanding of ASML's existing Accounts Payable process and the main factors contributing to inefficiency.

By combining Fishbone Analysis with BPMN modelling and bottleneck identification, I was able to connect the underlying causes of problems with specific activities in the workflow.

These findings formed the foundation for developing the improved SOLL process, requirements, and automation solution in the next phases.
