# Maximus — JARVIS Trading Mastermind

Gold trading intelligence. Reports to JARVIS. Executes via Trade Nation API.

**Status:** Built. Awaiting Trade Nation API credentials (May 20th).

## Structure
- Gold Scout runs every hour — price, RSI, news, support/resistance
- Maximus analyses Scout data and writes recommendations
- JARVIS reads recommendations and alerts the owner via Siri
- Owner approves → Maximus executes via Trade Nation

## Files
- `maximus-brain.md` — Scout intelligence (updated hourly)
- `maximus-strategy.md` — current trading rules and stance
- `trade-log.md` — every trade ever made
