# AI-Powered-Gmail-Triage-Automated-Spam-Promotional-Filtering-Workflow
Engineered an end-to-end autonomous email classification pipeline using n8n and Google Gemini to automatically detect, categorize, and filter promotional spam out of the primary inbox in real time. The workflow combines agentic AI processing with structured outputs to maintain high precision without manual intervention.

Key Features & Implementation :

Real-Time Event Triggering: Listens continuously for new unread messages via the Gmail API trigger to initiate immediate evaluation upon email arrival.

Agentic Contextual Classification: Utilizes an AI Classifier Agent powered by the Google Gemini Chat Model to analyze full email context, intent, and semantics, surpassing traditional rule- or keyword-based filters.

Deterministic Parsing: Implemented a Structured Output Parser to guarantee that LLM evaluations conform to strict schema boundaries, preventing hallucination errors during downstream decision-making.

Automated Inbox Cleanup: Executes conditional logic nodes (Is Promotional Spam?) to evaluate threat/spam signals and automatically updates email labels via the Gmail API to move flagged items directly to Spam.

Key Technical Achievements :

Integrated zero-code/low-code workflow orchestration with state-of-the-art LLMs.

Enforced structured output constraints on LLMs for reliable automated branching.

Minimized primary inbox clutter by automating repetitive email triage tasks.

<img width="1295" height="577" alt="Screenshot 2026-09-09 003441" src="https://github.com/user-attachments/assets/503a27ee-0c91-4918-99c2-251d9f7987e1" />
