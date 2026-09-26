# The Short-Order Cook

*Illustrative scenario — a composite sketch, not a real person.*

## The repo

Friday night, six burners, a ticket rail full of orders, the health inspector watching, and a fryer that only works if you kick it. She ran that kitchen for eleven years.

## The commits

- Tracking fourteen orders in her head while plating six more — concurrency under load, no mutex, no retries.
- Reading a ticket and knowing the table's mood from the handwriting — input parsing with emotional metadata.
- The night the gas went out mid-rush and she replanned the entire menu around two working burners in ninety seconds — graceful degradation under hard constraints.

## The fork

Picture the fork: an emergency department rethinking triage intake. Fourteen patients instead of fourteen tickets, the rail is a whiteboard, the fryer that needs kicking is a CT scanner with a queue. Nobody in the hospital has ever thought of the waiting room as a ticket rail — she has eleven years of Friday nights that say otherwise.

## The lesson

Concurrency under load is concurrency under load. The domain is just a theme.
