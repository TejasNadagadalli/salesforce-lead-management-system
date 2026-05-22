# System Architecture

## Overview

The Salesforce Lead Management System automates lead handling and improves sales workflow efficiency using Salesforce automation tools.

## Workflow Architecture

1. User creates a Lead record
2. Record-Triggered Flow evaluates Lead Region
3. Lead Owner is assigned automatically
4. Email notification is sent to assigned sales representative
5. Validation Rules enforce data quality before lead conversion
6. Reports and Dashboards provide business insights

## Components Used

- Lead Object
- Record-Triggered Flow
- Validation Rules
- Lightning Record Pages
- Reports & Dashboards
- Email Actions

## Automation Logic

| Region | Assigned Owner |
|---|---|
| India | India Sales User |
| USA | US Sales User |
| Europe | Europe Sales User |
