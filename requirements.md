# Festa MVP Requirements

## Problem

Event planning is complicated and time-consuming.

Users struggle with:

- Budget planning
- Vendor planning
- Timeline management
- Cost overruns

## Solution

Festa acts as an AI Event Copilot.

Users enter:

- Event type (wedding, birthday, community event, corporate event)
- Guests
- Budget
- Event date
- City

Festa generates:

- Budget allocation and cost breakdown
- Event checklist
- Timeline with real dates
- AI insights: risk prediction, cost optimisation, vendor planning ranges
- AI confidence score, risk level, sustainability score and potential savings
- Spoken narration with Start, Pause and Stop

## MVP Scope

- One executable file: `index.html`, with no server, install or API key.
- Rule-based insights computed in the browser. Nothing the user enters leaves the device.
- Out of scope: vendor marketplace, payments, live pricing, live LLM calls, chat.

## Success Metrics

- User completes a plan within 60 seconds
- Narration starts instantly after the button is pressed
- Mobile responsive
- Keyboard accessible, with captions for the spoken narration
- Early-user signal: at least 10 test users complete a plan, and at least 7 say they would use it for a real event

## Honest Limits

- Scores and savings are planning estimates, not vendor quotes, market data or a trained model.
- Voice quality depends on the voices installed on the user's device.
