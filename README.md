# kalshi-positions

`positions.yaml` book for the touch position tracker in
[arbitrage_kalshi](https://github.com/pohaoc2/arbitrage_kalshi)
(`scripts/viz/touch_position_tracker.py` and `scripts/track_touch_positions.py`).

Synced across devices via this private repo. On each device:

```bash
git clone git@github.com:pohaoc2/kalshi-positions.git ~/UW/kalshi-positions
ln -s ~/UW/kalshi-positions/positions.yaml ~/UW/arbitrage_kalshi/positions.yaml
```

The tracker's 儲存 button overwrites the file in place; commit and push after
editing, pull before opening the tracker on another device.
