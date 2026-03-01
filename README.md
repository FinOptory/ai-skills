# SAP RISE Contract Governance — AI Assistant

**Free AI instructions that turn Claude, ChatGPT, Gemini, or Copilot into a specialized advisor for SAP RISE contracts.**

This repository contains a skill file — a set of expert instructions you paste into any AI assistant. It transforms a general-purpose LLM into a knowledgeable advisor for SAP RISE commercial governance, from the customer's perspective.

---

## What this assistant knows

- **RISE contract structure:** ACV composition, FUE metrics, BTP credits, Digital Access, bundled and unbundled components — explained clearly and practically.
- **Commercial mechanisms and risks:** Pricing models, derived charges, fair-use policies, overage rules, and the most common pitfalls in user classification and cost escalation.
- **Renewal governance:** Timelines, negotiation levers, typical SAP tactics, exit scenarios, and how to prepare 12-18 months ahead.
- **Compliance and audit:** How SAP audits work under RISE, typical findings, and how to stay ahead of them.
- **July 2025 packaging changes:** The shift from tiered bundles to a la carte pricing, what was unbundled, and how it affects renewals and TCO.

---

## Installation

The file [`SAP-RISE-Contract-Governance.skill.md`](./SAP-RISE-Contract-Governance.skill.md) contains all instructions. Copy its entire content and paste it into your AI assistant as described below.

### Claude (Anthropic)

1. Open a **Project** at [claude.ai](https://claude.ai).
2. Go to **Project Knowledge** (or **Custom Instructions**).
3. Paste the full content of the skill file.
4. All conversations in this project now use SAP RISE expertise.

### ChatGPT (OpenAI)

1. Go to **Settings** > **Personalization** > **Custom Instructions**.
2. Paste the content under "What would you like ChatGPT to know about you?"
3. Alternatively: Create a dedicated **Custom GPT** with the skill file as its instructions.

### Gemini (Google)

1. Open **Gems** and create a new Gem.
2. Paste the skill file content as the Gem's instructions.
3. Alternatively: Start a conversation and paste the content as context at the beginning.

### Microsoft Copilot

1. Paste the content as a system prompt or custom instructions in Copilot Chat.
2. In enterprise setups: Use the skill file as a context document.

### Any other LLM

The skill file works with any model that supports custom instructions or system prompts — including Mistral, Llama, Perplexity, and others. Paste the content as instructions or system prompt.

---

## Example prompts

Once the instructions are loaded, try questions like these:

- *"What should I watch out for in my RISE contract?"*
- *"How is the ACV composed, and which components are negotiable?"*
- *"Our renewal is in 14 months — what should we do now?"*
- *"What are the risks with Digital Access if we connect a supplier portal?"*
- *"Create a board-level summary of our contract situation."*
- *"What changed with the SAP packaging update in July 2025, and how does it affect our renewal?"*

---

## What this assistant cannot do

This assistant provides **general knowledge** about SAP RISE contracts — structures, mechanisms, checklists, and strategic guidance. It cannot:

- **Analyze your specific contract** — it does not have access to your data.
- **Track your actual ACV, FUE utilization, or BTP consumption.**
- **Model your specific renewal scenarios** with real numbers.
- **Provide legal advice.**

For contract-specific analysis, continuous governance, and data-driven renewal preparation — where an AI works with your actual structured contract data — consider a dedicated solution like **[FinOptory](https://finoptory.ai)**.

---

## License

MIT License — free to use, share, and adapt. See [LICENSE](./LICENSE).

---

## Created by

**[FinOptory](https://finoptory.ai)** — SAP RISE Contract Governance as a Managed Service.

FinOptory provides continuous contract monitoring, renewal preparation, and cost optimization for SAP RISE customers as a managed service.

Questions or feedback: [bernhard@green-dopamine.at](mailto:bernhard@green-dopamine.at)
