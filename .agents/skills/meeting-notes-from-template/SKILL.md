---
name: meeting-notes-from-template
description: Use when creating or editing a Markdown meeting note from raw notes and an existing meeting template, especially in the DivergenceFreeSBM.jl project.
---

# Meeting Notes From Template

Turn rough meeting notes into a concise record using the meeting folder's `template.md` as the structure.

1. Read the target note, if it exists, and `template.md` in the same folder. In this repository, use `docs/meetings/template.md`. If neither an adjacent nor a supplied template is available, ask for one.
2. Preserve concrete details already entered in the target note, such as date, location, and attendees. Treat template examples, TODOs, and bracketed placeholders as unfilled.
3. Place each raw point under the matching template heading, in template order. Include a section only when the available notes support it. Keep the template's heading names; use only the table rows or columns that can be filled meaningfully.
4. Separate discussion notes from decisions, action items, open questions, and next meeting details. State an action's owner or deadline only when provided. Do not turn advice into a formal decision or infer attendance, dates, reasons, or issue links.
5. Paraphrase for clarity while preserving technical terms, names, and the strength of each statement. Use brief bullets rather than a transcript. Check the finished note against the raw notes and template before reporting completion.

For example, “regular meetings on Friday 11:00” belongs under `## Next meeting` as a recurring schedule; it does not establish a specific next date.
