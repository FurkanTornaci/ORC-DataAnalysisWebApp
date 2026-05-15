# Oldendorff Smart Operations Web App

Standalone Vercel-ready web application extracted from the main project.

## Routes
- `/` -> Trim Interval Speed-Power Visualizer
- `/ac-speed-compare` -> Vessel Performance Comparison

## Data files required
Add CSV files listed in `share_trim_webapp/data/README.md`.

## Local run
From this folder:

```bash
python -m http.server 8000
```

Open:
- `http://127.0.0.1:8000/share_trim_webapp/index.html`
- `http://127.0.0.1:8000/share_trim_webapp/ac_speed_compare_app.html`

## Deploy
```bash
vercel --prod
```
