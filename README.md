# Due Diligence Skills

This repository contains reusable Codex skills for company due diligence.

## Included Skill

### `company-due-diligence`

Use this skill to research and assess a company in a structured, evidence-backed way. It is designed for questions such as:

- Should we invest in this company?
- Is this acquisition target attractive?
- What are the main red flags for this vendor or partner?
- What should I ask management in the next diligence meeting?
- Can you turn this research into a concise diligence memo?

The skill emphasizes:

- Primary-source research
- Clear separation between fact and inference
- Workstream-based diligence across market, product, commercial, financial, legal, and management topics
- Decision-oriented outputs with explicit risks and next steps

## Repository Layout

```text
company-due-diligence/
  SKILL.md
  agents/openai.yaml
  references/
    source-priority.md
    diligence-checklist.md
    memo-template.md
```

## Using The Skill

Example prompt:

```text
Use $company-due-diligence to assess this company and produce a concise diligence memo.
```

You can also ask it to produce:

- a red-flag summary
- a management question list
- a comparison table across companies
- a focused diligence pass on one workstream

## Notes

The skill folder intentionally stays lean so Codex loads only the instructions and references it needs.
