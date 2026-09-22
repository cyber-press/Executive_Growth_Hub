# Executive Growth Hub v2.9 — AI Prompt Engine v2.0

This release preserves the approved HUD interface and replaces the prompt generator logic with a mission-specific execution engine.

## Engine changes
- Semantic context scoring instead of field-completion scoring
- Mission-specific objective alignment and contamination detection
- Mission-specific output contracts for Sales, Content, Validation, Planning, Customer Service, Operations, Branding, and Website Copy
- Quality gate before MISSION READY
- Invalid/test input detection
- Broad-audience detection
- No generic WhatsApp/community advertising injected into external AI prompts
- No irrelevant finance instructions injected into unrelated missions
- Explicit anti-fabrication guardrails and labeled assumptions

The app remains static and local-first.


## Prompt Engine v2.1

- Multi-offer detection blocks acquisition/content missions when several primary offers are bundled into one field.
- Buyer-context validation distinguishes demographic descriptions from acquisition-ready audience context.
- Output contracts now synchronize with the selected presentation format, including 30-day timelines, tables, checklists, and copy-ready output.
- Generated command header upgraded to `EGH AI EXECUTION COMMAND v2.1`.
