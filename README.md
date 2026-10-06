# COMM 1315 Schedule Dashboard

A self-contained, interactive dashboard for the **FA26 COMM 1315** course schedule.

## Files

- `COMM1315_Schedule_Dashboard.html` — the full dashboard
- `index.html` — redirect to the dashboard (for GitHub Pages)
- `extract_schedule.py` — script used to extract text from the original PDF
- `comm1315_page1.png`, `comm1315_page2.png`, `comm1315_page3.png` — extracted calendar images for cross-reference

## Features

- Visual calendar and weekly table
- Real-time days-remaining counter
- Progress tracking with checkboxes
- No-class days excluded from completion percentage
- Print / Save as PDF button
- Export CSV button
- Export/Import progress (JSON)
- Copy Share Link — copies a URL with progress embedded
- Download Shareable File — saves an HTML file with progress baked in

## Host on GitHub Pages

1. Create a new GitHub repository.
2. Upload `COMM1315_Schedule_Dashboard.html` and `index.html` to the root of the repo.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then click **Save**.
6. Wait about a minute. Your site will be live at:

```
https://yourusername.github.io/your-repo-name/
```

Use that URL with the **Copy Share Link** button to share your progress from any device.

## Use locally

Open `COMM1315_Schedule_Dashboard.html` in any web browser. No internet required.

## Source

Data extracted from `FA26 COMM 1315 Schedule.pdf`.
