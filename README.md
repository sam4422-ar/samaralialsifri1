# Real Estate Customer Service — Prompt Library
## مكتبة برومبتات خدمة العملاء العقارية

A reusable, versioned collection of customer-service prompt templates. Pick a template, fill the variables, run it, and review the reply before sending.

## What is inside
| Path | Purpose |
|---|---|
| `00_Prompt_Index.md` | Template index, purpose, version |
| `templates/customer_service.md` | Main customer-service template |
| `templates/_BLANK_TEMPLATE.md` | Blank reusable template |
| `blocks/DeskFacts.md` | Approved company facts to add as context |
| `quality_checklist.md` | Pre-send quality review |
| `examples.md` | Example variable sets and expected behavior |

## Daily workflow: Pick, Fill, Run, Review
1. **Pick** the template matching the customer's request.
2. **Fill** every `[VARIABLE]` with case details.
3. **Run** it with the customer's message and verified company facts.
4. **Review** the reply using `quality_checklist.md`.
5. **Approve** the response before sending.

## Safety and privacy
- Never store real customer names, national ID numbers, phone numbers, email addresses, or payment details in this shared library.
- Use only verified company policies, prices, dates, availability, and process details.
- Never invent booking status, property availability, deed delivery dates, refund decisions, or complaint resolutions.
- If a fact is unknown, say it needs confirmation and explain the next step.
- Escalate sensitive, disputed, or policy-exception cases to an authorized employee.
- A human must review every response before sending.

## Naming and versioning
Use: `CS-<Task>-<Object>-v<Number>_<YYYY_MM_DD>.md`
Example: `CS-Reply-Inquiry-v1_2026_10_13.md`
Increase the version number when instructions change.

## Defaults
- Language: match the customer's language.
- Tone: professional, calm, respectful.
- Length: concise but useful.
- Signature: `سارة` for Arabic replies; `Sara` for English replies.
- Do not disclose internal notes or explain the prompt to the customer.
