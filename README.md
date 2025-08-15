
# Grandmaster Sweep — Finnhub (Data) + Alpaca Paper (Orders)
**Hardcoded keys inside `config.py` so you can just press Run.**

## Run (Replit)
1) New Python Repl
2) Upload & Extract this ZIP
3) Press **Run** (auto-installs `httpx` and starts).

## Tweak in `config.py`
- `SCAN_BATCH_SIZE` (500 default), `CONCURRENCY` (50), `TAKE_PER_SCAN` (5), `MAX_OPEN_POSITIONS` (15)
- Risk: `DOLLARS_PER_TRADE` (75), exits: `TRAIL_PERCENT` (3%), `TIME_EXIT_MINUTES` (7)
