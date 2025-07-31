# WhatNext-Vision-Motors-Shaping-the-Future-of-Mobility-with-Innovation-and-Excellence

Apex Trigger and Batch Classes for Vehicle Order Management in Salesforce Project Title WhatNext Vision Motors: Shaping the Future of Mobility with Innovation and Excellence

Project Description This project is developed as part of my Salesforce internship. It focuses on managing vehicle orders efficiently using Apex Triggers, Handler Classes, Batch Apex, and Scheduler Classes.

The system prevents placing orders for vehicles that are out of stock and automatically updates the stock quantity when an order is confirmed. It also includes a batch job that confirms pending orders if stock becomes available, and a scheduler to run this batch job regularly.

Key Features Prevent orders when stock is 0

Automatically reduce stock when an order is confirmed

Confirm pending orders in batch if stock is available

Schedule the batch job to run at regular intervals

Project Files: File Name Purpose VehicleOrderTrigger.trigger: Handles before/after insert/update logic on orders VehicleOrderTriggerHandler.cls: Main logic for stock validation and updates VehicleOrderBatch.cls: Batch class to process pending orders in bulk VehicleOrderBatchScheduler.cls: Scheduler to run the batch job automatically

Tools & Technologies: Salesforce Apex

Apex Triggers and Classes

Batch Apex

Scheduler Class

Git & GitHub

How to Use : Deploy the Apex classes and trigger in your Salesforce Org

Create some Vehicle and Vehicle Order records

Use the trigger to validate stock logic

Run the batch job or set up the scheduler for automation

Purpose : This project demonstrates how to build a simple, modular, and scalable business logic solution using Salesforce Apex. It automates repetitive checks and ensures data consistency, which is crucial in real-world business applications.
