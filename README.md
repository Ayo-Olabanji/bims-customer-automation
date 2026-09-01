# BIMS Customer Automation System

> AI-powered customer enquiry, lead qualification and sales workflow automation built for BIMS Gadgets & Automobiles.

## Overview

The BIMS Customer Automation System is an end-to-end business automation solution designed to help BIMS capture customer enquiries, organise sales opportunities, prioritise leads and improve staff follow-up.

The system connects a mobile-friendly customer enquiry interface to an automated backend where enquiries are processed, classified and stored for sales operations.

## The Business Problem

Retail businesses can receive multiple customer enquiries every day. Without a structured system, valuable leads can be forgotten, follow-ups delayed and management may have limited visibility into ongoing deals.

The BIMS system was designed to:

- Capture customer enquiries automatically
- Organise customer and sales information
- Identify priority leads
- Track enquiry and deal status
- Support staff follow-ups
- Notify staff of relevant activity
- Give management better visibility
- Reduce repetitive manual work

## System Architecture

Customer Enquiry Form  
↓  
Secure Webhook  
↓  
n8n Automation Engine  
↓  
Data Processing & Validation  
↓  
AI-Assisted Lead Classification  
↓  
Structured Data Storage  
↓  
Staff / Sales Control  
↓  
Notifications & Follow-Up

## Core Features

### Customer Enquiry Capture
Customers submit enquiries through a simple mobile-friendly interface. The information is automatically transferred into the automation workflow.

### AI-Assisted Lead Classification
Incoming enquiries are analysed and organised into priority categories such as Hot, Warm and Normal to help sales staff focus attention appropriately.

### Sales Tracking
Customer enquiries and sales opportunities can be tracked through different stages, helping staff understand what requires action.

### Staff Notifications
The system can notify relevant staff about incoming enquiries and important changes without requiring constant manual checking.

### Follow-Up & Recovery
The architecture supports customer follow-ups and recovery of enquiries that might otherwise become lost opportunities.

### Management Visibility
Structured sales information gives management better visibility into customer enquiries and ongoing deals.

### Error Handling
Dedicated error-handling logic improves workflow reliability and makes automation failures easier to identify.

## Technology Stack

- n8n
- Railway
- REST APIs
- Webhooks
- JSON
- AI API integrations
- n8n Data Tables
- Gmail / notification integrations
- GitHub

## Engineering Approach

The system combines traditional automation rules with AI where language interpretation adds value.

Deterministic business rules are used where possible to keep important operations predictable and reduce unnecessary AI API costs.

## Security & Privacy

This public repository intentionally excludes all production secrets and private business information.

No API keys, access tokens, webhook secrets, customer personal information, authentication credentials or private production URLs are published here.

## Project Status

The core automation system has been built and deployed. Further production work includes system polishing, staff onboarding, testing and communication-channel integrations.

## Business Value

The purpose of this system is not simply to automate tasks.

It is designed to help BIMS respond faster, reduce missed sales opportunities, improve follow-up discipline and give management greater visibility while reducing the need to manually supervise every customer enquiry.

---

## Built By

**Ayo Olabanji**  
Founder, Mindset Labs AI  
AI Systems & Automation