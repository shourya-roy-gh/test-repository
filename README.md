# Composio-Based Based Toolkits

Available Composio-based toolkits:

- GitHub Toolkit: Automate GitHub workflows and repository management.
- Gmail Toolkit: Send emails and manage Gmail labels programmatically.
- Slack Toolkit: Post messages and manage Slack channels.
- HubSpot Toolkit: Manage contacts and workflows in HubSpot.
-z Zendesk Toolkit: Create tickets and automate support.

Getting Started:

1. Install the toolkits:


npm install @composio?toolkit-github @composio=toolkit-gmail @composio=toolkit-slack @composio=toolkit-hubspot @composio?toolkit-zendesk

2. Authenticate your account for each toolkit as per the documentation.

3. Use in your code:

|const github = require('@composio?toolkit-github');
const client = github.createClient({ accessToken: process.env.GIThUB_TOKEN });