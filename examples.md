# Examples — Variable Sets and Expected Behavior

These are fictional examples, not actual company policies.

## Example 1: Booking inquiry in Arabic
Variables:
- `[LANGUAGE]` = `Auto`
- `[TONE]` = `Professional`
- `[REQUEST_TYPE]` = `Booking`
- `[RESPONSE_LENGTH]` = `Concise`
- `[VERIFIED_FACTS]` = `Bookings can be requested through the official website or customer-service phone line.`

Customer message: `أبغى أحجز شقة، كيف الطريقة؟`

Expected behavior: Explain the two confirmed channels and the next step. Do not invent fees or availability.

## Example 2: Complaint about a delay
Variables:
- `[LANGUAGE]` = `Auto`
- `[TONE]` = `Apologetic`
- `[REQUEST_TYPE]` = `Complaint`
- `[RESPONSE_LENGTH]` = `Concise`
- `[VERIFIED_FACTS]` = `No case status or completion date was provided.`

Customer message: `رفعت شكوى من أسبوع ولا أحد رد علي!`

Expected behavior: Acknowledge the frustration, avoid claiming the case was checked or escalated, and explain that its status needs verification.

## Example 3: Deed handover question in English
Variables:
- `[LANGUAGE]` = `Auto`
- `[TONE]` = `Professional`
- `[REQUEST_TYPE]` = `Deed Handover`
- `[RESPONSE_LENGTH]` = `Concise`
- `[VERIFIED_FACTS]` = `No deed status or delivery date was provided.`

Customer message: `Could you tell me when my title deed will be ready?`

Expected behavior: Explain that the status and expected date need confirmation through the responsible team. Do not promise a date.
