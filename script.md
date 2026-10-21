# Meta's Muse: The Future of AI Coding and Security

**Topic:** Meta's Muse and AI Coding Agents  
**Target Duration:** 2:30–3:00 minutes  
**Team Size:** 4 Members

---

[0:00-0:18] ## Hook 
For years, AI chatbots answered your questions and left the work to you. On September 8, 2026, Meta launched f  Muse, a personal AI agent that does the work itself. It opens a browser, fills out forms, and acts on your behalf.

[0:18-0:46] ## What Muse is 
Muse is available to adults in the US, and it connects to apps you already use: email, calendars, payments, shopping, even health apps. You reach it through an app, the web, or WhatsApp, and it keeps working after you close it. There's a free tier, with paid plans at $20 and $100 a month. But an agent with access to your inbox and your wallet raises an obvious question: why trust it?

[0:46-1:04] 
Answer one: where it lives Meta's first answer is where Muse runs. Each user gets a dedicated cloud computer, the Muse Secure VM, with its own browser. The agent works inside a sealed container, and the safety services run outside it.

[1:04-1:24] 
Answer two: Sentinel Second is Sentinel, a separate security agent on the same machine. Muse can only propose actions. Sentinel decides whether to allow, deny, or ask you, and it checks every outgoing network request. Approvals appear in the Muse app, not the chat, so the agent can't talk you into them.

[1:24-1:50] 
Answer three: credentials and payments Third, your logins. Muse hands the agent stand-in tokens, and the real credentials are swapped in only after Sentinel approves. So even a malicious email or web page can't trick the agent into leaking a password it never had. Payments use a one-time card from Link by Stripe, tied to one merchant and one amount, and Meta says you approve every purchase.

[1:50-2:35] 
The catch But this is Meta's own description, and early coverage said it needs outside scrutiny. Meta admits Muse isn't immune to attack, and that prompt injection is still an open problem. Meta can also still access your VM when necessary to support, secure, or operate the service. An encrypted Confidential VM that even Meta can't open is promised for later this year, but it hasn't shipped. Training on your interactions is on by default, though you can opt out. Meta says Muse data stays out of its ad systems, although browsing may still influence your ads. And Meta's privacy history is why many people are asking whether to trust it.

[2:35-2:50] 
Close Agents that act could save real time, but they're only as safe as the access you give them. Muse answers part of the trust question. The rest depends on whether Meta delivers. Time will tell.
