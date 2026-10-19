# Research Notes

## Topic
Investigation of Meta's personal AI agent 'Muse' and a comparative analysis of its features against major AI tools (ChatGPT, Gemini, OpenClaw).

## Key Facts

### Muse (Meta)
* **Product Overview:** Meta's personal AI agent, launched on September 8, 2026, in the US and Canada. It is available on the web (muse.ai), as well as through iOS, Android, and Mac apps. Expansion into regions like Europe has been delayed due to strict regulatory compliance required for AI products handling personal data.
* **Model & Pricing:** Powered by Muse Spark 1.3, part of Meta's Muse model family. The more capable sibling, 'Muse Wonder' (announced October 12, 2026), runs on premium paid plans, which include a $50/month "Muse Code" subscription and API usage costs ($4 per 1 million input tokens / $20 per 1 million output tokens).
* **How It Runs:** Instead of a simple chat interface, Muse assigns every user their own dedicated, persistent computer. This is an independent Linux machine equipped with a real browser, terminal, and filesystem that securely stores the agent's memory and maintains state between conversations.
* **Core Capabilities:**
  * **Proactive Design:** Runs scheduled background work (e.g., a 7 AM briefing) and delegates multi-step tasks to subagents that continue working while the user is away.
  * **Live Web Browsing:** Live web browsing (including securely maintaining active sign-ins to websites using its dedicated machine), code execution, and file management.
  * **Integrations:** Connectors to external services like Gmail, Google Calendar, and Notion.
* **User Interaction:** Retains a persistent memory of user instructions and joint activities to eliminate repetitive explanations. To ensure safety, it always requests user confirmation before executing actions that are difficult to undo. The default name is 'Muse', but it can be changed at any time.

## Comparison

### ChatGPT (OpenAI)
* **Features:** The broadest all-rounder supporting chat, voice, vision, image and video generation (Sora), browsing, and Deep Research. Pricing tiers include Free, Plus ($20/mo), and Pro ($200/mo).
* **Agent Capabilities:** Evolved from Operator into "agent mode" and now "Work" mode. For complex tasks, it gets assigned its own virtual computer with a browser and terminal. However, unlike Muse's dedicated and always-on Linux machine, ChatGPT's environment is dynamically spun up for specific multi-step tasks.
* **Other Details:** Offers connectors for Gmail, Drive, Notion, and GitHub, along with persistent memory and custom GPTs. It remains fundamentally a chatbot first and an agent second.

### Gemini (Google)
* **Features:** Boasts the deepest integration with Google Workspace (Gmail, Drive, Docs, Calendar) with over 1 billion monthly users.
* **Agent Capabilities:** The "Gemini agent" was announced on October 8, 2026. It is a universal work agent driven by "objectives" rather than simple instructions. It can process long-running, multi-step jobs and intelligently routes tasks across both Google's Gemini models and Anthropic's Claude models.
* **Enterprise Integration & Cost:** Features "coworker agents" that act under their own identity. Each coworker agent receives a functional Workspace account with an `@agents.company.com` email address, calendar, Drive storage, and a directory entry. Every action is logged to an audit trail attributed directly to the agent. While currently in private preview with no published standalone price, reports indicate there is no additional charge for organizations where Gemini Enterprise is already available.

### OpenClaw
* **Features:** An open-source framework for personal AI agents created by Peter Steinberger. Steinberger notably relocated to the US and joined OpenAI in early 2026, citing that European regulations were stifling AI development.
* **Agent Capabilities:** Features a messaging-first interface, interacting autonomously with users through platforms like WhatsApp, Telegram, and Discord. It can execute shell commands, manage files, operate on schedules, and remember context across sessions.
* **Infrastructure & Models:** Because OpenClaw is a framework and not a model itself, users self-host it on their own machines and orchestrate their preferred backend models (such as GPT, Claude, Gemini, or local open-weights models). The specific system requirements (like VRAM) and performance limits depend entirely on the model the user chooses to plug into the framework. Free software gives full data control, but the user is completely responsible for setup, security, and hardware infrastructure.
