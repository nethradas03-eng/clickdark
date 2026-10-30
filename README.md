# ClickTrap – Dark Pattern Detector

ClickTrap is a student Git Discipline Project that explores how deceptive interface designs ("dark patterns") can influence user choices. The project uses HTML, CSS, JavaScript, Chrome Extension APIs, and a rule-based detection engine.

## Project links

- **Live project website:** https://nethradas03-eng.github.io/clickdark/
- **Dashboard:** https://nethradas03-eng.github.io/clickdark/dashboard/
- **Sample test pages:** https://nethradas03-eng.github.io/clickdark/test-pages/
- **Source code:** https://github.com/nethradas03-eng/clickdark

## Main features

- Rule-based checks for urgency, scarcity, confusing cookie consent, hidden costs, confirmshaming, and obstructive cancellation.
- Explanations and recommended actions for detected signals.
- Browser extension popup with scan results and local scan history.
- Companion dashboard with sample pages, reports, history, and educational content.

## Run the dashboard and URL scanner locally

The GitHub Pages website is static. It can show the landing page, dashboard, and sample pages, but GitHub Pages does not run the Node.js scanning server.

To use the local URL-scanning API:

1. Install Node.js.
2. Clone this repository and open its folder in a terminal.
3. Run `npm start`.
4. Open http://localhost:3000.

The local server is used for fetching and analysing a URL. Some websites may still block automated requests or require a browser session.

## Install the Chrome extension

1. Download or clone this repository.
2. Open `chrome://extensions` in Google Chrome.
3. Enable **Developer mode**.
4. Select **Load unpacked**.
5. Choose the cloned `clickdark` folder (the folder containing `manifest.json`).
6. Open a normal webpage, click the ClickTrap extension icon, and select **Scan this page**.

## Run tests

```bash
npm test
npm run evaluate
```

## Important limitation

ClickTrap uses predefined rules and DOM heuristics. Its results are potential warning signals, not definitive findings of fraud or legal violations. False positives and missed detections are possible.

## Team

- Nandhana P P
- Nayana M
- Neethu M
- Nethra Das M

Department of Computer Science and Engineering
