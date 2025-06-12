# integrations

## Template Accessibility

After being uploaded by the GitHub Actions workflow, the n8n templates are accessible at the following URLs:

- Base URL: `https://cdn.explorium.ai/integrations/n8n/`
- Individual templates:
  - `https://cdn.explorium.ai/integrations/n8n/automate-contact-enrichment-from-hubspot-to-salesforce-using-exploriumai.json`
  - `https://cdn.explorium.ai/integrations/n8n/automate-hubspot-to-salesforce-lead-creation-with-explorium-ai-enrichment.json`
  - `https://cdn.explorium.ai/integrations/n8n/automated-ai-lead-enrichment-salesforce-to-explorium-for-enhanced-prospect-data.json`
  - `https://cdn.explorium.ai/integrations/n8n/automated-sales-outreach-using-event-triggered-data-with-explorium-mcp-and-slack.json`
  - `https://cdn.explorium.ai/integrations/n8n/enrich-company-firmographic-data-in-google-sheets-with-explorium-mcp.json`
  - `https://cdn.explorium.ai/integrations/n8n/search-prospects-with-natural-language-using-explorium.ai-mcp.json`

The repository structure is preserved in the S3 bucket, so any new templates added to the repository will be available at their corresponding path after the workflow runs.

## Deployment

Templates are automatically uploaded to the S3 bucket whenever changes are pushed to the main branch. You can also manually trigger the upload process from the GitHub Actions tab in the repository.
