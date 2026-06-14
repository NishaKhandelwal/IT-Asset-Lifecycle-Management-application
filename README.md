# IT Asset Lifecycle Management System

## Overview

The IT Asset Lifecycle Management System is a custom **ServiceNow Scoped Application** built to automate and manage the complete lifecycle of IT assets within an organization.

The application provides employees with a self-service portal for requesting and managing IT assets while enabling the IT Asset Team to efficiently manage allocation, repairs, transfers, returns, retirement, and inventory through automated workflows.

> **Note:** This is an independent educational project developed on a ServiceNow Personal Developer Instance (PDI) for learning and portfolio purposes. It is not affiliated with, sponsored, or endorsed by ServiceNow.

---

## Features

### Asset Management

* Custom IT Asset table extending the Asset table
* Child asset tables:

  * Laptop
  * Desktop
  * Mobile Phone
* Automatic Asset Tag generation
* Manufacturer and model selection
* Asset lifecycle tracking

### Service Catalog

Catalog Items

* Request Laptop
* Request Desktop
* Request Mobile Phone

Record Producers

* Return Asset
* Report Asset Issue
* Transfer Asset
* Retire Asset

A custom **IT Asset Catalog** module provides direct access to all catalog items.

---

## Workflow Automation

### Asset Request Process

* Service Catalog request submission
* Approval workflow
* Inventory availability validation
* Automatic Asset Task creation
* Asset allocation
* Request fulfillment

### Asset Repair Process

* Report asset issues through the Service Catalog
* Automatically place assets into **In Repair** status
* Optional temporary replacement request
* Automatic creation of replacement allocation tasks (subject to availability)
* Repair completion workflow
* User notifications after repair completion

### Asset Return

* Return requests through Record Producers
* Automatic asset status updates
* Removal of user assignment
* Task closure and notifications

### Asset Transfer

* Transfer assets directly between employees
* Automatic reassignment through Asset Tasks

### Asset Retirement

* Retirement request workflow
* Approval process
* Retirement date tracking
* Asset lifecycle updates

---

## Additional Enhancements

* Inventory availability validation before approval
* Temporary replacement request during repair
* Optional repair completion notifications
* Warranty tracking and proactive warranty alerts
* Retirement recommendations based on asset lifecycle criteria

---

## Reporting & Dashboard

Dashboard includes:

* Assets By Type
* Assets By Status
* Assets In Repair
* Open Asset Tasks
* Retired Assets
* Asset Requests By Type
* Assets Assigned Per User

---

## Technologies Used

* ServiceNow Scoped Applications
* Flow Designer
* Service Catalog
* Record Producers
* Catalog Items
* Approvals
* Notifications
* Client Scripts
* Business Scripts
* Reporting
* Dashboards
* Table Inheritance

---

## Skills Demonstrated

* ServiceNow Application Development
* Flow Designer Automation
* Service Catalog Development
* Table Design & Inheritance
* Asset Lifecycle Management
* Business Process Automation
* Client-side Scripting
* Reporting & Dashboards
* End-to-End Application Design

---

## Disclaimer

This project was developed independently as a learning and portfolio project using a ServiceNow Personal Developer Instance (PDI). It contains original application design and implementation and does not include proprietary ServiceNow training material, certification content, or exam questions. "ServiceNow" is a trademark of ServiceNow, Inc. This project is not affiliated with or endorsed by ServiceNow.
