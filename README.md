# Concert Tickets

## Intro

Concert tickets should allow the owners of the tickets to attend concerts/events. Tickets are tokens that can be owned through the blockchain.

## Specification / Requirements

- A ticket can only be used once to enter the venue/concert/event
- For each event, there is a limited supply of tickets
- Each ticket purchase should split the paid value between the predefined event organizers (Artist, Venue, Operations ...)
- Reselling the ticket should still send part of the resell value to the event organizers

## Open Questions

- Can we add identity verification into this to ensure that reselling rules cannot be avoided by creating a new account and selling the account?
- Is it possible to only allow resale through the Concert Ticket platform and not through sending the token directly?
