<div align="center">

# 🔗 Explorium.ai Integration Templates

[![Platform](https://img.shields.io/badge/platform-n8n%20%7C%20Make-blue?style=for-the-badge)](https://n8n.io)
[![Templates](https://img.shields.io/badge/templates-9%20ready--to--use-green?style=for-the-badge)](https://github.com/explorium-ai/integrations-templates)
[![License](https://img.shields.io/badge/license-MIT-yellow?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/status-maintained-brightgreen?style=for-the-badge)](https://github.com/explorium-ai/integrations-templates)

**Pre-built automation templates for AI-powered data enrichment with n8n and Make**


</div>



## 🎯 What are these templates?

This repository contains **ready-to-use automation workflows** that leverage [Explorium.ai](https://explorium.ai)'s AI technology to enrich prospect and company data. Perfect for sales and marketing teams looking to:

- 🤖 **Automatically enrich contact data** with company details, social profiles, and contact information
- 📈 **Enhance lead quality** by adding firmographic data to prospects  
- 🎯 **Streamline sales outreach** with enriched prospect information
- 🔍 **Search for prospects** using natural language queries
- 🔗 **Integrate data across multiple platforms** (like HubSpot, Salesforce, Google Sheets and Slack)

---

## 🚀 Getting Started

### Prerequisites
- [Explorium.ai](https://explorium.ai) account with API credentials
- n8n or Make account
- Integration platform credentials (HubSpot, Salesforce, etc.)

### Quick Setup

<details>
<summary><strong>📥 For n8n Templates</strong></summary>

1. **Import the template**
   - Copy the template URL from the table below
   - Paste into n8n's "Import from URL" feature
   - Or download the JSON file and upload manually

2. **Configure credentials**
   - Set up API keys for Explorium.ai
   - Configure service connections (HubSpot, Salesforce, etc.)

3. **Customize & test**
   - Adjust triggers, filters, and data mapping
   - Run test scenarios to verify functionality
   - Activate the workflow

</details>

<details>
<summary><strong>📥 For Make Templates</strong></summary>

1. **Import the blueprint**
   - Copy the blueprint URL from the table below
   - Paste into Make's "Import from URL" feature

2. **Set up connections**
   - Configure service connections
   - Add API credentials for all services

3. **Customize & deploy**
   - Modify the scenario for your use case
   - Test thoroughly before activation
   - Deploy the scenario

</details>

---

## 📚 Templates Directory

### 🔄 n8n Templates

#### Lead Enrichment & Creation Workflows

| Template | Description | Integrations | URL |
|----------|-------------|--------------|-----|
| **HubSpot → Salesforce Contact Enrichment** | Automatically enriches contact data from HubSpot and syncs to Salesforce | ![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white) ![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat&logo=salesforce&logoColor=white) | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/refs/heads/main/n8n/automate-hubspot-to-salesforce-lead-creation-with-explorium-ai-enrichment.json) |
| **HubSpot Lead Enrichment** | Enriches existing HubSpot leads with AI-powered prospect data | ![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white) | [🔗 URL](https://github.com/explorium-ai/integrations-templates/blob/main/n8n/automated-lead-enrichment-hubspot-for-enhanced-prospect-data.json) |
| **Salesforce Lead Enrichment** | Enriches existing Salesforce leads with AI-powered prospect data | ![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat&logo=salesforce&logoColor=white) | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/n8n/automated-ai-lead-enrichment-salesforce-to-explorium-for-enhanced-prospect-data.json) |

#### Sales Outreach & Data Management

| Template | Description | Integrations | URL |
|----------|-------------|--------------|-----|
| **Sales Outreach with Slack** | Triggers sales outreach campaigns with Slack notifications | ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white) ![AI](https://img.shields.io/badge/AI-000000?style=flat&logo=openai&logoColor=white) | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/n8n/automated-sales-outreach-using-event-triggered-data-with-explorium-mcp-and-slack.json) |
| **Google Sheets Company Enrichment** | Enriches company data in Google Sheets with firmographic information | ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=google-sheets&logoColor=white) | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/n8n/enrich-company-firmographic-data-in-google-sheets-with-explorium-mcp.json) |
| **Monday.com Lead Enrichment & Email Drafting** | Enriches Monday.com leads and drafts personalized emails using AI-powered research | ![Monday.com](https://img.shields.io/badge/Monday.com-FB0D93?style=flat&logo=monday.com&logoColor=white) ![AI](https://img.shields.io/badge/AI-000000?style=flat&logo=openai&logoColor=white) | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/n8n/enrich-monday.com-leads-and-draft-personalized-emails-with-explorium-mcp-and-gpt.json) |
| **Natural Language Prospect Search** | Search for prospects using AI-powered natural language queries | ![AI](https://img.shields.io/badge/AI-000000?style=flat&logo=openai&logoColor=white) | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/n8n/search-prospects-with-natural-language-using-explorium.ai-mcp.json) |

### ⚙️ Make Templates

#### Prospect & Company Enrichment

| Template | Description | URL |
|----------|-------------|-----|
| **Prospect Enrichment** | Enriches individual prospect data with contact and company information | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/make/enrich-prospect.blueprint.json) |
| **Company Enrichment** | Enriches company data with firmographic and business intelligence | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/make/enrich-company.blueprint.json) |
| **Multi-Source Company Enrichment** | Performs multiple types of enrichment for comprehensive company insights | [🔗 URL](https://raw.githubusercontent.com/explorium-ai/integrations-templates/main/make/enrich-company-with-multiple-enrichments.blueprint.json) |


---

## 📖 Documentation & Support

- **📚 [Explorium.ai Developer Docs](https://developers.explorium.ai)** - Complete API documentation
- 📧 **Support**: Contact [Explorium.ai support team](mailto:support@explorium.ai)
