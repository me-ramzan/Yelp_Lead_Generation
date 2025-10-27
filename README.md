# Yelp_Lead_Generation
## Overview
This is an automated web scraping and data collection system that identifies real estate investors and rental property professionals from online directories, extracts their business information, and builds a structured prospect database for sales and marketing purposes.

## Key Functionality
1. Automated Web Scraping
Uses Apify API to crawl business directories and listings

Targets specific keywords: "Real Estate" and "Rental Investor"

Focuses on geographic locations: Texas and Florida

Crawls multiple pages (max 3 pages) for comprehensive data

2. Intelligent Data Processing
Monitors scraping job status with polling mechanism

Implements conditional logic to wait for successful completion

Handles failed jobs with retry capability

Extracts structured data from raw scraping results

3. Prospect Database Management
Stores extracted data in Google Sheets with fields including:

Client Name (fullName)

Title/Username (username)

Company Name (businessCategoryName)

Contact information (Email, Phone, Address, State)

Geographic operations coverage

4. Workflow Automation
Manual trigger initiation with automated execution

Status monitoring with wait intervals

Sequential data processing pipeline

Error handling and retry logic

## Primary Use Cases
1. Real Estate Service Providers
Mortgage brokers seeking investor clients

Insurance companies targeting rental property owners

Contractors looking for real estate investor customers

Property management service sales

2. Investment Companies
Private equity firms sourcing real estate opportunities

REITs identifying potential acquisition targets

Hard money lenders prospecting borrowers

3. Marketing & Sales Teams
B2B sales teams in real estate adjacent industries

Marketing agencies serving real estate sector

Lead generation services for property-related businesses

4. Business Development
Partnership opportunities with real estate investors

Networking with rental property professionals

Market research on real estate investment landscape

## Technical Value Proposition
This system automates the tedious process of manually searching for real estate investors across multiple directories, ensures consistent data extraction, creates a structured database for CRM integration, and provides a scalable solution for ongoing prospect generation without manual effort. The geographic targeting (Texas, Florida) makes it particularly valuable for region-specific business development strategies.

