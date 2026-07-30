# Courtny Robinson — Portfolio

Personal portfolio site. Static HTML/CSS/JS, no build step, hosted free on GitHub Pages.

**Live:** https://crobinson-datascientist.github.io/

## Structure

```
├── index.html                      # main portfolio page
├── assets/
│   ├── style.css                   # shared stylesheet
│   ├── main.js                     # nav toggle + scroll reveal
│   └── Courtny_Robinson_Resume.pdf
├── projects/                       # project detail pages
│   ├── evm-dashboard.html
│   ├── procurement-analyzer.html
│   ├── setaside-analysis.html
│   └── ai-procurement-risk.html
└── dashboards/                     # live interactive demos
    ├── evm-dashboard.html
    └── procurement-dashboard.html
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Note on demo data

The dashboards under `dashboards/` are recreations built for portfolio purposes. All names, figures,
and dates are fictional. No proprietary or employer-confidential data is represented.
