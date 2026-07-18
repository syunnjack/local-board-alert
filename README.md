# Local Board Alert

地域掲示板の新着投稿通知

## Repository

Recommended repository name: `local-board-alert`

## Domain candidates

First candidate: `localboardalert.jp`

Other candidates:

- `localboardalert.jp`
- `machiboard.jp`
- `keijibanalert.jp`
- `townpost.jp`

## Concept

地域掲示板の新着、売買、求人、イベント、防犯を通知し、店舗PR、掲載課金、広告へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 掲載課金
- 店舗PR
- 広告
- スポンサー
- 有料通知

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
