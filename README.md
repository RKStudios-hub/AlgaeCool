# Algae Cool

QR code for the **Algae Cool** video site.

## Scan it

![Algae Cool QR code](./algae-cool-qrcode.png)

The QR encodes:

```
https://fashion-outro-site.vercel.app
```

## Site

The page hosted at that URL lives in [`index.html`](./index.html) — a single
static file that autoplays the outro video on loop, with playback controls and
a direct MP4 download link.

| File | Description |
| --- | --- |
| `algae-cool-qrcode.png` | 1000x1000 QR code PNG, error correction level H |
| `index.html` | Source of the deployed video page |

## Deploy

```bash
vercel --prod
```

Note: the deployed video is served from `/outro.mp4`, so copy the MP4 into a
`public/` directory alongside `index.html` before deploying.
