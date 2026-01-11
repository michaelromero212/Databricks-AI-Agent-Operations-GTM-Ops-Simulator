# Sample Input Files for Testing

This folder contains ready-to-upload test files for each task type supported by the AI Agent.

## 📁 Files

| File | Task Type | Description |
|------|-----------|-------------|
| `01_lead_summary_example.txt` | Lead Summary | New prospect from webinar with qualification details |
| `02_follow_up_example.txt` | Follow-Up Suggestion | Post-demo follow-up for Enterprise account |
| `03_risk_analysis_example.txt` | Risk Analysis | At-risk deal with multiple warning signs |
| `04_data_hygiene_example.txt` | Data Hygiene Check | CRM records with quality issues |

## 🚀 How to Use

1. Navigate to the web app: `http://localhost:8000/upload`
2. Select the matching **Task Type** from the dropdown
3. Click **Choose File** and select one of these sample files
4. Click **Upload & Process**
5. Review the agent's response

## 💡 Tips

- Each file is designed to showcase realistic GTM/Sales Ops scenarios
- The agent will extract context and generate a structured response
- Without `HF_TOKEN`, the agent uses mock responses (still useful for testing UI flow)
- Files are saved to `data/uploaded_inputs/` after processing
