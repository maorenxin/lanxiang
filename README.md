# 蓝象智联｜数字驾驶舱 V2（中英对照版）

Static single-page dashboard. Served with GitHub Pages.

Public URL: https://maorenxin.github.io/lanxiang/

- Entry: `index.html`
- Assets: `assets/`

## Language toggle

- Top-right control cycles `中/英` (bilingual) → `中文` → `EN`.
- The choice is persisted in `localStorage`; a URL parameter also works: `?lang=both`, `?lang=zh`, `?lang=en`.

## Viewport notes

- Desktop-first; all six pages verified at 1920x1080, 1600x900, 1366x768 and 1280x720.
- Below a 720px browser viewport height, the page keeps a 720px design height and scrolls vertically so content is not hard-clipped.
- On page 06 the customer logo wall scrolls vertically; the fade and `SCROLL` hint indicate more rows.
