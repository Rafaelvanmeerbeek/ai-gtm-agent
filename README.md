# AI GTM Agent

AI-powered go-to-market automation system built with n8n, OpenAI API, APIs and structured workflows.

## Overview

This project demonstrates how AI agents can be used to automate real GTM workflows such as lead qualification, enrichment, prioritization and follow-up.

The workflow receives a lead, processes the data, uses an LLM to evaluate the opportunity, produces structured output and routes the lead based on business logic.

## Workflow

Lead Source  
↓  
Webhook  
↓  
n8n  
↓  
Data Validation  
↓  
API Enrichment  
↓  
OpenAI API  
↓  
Structured JSON Output  
↓  
Lead Qualification  
↓  
Database  
↓  
Follow-up Action

## Tech Stack

- n8n
- OpenAI API
- JavaScript
- REST APIs
- Webhooks
- JSON
- PostgreSQL
- MongoDB
- Pinecone
- RAG
- LLM workflows

## Example Output

```json
{
  "lead_score": 87,
  "qualification": "high_priority",
  "company_type": "ecommerce",
  "estimated_fit": "strong",
  "recommended_action": "personalized_outreach"
}
