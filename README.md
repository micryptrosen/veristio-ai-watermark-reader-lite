# AI Watermark Reader Lite

A dependency-free local browser prototype for Build With AI Hackathon #2.

## Features

- Inspect pasted text and optional source/context notes.
- Review visible disclosure markers, provenance hints, and repeated-phrasing notes.
- Read limitations and recommended human review steps, then copy the report.

## Run Locally

Open `index.html` in a browser, or serve this folder over localhost:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Open `http://127.0.0.1:8080/`. No dependency installation, account, API key, or paid service is needed. The app uses plain HTML, CSS, and JavaScript with no external network calls, telemetry, or input storage. Clipboard availability depends on the browser; use the displayed fallback selection when necessary.

## Demo

[Watch the demo](https://youtu.be/g4BtTbJOI8Y). Public publication was reported by the owner; uploaded playback and metadata have not been independently verified.

## Limitations

Educational transparency review only. It does not determine authorship or verify hidden watermarks. Missing signals do not establish human authorship; suspicious patterns do not establish AI authorship. Avoid sensitive pasted content.

## Project Notes

See `ROADMAP.md`, `DEMO_SCRIPT.md`, `DEVPOST_REQUIREMENTS.md`, and `SOURCE_CUSTODY.md`. This repository is a fresh publication snapshot of an independently developed local prototype; its first commit does not represent the beginning of development. Devpost submission has not been performed.

## License

MIT. See `LICENSE`. The license covers this independent prototype, not excluded source-reference materials.
