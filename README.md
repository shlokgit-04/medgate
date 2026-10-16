# MedGate - Clinical Action Review Console

MedGate is the human side of a clinical AI agent's safety gate. When a healthcare agent
wants to take a consequential action (order a test, send a patient message, request a
refill, book a follow-up), the gate holds it in a review queue and shows the clinician
the evidence needed to decide in seconds.

## Screens

- **Review queue** - pending agent actions with verdict pills (block / review / pass)
- **Case detail** - why the gate held the action: the agent's plan beside untrusted text
  found in a retrieved document, quoted verbatim, plus explicit reviewer choices
- **Audit log** - every gate decision, newest first
- **Policy settings** - plain-language policy knobs (off-hours messaging hold, chart
  mismatch holds, controlled-substance ceiling, untrusted-text escalation)

## Honest scope

This is a static front-end prototype: HTML, CSS and vanilla JavaScript, no backend.
All patients, charts and messages are **synthetic demo data**. No real PHI, no live EHR
connection, no clinical recommendations. This is a workflow mock-up, **not a medical device**.

## Run it

Open `index.html` in a browser, or use the GitHub Pages deployment.

## License

MIT - see LICENSE.
