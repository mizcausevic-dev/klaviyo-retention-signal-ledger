# klaviyo-retention-signal-ledger

Board-readable Kinetic Gain proof repo for **Klaviyo** platform and company signal coverage.

## Product thesis

Retention programs lose credibility when consent, deliverability, flow performance, revenue attribution, and customer recovery are fragmented.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** Lifecycle marketers, e-commerce operators, RevOps, and product marketing leaders
- **Signal domain:** Revenue Operations
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product maps lifecycle flows, consent posture, deliverability risk, customer recovery, and campaign value into one ledger.
- **Value architecture:** Leaders can identify revenue leakage, protect customer trust, and prioritize lifecycle investments with evidence.

## What this repo proves

- **Normalize:** messy Klaviyo operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: Klaviyo flows, segments, consent records, deliverability metrics, conversion events, and recovery campaigns.

This is synthetic proof only. It does not connect to live Klaviyo tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- Klaviyo
- retention marketing
- lifecycle ops
- deliverability
- revenue attribution
