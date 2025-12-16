
# Squadron Prompts

**A curated prompt library for military aviators using LLMs for academics, CRM, instrument/procedure study, debrief structure, and conservative decision-making.**

> **Safety‑Critical Use Banner**  
> Military aviation is safety‑critical. This repository is **not official guidance**, **not formal instruction**, and **not a substitute** for your unit standards, AFIs/AFMANs, TOs, checklists, published tactics volumes, training rules, or instructor supervision.  
> Large Language Models can **hallucinate** (confidently generate incorrect or fabricated information). Treat all outputs as **unverified drafts** and validate against authoritative references.

## What this is
A collection of prompts you can paste into an LLM to get:
- Structured explanations and study guidance (unclassified / non-sensitive)
- Crew resource management (CRM) and threat/error management (TEM) practice
- Mission brief and debrief structure (format and discipline, not classified content)
- Instrument/procedure study aids and checklists (conceptual)
- Stan/Eval style oral practice (conceptual, reference-driven)

## What this is not
- Not mission execution guidance
- Not tactical employment instruction (weapons, threat reactions, classified tactics)
- Not a replacement for publications, training rules, or instructor oversight
- Not legal advice or official regulatory interpretation

## OPSEC / data handling (read this)
- **Do not paste classified, CUI, FOUO, or sensitive mission details into any LLM.**
- Assume any cloud LLM is **not approved** unless explicitly authorized in your environment.
- When in doubt: keep it generic, sanitize details, or use a **local/offline model**.

## Quick start
1. Pick a prompt from `prompts/`.
2. Replace bracketed fields like `[platform]`, `[phase]`, `[weather snippet]`.
3. Paste into your preferred LLM.
4. **Verify** outputs with authoritative sources (AFIs/TOs/unit standards).

Recommended: start with templates in `templates/` to force conservative, reference-driven output.

## Repository layout

```
squadron-prompts/
  README.md
  SAFETY.md
  CONTRIBUTING.md
  LICENSE
  prompts/
  templates/
  examples/
```

## Short disclaimer
Educational use only. Not official guidance. Verify with authoritative sources. LLMs may hallucinate.
