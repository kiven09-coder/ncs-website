# NCS — National Center for Studies / المركز الدراسات المصري

Web frontend for the NCS news aggregation platform.

> منصّة إخبارية شاملة — أخبار سياسية ودولية، رياضة لحظية، اقتصاد (ذهب الصاغة + البنك المركزي)، خريطة عالمية ثلاثية الأبعاد لحركة الشحن والطيران المدني والعسكري، ومرآة لصفحة المركز على فيسبوك.

## Project structure

```
website/
├── drafts/
│   └── v1/                   ← current static prototype (open index.html)
│       ├── index.html
│       ├── logo.jpg          ← official NCS logo
│       └── logo.svg          ← scalable fallback
└── (next/)                   ← Next.js production app (coming next)
```

## View the draft locally

Just double-click `drafts/v1/index.html` — works offline, single file.

## View the draft online (GitHub Pages)

After the repo is pushed and Pages is enabled (Settings → Pages → branch `main` / root):

```
https://<username>.github.io/<repo-name>/drafts/v1/
```

## Status

- ✅ v1 — visual prototype with simulated live data
- ⏳ v2 — Next.js + TypeScript scaffold
- ⏳ v3 — wire to backend (FastAPI in sister `ncs-backend` repo)
- ⏳ v4 — PWA + Capacitor wrap for iOS / Android
