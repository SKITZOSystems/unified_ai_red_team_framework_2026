Small Biz AI Hardening: The 24-Hour Quick-Start Checklist
Version: 1.0 (SkitzOS Studio)

Most small businesses are "leaking" data through AI tools they don't even know their employees are using. Use this checklist to lock down your perimeter before you scale.

1. Inventory & Visibility (The "What are we even using?" Phase)
[ ] Audit the "Shadow AI": List every AI tool currently being used by your team (ChatGPT, Claude, Jasper, Canva Magic, etc.).

[ ] Map the Data Flow: Identify which tools have access to "Live" data (CRM, Email, Bank, or Customer PII).

[ ] Identify the "Mascots": Are you using an AI chatbot for customer service? If yes, this is your #1 attack surface.

2. Immediate "Kill-Switch" Settings (The "Stop the Bleed" Phase)
[ ] Disable Global Memory: Unless a task strictly requires it, turn off "Long-term Memory" or "Personalization" in AI settings to prevent Memory Poisoning.

[ ] Set Cost Ceilings: Go into your API dashboard (OpenAI, Anthropic, etc.) and set a hard monthly billing limit (e.g., $50). This kills Economic DoS attacks in their tracks.

[ ] Strict TTL (Time-To-Live): For any internal knowledge base (RAG), set a policy to re-verify or wipe the context every 30 days.

3. Boundary Hardening (The "Gatekeeper" Phase)
[ ] Data-Only Schemas: If your AI talks to other tools, ensure it can only send/receive specific data types (e.g., "Dates" or "Numbers")—no open text fields that could hide commands.

[ ] The "Human-In-The-Loop" Rule: Ensure no AI can "Send Email," "Move Money," or "Delete Data" without a human clicking a physical "Confirm" button.

[ ] Prompt Provenance: Ensure your team knows never to copy-paste documents from untrusted external sources directly into the AI for "summarization."

4. Employee Policy (The "Human Firewall" Phase)
[ ] The "No-PII" Rule: Issue a standing order: No customer passwords, social security numbers, or internal financial spreadsheets are to be uploaded to a public LLM.

[ ] The "Advice, Not Orders" Training: Train staff to treat AI output as a suggestion that needs verification, never as a final command.
