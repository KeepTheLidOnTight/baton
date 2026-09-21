# Baton

## Why I built it

When an account moves between internal teams, the next owner needs a quick, reliable view of the customer: what was sold, what matters now, and what still needs a decision. Baton turns that handoff into one account deck so the new team can start with the right context and open work.

## Simple assumptions

A person starts each handoff. In a future Salesforce integration, automation could flag a handoff when a Closed Won deal has the needed fields populated. The person reviews the account, confirms the handoff, and Baton uses the CRM export and call notes as the shared record for the deck.

## A concrete example

Terrapin Touring Co. moves from Sales to Product Onboarding on September 16. The handoff deck captures the customer goal, key contacts, and the work Sales promised. When the account moves again, Baton adds the new handoff to the same deck and keeps the earlier record in place. The current owner can quickly see what is still open, who owns it, and when it is due.

## How Baton works

1. Salesforce automation can flag a possible handoff when the needed fields are complete.
2. A person reviews the account and triggers the handoff. Baton reads the records and notes, then creates or updates that account's deck.
3. The team reviews the deck, completes the open items, and leaves feedback so the next handoff gets better.

## Human in the loop

AI helps organize the information and point out missing details. A person reviews the deck before using it, confirms what is true, and decides what should happen next.

## What I would add in production

I would connect Baton to Apollo's API so it can pull the right account context. I would add Salesforce automation that prepares a draft when the needed handoff fields are complete, while a person still reviews and triggers it. Feedback on every deck would improve the handoff checks over time. Teams could also set their own required fields and notification rules.

*All names, records, dates, and results in this demo are fictional.*
