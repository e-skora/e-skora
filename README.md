# Elias Skora

I build software that makes automated systems accountable for their decisions.

My work spans AI agents, shared memory, decision infrastructure, and the controls that keep people in charge of increasingly autonomous software. The common thread is simple: when a system makes a decision or takes an action, someone should be able to find out why, inspect what happened, and change what happens next.

I came to engineering through revenue and operations. Before building software, I worked in business development at Great Question, sold payroll and HR technology at Paychex, and managed operations for a nonprofit and restaurants. Different industries, same recurring problem: important context disappeared between decisions, systems, and the people responsible for the outcome.

That experience shapes what I build.

### Flight Recorder

*Decision history and replay for revenue systems*

[Live demo](https://flight-recorder.app/demo) · [Source code](https://github.com/e-skora/flight-recorder) · Python, FastAPI, SQLite

Sales software decides which accounts get attention, what triggers an outreach sequence, and what happens next. Flight Recorder preserves the evidence and rules behind those decisions.

Teams can reconstruct a decision, see exactly what informed it, and test how different rules would have changed the outcome.

The public demo includes 241 sample accounts. Change the logic, replay the decisions, and see what changes.

### Aeverum

*Shared memory across AI models*

[aeverum.co](https://aeverum.co/)

AI assistants are good at generating answers and remarkably bad at maintaining a consistent understanding of the person using them.

Aeverum is a shared memory system designed to work across models and tools. It keeps track of where information came from, evaluates what deserves to be remembered, and provides a controlled way to correct or forget it.

The goal is continuity without surrendering ownership of your own context.

### Petasos

*Safety controls for autonomous actions*

[petasos.io](https://petasos.io/)

AI agents can do more than answer questions. They can send messages, modify files, and make changes outside the conversation.

Petasos is a control layer between an agent's proposed action and its execution. Explicit rules determine what can proceed, what needs human approval, and what must be blocked.

Its focus is on enforcing those boundaries, recording decisions, and handling uncertainty when an action's outcome cannot be confirmed.

### Talaria

*Personal multi-model agent system*

Talaria is the agent system I use in my own daily work.

It coordinates work across Anthropic, OpenAI, Gemini, and local models, routes tasks between them, and provides fallback paths when a provider is unavailable.

The more important part is what it doesn't do freely: irreversible actions require explicit confirmation.

A public version is in development.

### Consilience Operations House

Flight Recorder, Aeverum, and Petasos are developed under [Consilience Operations House](https://consilienceops.com/), the software company I founded to build systems that are easier to inspect, govern, and trust.

I'm particularly interested in agent infrastructure, applied AI, developer tools, and the places where software meets real operational responsibility.

Portland, Oregon

[Website](https://eskora.co/) · [LinkedIn](https://linkedin.com/in/eliassskora) · [Email](mailto:es@eskora.co)
