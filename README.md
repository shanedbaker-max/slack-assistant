Slack Assistant

This repository contains my personal Slack assistant application. It will connect Slack to my AWS backend so I can:

- Ask knowledge questions powered by Amazon Q Business or Bedrock
- Run job search automation workflows
- Log learning progress
- Summon my custom GPT inside Slack
- Retrieve information from my Notion or AWS knowledge sources
- Trigger AWS Lambda functions or workflows
- Support future enterprise demos (HR, IT, Ops assistants)

Core planned components:

1. Slack App Configuration
   - Slash commands
   - Event subscriptions
   - OAuth and permissions
   - Bot user and interactions

2. AWS Backend Integration
   - POST /ask_knowledge
   - POST /log_event
   - POST /slack_interaction

3. Infrastructure (future)
   - Lambda functions
   - API Gateway routes
   - DynamoDB logging
   - Slack signing secret validation

Directory structure (to be added next):

src/     - main Slack bot logic
docs/    - diagrams, screenshots
tests/   - unit tests

More features will be added as the system grows.
