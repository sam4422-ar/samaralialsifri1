# Real Estate Customer Service — Prompt Library

## مكتبة برومبتات خدمة العملاء العقارية

A reusable, versioned collection of customer-service prompt templates. Pick a template, fill the variables, run it, and review the reply before sending.

## What is inside

| File | Purpose |
| ---- | ------- |
| `00_Prompt_Index.md` | Template index, purpose, version |
| `Real_Estate_Customer_Service_Prompt_Library.md` | Full prompt library |
| `customer_service.md` | Main customer-service template |
| `customer_complaint.md` | Complaint-handling template |
| `CS-Classify-Request.md` | Classify the customer's request |
| `CS-Reply-Inquiry-v1_2026_10_15.md` | Reply template for inquiries |
| `CS-Reply-Complaint-v1_2026_10_15.md` | Reply template for complaints |
| `CS-Escalate-Issue.md` | Escalate sensitive or disputed cases |
| `CS-Privacy-mask.md` | Mask personal data before use |
| `DeskFacts.md` | Approved company facts to add as context |
| `rules_safety_rules.md` | Safety and privacy rules |
| `quality_checklist.md` | Pre-send quality review |
| `examples.md` | Example variable sets and expected behavior |
| `library_guid.md` | Library usage guide |
| `library_index.md` | Library index |
| `Test_Results_Report.md` | Test results report |

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
Example: `CS-Reply-Inquiry-v1_2026_10_15.md`
Increase the version number when instructions change.

## Defaults

- Language: match the customer's language.
- Tone: professional, calm, respectful.
- Length: concise but useful.
- Signature: `سارة` for Arabic replies; `Sara` for English replies.
- Do not disclose internal notes or explain the prompt to the customer.
## Training Program
This project was completed as part of the Prompt Engineering and Responsible AI Use training program at SDAIA Academy, under the supervision of Abdullah Khalid Alshahrani. 
The project demonstrates the practical application of prompt engineering and responsible AI use — building a clean, approved prompt library through structured RACE prompts, reusable templates with variables and fixed output formats, safe handling of sensitive data, verification and responsible-use rules, and a documented three-test quality report.
Official SDAIA Academy GitHub:
https://github.com/SDAIAAcademy
