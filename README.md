# Elias Skora

I build and operate self-hosted AI agent systems, and before that I spent three years carrying a quota. GTM engineering is where those two stop being separate jobs.

Most of what I have built runs privately, at least for now, which limits what a profile page can honestly show. What it can show is the part that is checkable.

### Running

Talaria is a Python daemon on macOS: one agent core carrying shared memory, skills, trust rules across a CLI, Telegram, an installable web app, and four model bridges (Anthropic, OpenAI, Gemini, local Ollama). Every irreversible action passes a five-level trust gradient that ends in a hand-typed confirmation. Its MCP server answers at `mcp.eskora.co/mcp`, where identity is enforced at the ASGI seam, before any protocol traffic reaches the server. An unauthenticated request gets a 401. That is the check, if you want to make it.

Unbelieve is a Next.js and Supabase app at `app.unbelieve.app`. An AI interview ladders down to a testable belief, and deterministic code, never the model, keeps score.

### In the open

The one I build in public is [**flight-recorder**](https://github.com/e-skora/flight-recorder), an observability layer for automated revenue decisions. It preserves the evidence behind a prioritization call at the moment the call is made, so the same decision can be replayed months later against what was actually known at the time. The fields that fed it get overwritten in the months after. A preserved record does not. Python, FastAPI, SQLite, no JavaScript framework.

It covers one decision class. The repository says which parts are not built.

### The other half

I was a BDR at Great Question and then a mid-market account executive at Paychex. Roughly 500 outbound touches a week across Apollo, Orum, Sales Navigator, averaging 15 sales-qualified meetings a month against a target of 10, then 40 to 60 open opportunities at a time while self-sourcing 60 percent or more of the pipeline. The part I kept wanting more of was finding where the process leaked and fixing it. That is most of why the repositories exist.

Portland, Oregon · Open to relocation · [es@eskora.co](mailto:es@eskora.co) · [eskora.co](https://eskora.co) · [LinkedIn](https://linkedin.com/in/eliassskora)
