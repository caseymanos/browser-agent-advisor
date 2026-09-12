# Browser Agent Advisor

Choose browser agents, computer-use tools and infrastructure with minimal decision-changing questions. Includes an offline questionnaire and cited capability matrix.

## Install

```bash
npx skills add caseymanos/browser-agent-advisor --skill browser-agent-advisor
```

Ask your agent:

> Use browser-agent-advisor to choose a browser automation stack. I need hosted execution, persistent logins, and an API for my product.

Or generate the interactive overview with Python 3:

```bash
python3 skills/browser-agent-advisor/scripts/render_overview.py --output-dir ./overview
```

Open `overview/agent-capabilities.html`. Questionnaire and filtering work offline; sources require internet. No Python packages required.

## Evidence boundaries

32 capabilities, 11 surfaces, 352 evidence entries, 58 sources. Baseline checked September 10, 2026; Browserbase/Stagehand September 11; decision analysis September 12. Current recommendations require fresh verification; bundled HTML remains dated. No comparative agent-performance benchmark was run. No accounts, automatic purchases or background network calls are required by the renderer.

Independent community guide; not affiliated with the vendors. Original instructions/code are MIT licensed. Linked source materials remain subject to their owners' rights.

## Distribution

Follows [skills.sh guidance](https://skills.sh/docs/faq): GitHub-hosted skills are discovered through skills CLI installations. Directory indexing is separate from GitHub availability.

The repository and skill are both named `browser-agent-advisor`.
