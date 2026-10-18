# 03 – Power Automate Development & Testing

## Overview

The final phase of the ASML project focused on translating the proposed Accounts Payable improvements into an automation prototype using Microsoft Power Automate.

After completing the business analysis, process modelling, and requirements development, I explored how SharePoint integration, conditional logic, and automated notifications could support invoice processing and exception handling.

The goal was to demonstrate how business rules could be automated to reduce manual checking and improve communication.

## Development & Testing Activities

### 1. [Power Automate Workflow](https://github.com/patritsia-marinova/ASML-Accounts-Payable-Process-Automation/blob/main/03%20%E2%80%93%20Power%20Automate%20Development%20%26%20Testing/Power%20Automate%20Flow.png)

I independently developed a Power Automate prototype that simulates part of the proposed Accounts Payable process.

The workflow starts when a new item is created in SharePoint. It then retrieves existing items, initialises a variable, and evaluates predefined conditions to determine which actions should be performed.

I used nested conditions to handle different scenarios. Depending on the evaluated information, the workflow can update SharePoint records, set variables, or send automated email notifications.

This demonstrated how business requirements could be translated into automated decision-making and communication.

### 2. Workflow Testing

I tested the workflow by executing it and reviewing the results of the individual actions and conditions.

The screenshot shows a successful execution in which the workflow retrieved SharePoint items, initialised a variable, evaluated the first condition, and continued through the second condition.

During this execution, the workflow followed the False branch of the first condition and the True branch of the second condition. It successfully updated the variable and sent an automated email notification.

The remaining actions were skipped because their conditions were not met. This helped me understand how Power Automate evaluates business rules and executes different branches depending on the available information.

## Outcome

This phase resulted in a developed and tested Power Automate prototype demonstrating how parts of the proposed Accounts Payable process could be automated.

The workflow demonstrated how SharePoint integration, conditional logic, variables, and automated notifications could support structured decision-making and exception handling.

Through this development, I strengthened my skills in **Power Automate, workflow design, conditional logic, testing, and translating business requirements into technical solutions**.

The prototype was developed as a proof of concept and was not deployed as a production system at ASML.
