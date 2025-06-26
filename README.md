# integrations

This repository contains pre-built automation templates for integrating Explorium.ai's AI-powered data enrichment capabilities with popular workflow automation platforms like n8n and Make.

## What are these templates?

These templates are ready-to-use automation workflows that leverage Explorium.ai's AI technology to enrich prospect and company data. They help sales and marketing teams:

- **Automatically enrich contact data** with additional information like company details, social profiles, and contact information
- **Enhance lead quality** by adding firmographic data to prospects
- **Streamline sales outreach** with enriched prospect information
- **Search for prospects** using natural language queries
- **Integrate data across multiple platforms** like HubSpot, Salesforce, Google Sheets, and Slack

## How to use these templates

### For n8n Templates:
1. **Import the template**: Copy the template URL and import it into your n8n instance or download the file and upload it.
2. **Configure credentials**: Set up your API keys for the services you're connecting (Explorium.ai, HubSpot, Salesforce, etc.)
3. **Customize the workflow**: Adjust triggers, filters, and data mapping to match your specific needs
4. **Test and activate**: Run a test to ensure everything works correctly, then activate the workflow

### For Make Templates:
1. **Import the blueprint**: Use the blueprint URL to import the template into your Make account
2. **Set up connections**: Configure your service connections and API credentials
3. **Customize scenarios**: Modify the scenario to fit your specific use case and data requirements
4. **Deploy**: Activate the scenario to start the automation

## Template Accessibility

### n8n Templates

#### Lead Enrichment & Creation Workflows
- **`automate-contact-enrichment-from-hubspot-to-salesforce-using-exploriumai.json`**
  - **Purpose**: Automatically enriches contact data from HubSpot and syncs enriched information to Salesforce
  - **Use case**: When new contacts are added to HubSpot, automatically enrich them with additional data and update Salesforce records
  - **Key features**: Real-time enrichment, cross-platform synchronization, automated data updates

- **`automate-hubspot-to-salesforce-lead-creation-with-explorium-ai-enrichment.json`**
  - **Purpose**: Creates enriched leads in Salesforce from HubSpot contacts with additional AI-powered data
  - **Use case**: Convert HubSpot contacts into high-quality Salesforce leads with comprehensive prospect information
  - **Key features**: Lead scoring, firmographic data enrichment, automated lead creation

- **`automated-ai-lead-enrichment-salesforce-to-explorium-for-enhanced-prospect-data.json`**
  - **Purpose**: Enriches existing Salesforce leads with AI-powered prospect data from Explorium.ai
  - **Use case**: Enhance existing lead records with additional contact and company information
  - **Key features**: Bulk enrichment, data validation, enhanced lead profiles

#### Sales Outreach & Data Management
- **`automated-sales-outreach-using-event-triggered-data-with-explorium-mcp-and-slack.json`**
  - **Purpose**: Triggers sales outreach campaigns based on enriched prospect data with Slack notifications
  - **Use case**: Automatically notify sales teams about new enriched prospects and trigger outreach sequences
  - **Key features**: Event-driven automation, Slack integration, sales workflow automation

- **`enrich-company-firmographic-data-in-google-sheets-with-explorium-mcp.json`**
  - **Purpose**: Enriches company data in Google Sheets with firmographic information
  - **Use case**: Add company size, industry, revenue, and other firmographic data to your prospect lists
  - **Key features**: Spreadsheet automation, bulk data enrichment, company intelligence

- **`search-prospects-with-natural-language-using-explorium.ai-mcp.json`**
  - **Purpose**: Allows natural language search for prospects using AI-powered queries
  - **Use case**: Find prospects by describing what you're looking for in plain English
  - **Key features**: Natural language processing, intelligent prospect discovery, flexible search criteria

### Make Templates

#### Prospect Enrichment
- **`enrich-prospect.blueprint.json`**
  - **Purpose**: Enriches individual prospect data with additional contact and company information
  - **Use case**: Add missing information to prospect records or validate existing data
  - **Key features**: Single prospect enrichment, data validation, contact verification

#### Company Enrichment
- **`enrich-company.blueprint.json`**
  - **Purpose**: Enriches company data with firmographic and business intelligence
  - **Use case**: Get comprehensive company information including size, industry, technology stack, and more
  - **Key features**: Company intelligence, firmographic data, business insights

- **`enrich-company-with-multiple-enrichments.blueprint.json`**
  - **Purpose**: Performs multiple types of enrichment on company data for comprehensive insights
  - **Use case**: Get the most complete picture of a company with multiple data sources and enrichment types
  - **Key features**: Multi-source enrichment, comprehensive company profiles, advanced analytics

## Getting Started

1. **Choose your platform**: Select either n8n or Make based on your existing workflow automation setup
2. **Pick the right template**: Identify which template best matches your use case
3. **Set up Explorium.ai**: Ensure you have an Explorium.ai account and API credentials
4. **Configure integrations**: Set up the necessary service connections (HubSpot, Salesforce, etc.)
5. **Test thoroughly**: Run test scenarios to ensure data flows correctly
6. **Go live**: Activate your automation and monitor its performance

## Support

For questions about these templates or Explorium.ai integration, please refer to the Explorium.ai documentation or contact their support team.

for more information: https://developers.explorium.ai
