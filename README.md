# Academic Writing Skill

A reusable LLM skill based on a comprehensive academic writing guide.
Load the system prompt into any LLM to get expert writing coaching.

## How to use (examples)

### Claude — Project instructions
1. Go to claude.ai → Projects → New Project
2. Open Project instructions
3. Paste the full contents of `SKILL.md`

### Gemini — Gem
1. Go to gemini.google.com → Gems → New Gem
2. In the "Instructions" field, paste the full contents of `SKILL.md`
3. Name it "Academic Writing Coach" and save

### API / local use (system prompt)
Paste the full contents of `SKILL.md` as the `system` message in your API call or tool (e.g. OpenWebUI, LM Studio, Ollama, Cursor).

### Chat-only interfaces (no system prompt access)
Paste this as your very first message:
> "For this conversation, act as an academic writing coach.
> Follow these instructions precisely: [paste SKILL.md contents here].
> Confirm you understand before we begin."

## Files
- `SKILL.md` — the system prompt, paste this into your LLM of choice
- `LICENSE` — CC BY-NC 4.0
- `README.md` — this file