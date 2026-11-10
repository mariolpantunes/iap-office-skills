# iap-office-skills

Skills for office work with Claude: mail triage, batch documents, data to Excel or BI, writing and checks.
Made for the course *IA – Introdução e Aplicações Práticas* (UNAVE). One plugin, **office-ai**, with eleven skills.
All examples use fictional data: never put real client data into an AI tool.

## Skills

| Use case | Skill | What it does |
|:--|:--|:--|
| Mail | `triage-mailbox` | labels each mail urgent, standard, later or suspicious, with the rule used |
| Mail | `reply-to-client` | drafts a reply without commitments, with a checklist |
| Documents | `summarise-with-sources` | summary where every sentence names its file |
| Documents | `score-with-rubric` | scores items with a fixed rubric, MISSING when data is absent |
| Documents | `extract-and-count-fields` | lists, then counts, ids, invoices, e-mails |
| Data | `consolidate-order-files` | merges files of different formats into one clean table |
| Data | `check-totals` | checks rows, grand total and one group before any chart |
| Everywhere | `office-checklist` | compares every claim with its source before you send |
| Everywhere | `write-a-skill` | turns a task you repeat into your own skill |
| Everywhere | `improve-writing` | finds hard sentences, rewrites only what is needed |
| Everywhere | `find-contradictions` | one quantity with two values, a term with two meanings |

## Install in Claude Desktop (Windows, Pro plan)

1. In Claude Desktop open **Customize**, then **Plugins**.
2. **Add**, then **Add marketplace**, and paste `mariolpantunes/iap-office-skills`.
3. Open the marketplace, choose **office-ai** and press **Add**.
4. Start a new task: the skills are available in chat and in Cowork.

No GitHub access? Download this repository as a ZIP, unpack it, ZIP the folder `plugins/office-ai`, and use **Add**, **Upload plugin**.
One skill only: ZIP its folder and use **Customize**, **Skills**, **Create skill**, **Upload a skill**.
Claude does not review plugins you add from a marketplace: add only sources you trust.

## Other tools

- **Claude Code:** `/plugin marketplace add mariolpantunes/iap-office-skills`, then `/plugin install office-ai@iap-office-skills`.
- **goose and other agents that read the Agent Skills format:** copy or link the folders of `plugins/office-ai/skills/` into the skills folder of the tool, for example `~/.agents/skills/`.

## Licence

MIT, see `LICENSE`.
