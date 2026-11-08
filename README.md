# AI-Powered Customer Support Automation

## Project Overview
An automated customer support workflow built with Zapier that processes incoming customer emails, uses AI to analyze complaints, stores structured customer support data, and routes notifications based on complaint priority.

## Business Problem
Customer support teams receive multiple emails daily. Manually reviewing, categorizing, prioritizing, and tracking each request can be time-consuming and may delay urgent responses.

## Solution
This workflow automates the initial customer support process using AI and workflow automation.

## Workflow Architecture

**Gmail → AI by Zapier → Google Sheets → Paths by Zapier → Gmail Notifications**

### 1. Email Trigger
- Monitors incoming customer emails.
- Retrieves customer message details.

### 2. AI-Powered Analysis
AI analyzes the email and extracts:
- Customer name
- Customer email
- Order ID
- Issue category
- Priority level
- Customer sentiment
- Issue summary
- Suggested customer reply

### 3. Google Sheets Integration
Stores structured customer support records, including:
- Date
- Customer information
- Order ID
- Category
- Priority
- Sentiment
- Issue summary
- Suggested reply
- Status

### 4. Priority-Based Routing
Uses Paths by Zapier to route notifications:

**Path A – High Priority**
- Detects high-priority complaints.
- Sends an urgent email notification.
- Highlights the need for immediate attention.

**Path B – Medium / Low Priority**
- Handles medium- and low-priority requests.
- Sends a standard notification.

### 5. Email Notifications
The support team receives structured notifications containing the complaint details and AI-generated suggested reply.

Customer replies are not sent automatically; human review is required.

## Tools & Technologies
- Zapier
- Gmail
- AI by Zapier
- Google Sheets
- Paths by Zapier
- Workflow Automation
- AI Text Classification
- Data Extraction and Routing

## Testing & Validation
- Successfully tested incoming customer email.
- Verified AI extraction and classification on a sample complaint.
- Verified Google Sheets record creation and field mapping.
- Tested high-priority and standard notification paths.
- Verified email notification delivery.

## Business Value
- Reduces manual email review.
- Organizes customer support requests.
- Highlights urgent complaints.
- Improves visibility into customer issues.
- Keeps a structured support tracker.
- Supports human-reviewed customer communication.
