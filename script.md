# Meta's Muse: The Future of AI Coding and Security

**Topic:** Meta's Muse and AI Coding Agents  
**Target Duration:** 2:30–3:00 minutes  
**Team Size:** 4 Members

---

## The Hook 
For the last few years, AI chatbots have exploded, answering your questions, but left the work to you. This past year, on September 8, 2026, Meta launched Muse, the "personal AI agent that does the work itself". It can open a browser, it can fill out your forms, over all, it can do tasks and act on your behalf.

## How do you use it?
Muse is available to adults in the US, and it connects to apps you already use: email, calendars, payments, shopping, even health apps. You reach it through an app, the web, or WhatsApp, and it keeps working after you close it. There's a free tier, with paid plans at $20 and $100 a month. But now here's the dilemma. An artificial intelligence agent with access to your personal inbox and your own wallet raises the obvious question: why trust it? This leads us to:

## Answer one: Where it lives 
Meta's first answer is where Muse runs, where it lives. Each user gets a dedicated cloud computer, the Muse Secure VM, with its own browser. The agent works inside a sealed container, and the safety services run outside around it.

## Answer two: Sentinel 
Second is Sentinel, a separate security agent on the same machine. Muse can only propose actions. Sentinel decides whether to allow, deny, or ask you, and it checks every outgoing network request. Approvals appear in the Muse app, not the chat, so the agent can't try to convince you, or talk you into them.

## Answer three: Credentials and payments 
Third is your logins. Muse hands the agent "stand-in tokens", and the real credentials are swapped in only after Sentinel approves. So even a malicious email or web page can't trick the agent into leaking a personal password if it never had it in the first place. Aside from that, on the topic of money. Payments use a one-time card from Link by Stripe, this is tied to one merchant and one amount, and Meta says you give it the green light every purchase before it approves.

## The Catch 
Muse’s security features come mostly from Meta itself, and some risks remain: prompt injection is unsolved, Meta can still access your VM when needed, and your chats train its AI by default unless you opt out. Meta’s privacy history makes trust the real question. Agents that act can save time, but they’re only as safe as the access you give them.
