# bhub1 — Ableton Build Hub

Static Ableton Live 12 Build Hub designed to run at:

```text
http://192.168.1.85:3333/
```

## Run locally

```bash
python -m http.server 3333
```

Then open:

```text
http://192.168.1.85:3333/
```

## Current build

This repo is being updated into a local-first Build Hub for started Ableton tracks.

Included in `index.html`:

- Build Hub dashboard
- Track finishing pages
- 25 L' Paradiso v2.1 finish plan
- 23 Deepin It v2.1 finish plan
- Best next steps
- What to add next
- Up-shifters
- Down-shifters
- FX layer plan
- Pads/chords/stabs plan
- Chain settings
- Arrangement map
- Progress checkboxes saved in browser localStorage
- Import/export data controls

## Low-end rules

- Keep sub mono below 120 Hz.
- Do not send sub to reverb/delay.
- Phase-align kick and bass before mastering.
- Pull mix bus to roughly -6 dB peak before limiting.

## 25 L' Paradiso immediate finish order

1. Save new Ableton version: `25 L Paradiso - v2.2 FINISH PLAN`.
2. Pull the mix back so the mix bus peaks around -6 dB.
3. Phase-align kick and G0 sub.
4. Extend the track to a DJ-safe 192–208 bar arrangement.
5. Add controlled up-shifters before energy increases.
6. Add down-shifters before breakdowns and section resets.
7. Add G minor pads only in breakdown/rebuild sections first.
8. Add hook stabs/vocal answers every 8–16 bars only.
9. High-pass all FX/returns.
10. Export pre-master before final limiting.
