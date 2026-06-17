# web

Hebei Xiong'an Jietong Innovation Tech Co., Ltd. - Custom hat manufacturer website

## Vercel Speed Insights

This project includes Vercel Speed Insights for performance monitoring.

### Setup

The Speed Insights integration is already configured. To rebuild the script after making changes:

```bash
npm install
npm run build
```

### How It Works

- Speed Insights is loaded via `dist/speed-insights.min.js` on all HTML pages
- The script uses the `@vercel/speed-insights` package to automatically track web vitals
- To enable data collection, activate Speed Insights in your Vercel project dashboard

