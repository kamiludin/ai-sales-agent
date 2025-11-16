# AI Sales Agent with n8n, Typeform, Airtable, and Slack

Building an AI Sales Agent with Human-in-the-Loop Using n8n in Just a Few Minutes
<img src="AI Sales Agent.jpg">

## Introduction

Converting leads effectively requires more than just capturing form data. Traditional automation often:

- Sends the same follow-up email to every lead.

- Doesn’t classify or prioritize leads based on interest or timing.

- Lacks human oversight before taking action.

- Can’t dynamically revise content based on feedback.

Traditional automations act like a machine: they execute tasks blindly. AI Sales Agents, on the other hand, act more like human sales reps — classifying, reasoning, generating personalized emails, and improving through human feedback.

In this project, we integrate lead classification, AI-generated emails, human-in-the-loop validation, and cross-platform communication using tools like n8n, Typeform, Airtable, Slack, and SMTP email.

---

## Key Features

- 🤖 AI-Powered Lead Scoring: Classifies leads into Cold, Warm, or Hot based on “Campaign Timeline”.

- 📥 Typeform Integration: Captures structured lead data through a simple form.

- 📊 Airtable CRM Database: Automatically stores and updates lead data.

- ✉️ Dynamic Email Generation: Uses OpenAI to create custom emails based on lead type.

- 🔁 Human-in-the-Loop Workflow: Slack-based review before sending follow-up emails.

- 📤 SMTP Email Delivery: Sends finalized emails to any lead's email address (not limited to Gmail).



---

## How it Works

1. User fills in the Typeform, including “When do you plan to start your next content campaign?”.

2. n8n classifies the lead (Cold/Warm/Hot) based on the response.

3. Lead data is saved into Airtable with metadata like created time and lead status.

4. AI Agent generates a personalized email using the classification result.

5. Slack sends a preview of the email to the sales team for approval or revision.

6. If approved, the email is sent using SMTP via the “Send Email” node.

7. If denied, a secondary AI agent revises the email based on human feedback, and resends for approval.

---


## Demo Video

https://youtu.be/9MN61VzGjhM?si=2HNhSBJfEWQ2XeVS


Thank You...
