# Global Conflict Monitor V2

A mobile-first Progressive Web App prototype for high-level
conflict escalation monitoring and de-escalation decision support.

## Important

This is a research/prototyping application.

It is NOT:

- a military command system
- an intelligence collection system
- a weapons-control system
- an offensive cyber system
- an autonomous retaliation system
- a validated geopolitical prediction model

No external operational systems are connected.

All event data is stored locally in the browser.

---

## Features

### Global escalation index

Produces a 0–100 demonstration risk score.

### Distance to escalation threshold

Shows the remaining margin before the prototype enters its
mandatory verification state.

This is NOT a prediction of how long remains until a conflict occurs.

### Four risk tracks

- Military escalation
- Cyber escalation
- Critical infrastructure
- AI-mediated escalation

These are derived display tracks rather than independent
validated models.

### Attribution uncertainty

Every event contains an attribution-confidence value.

The system explicitly separates:

- event severity
- attribution confidence
- escalation risk

### Five analytical perspectives

1. Intelligence
2. Skeptic
3. Adversary
4. Escalation
5. De-escalation

The purpose is to reduce single-model confirmation bias.

### Verification pause

At a risk score of 70 or above the system enters:

MANDATORY VERIFICATION PAUSE

The application recommends:

- evidence preservation
- independent attribution verification
- crisis communication
- containment
- consequence modelling
- explicit human authorisation

### Human response gate

The system cannot authorise retaliation.

The prototype explicitly records:

AUTONOMOUS RESPONSE: NO

---

## Risk heuristic

The prototype uses:

score =

(severity × 8
+ critical infrastructure × 20
+ cross-border × 15
+ casualties × 20)

× (0.45 + attribution confidence × 0.55)

The result is capped at 100.

Risk states:

0–44:
NORMAL MONITORING

45–69:
HEIGHTENED REVIEW

70–100:
MANDATORY VERIFICATION PAUSE

This is a transparent demonstration heuristic and should not
be interpreted as a real-world forecasting model.

---

## Running locally

The application can be opened directly as an HTML file.

For full PWA functionality, however, serve it through HTTPS.

Example:

python3 -m http.server 8080

Then open:

http://localhost:8080

---

## GitHub Pages

Create a GitHub repository and upload:

index.html
manifest.json
icon.svg
README.md

Then:

Settings
→ Pages
→ Deploy from branch
→ main
→ /root

GitHub Pages will provide an HTTPS URL.

---

## iPhone

Open the deployed HTTPS URL in Safari.

Then:

Share
→ Add to Home Screen

The application will launch as a standalone web app.

---

## Data

Event data is stored using:

localStorage

under:

globalConflictMonitorV2.events

No event data is sent to a server.

---

## Future architecture

The prototype is intentionally static.

A future research version could add:

- verified public data feeds
- event deduplication
- source reliability scoring
- temporal correlation
- geographic clustering
- uncertainty propagation
- independent model ensembles
- adversarial model testing
- audit logs
- cryptographic event signing
- human review workflows
- international crisis communication interfaces

Any future operational integration should preserve:

1. Human authorisation
2. No autonomous retaliation
3. Attribution uncertainty
4. Independent verification
5. Separation between intelligence and execution
6. Full auditability
7. No autonomous weapons authority
