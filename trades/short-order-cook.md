# The Short-Order Cook

## The repo

Friday night, six burners, a ticket rail full of orders, the health inspector watching, and a fryer that only works if you kick it. She ran that kitchen for eleven years.

## The commits

- Tracking fourteen orders in her head while plating six more — concurrency under load, no mutex, no retries.
- Reading a ticket and knowing the table's mood from the handwriting — input parsing with emotional metadata.
- The night the gas went out mid-rush and she replanned the entire menu around two working burners in ninety seconds — graceful degradation under hard constraints.

## The fork

An emergency department hired her to redesign triage intake. Same skill, different domain: fourteen patients instead of fourteen tickets, the rail is a whiteboard, the fryer that needs kicking is a CT scanner with a queue. Wait times dropped. Nobody in the hospital had ever thought of the waiting room as a ticket rail.

## The lesson

Concurrency under load is concurrency under load. The domain is just a theme.
