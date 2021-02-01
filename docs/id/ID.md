---
tags: [id]
---

# IDs

Saryno IDs are based on Twitter's Snowflakes IDs. 

Snowflakes are 64Bit Numbers that encode a **Timestamp**, **Internal ID** and a **Sequence**

## Decoding an ID

The ID is encoded using the following format:

- 1 Bit is Reserved
- 2 -> 42 (inclusive) Bit is the Timestamp
- 43 -> 52 Internal ID
- 53 -> 44 Sequence