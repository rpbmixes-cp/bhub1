# Deploy / Run bhub1

## Local server

From the repo folder:

```bash
python -m http.server 3333
```

Open:

```text
http://192.168.1.85:3333/
```

## Files

- `index.html` is a standalone static Build Hub.
- `README.md` contains the finish workflow and low-end rules.

## Browser storage

Checklist progress is saved in browser `localStorage` under:

```text
bhub1-checks
```

Use **Export Progress** in the app before clearing browser data or moving device.

## Club translation rules

- Sub mono below 120 Hz.
- No sub/bass send to reverb or delay.
- Mix bus around -6 dB peak before mastering.
- Target loudness only after kick/sub peaks are controlled.
