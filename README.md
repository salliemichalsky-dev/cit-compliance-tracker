# CIT Compliance Tracker

A standalone browser tool for researching and monitoring state-level requirements related to:

- Physical restraint use
- Seclusion and isolation policies
- Crisis intervention training (CIT) certification requirements
- De-escalation training mandates
- Documentation and incident reporting
- Parental/guardian notification requirements

## Setup

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
2. Enter your [Anthropic API key](https://console.anthropic.com/keys) when prompted
3. Your key is stored in your browser's `localStorage` only — it never leaves your machine except in direct calls to the Anthropic API

## Features

- **Research tab** — select a state and domain, get a detailed compliance summary with statute citations
- **State registry** — visual dashboard of all 50 states + DC with freshness indicators
- **Monthly monitor** — tracks last-checked dates and flags states overdue for review; run all overdue checks in one click

## Costs

Each research query uses the Claude API (claude-opus-4-5). Typical cost per state query is under $0.05. Monitor your usage at [console.anthropic.com](https://console.anthropic.com).

## Hosting on GitHub Pages

See the setup instructions in the repo for how to host this as a free GitHub Pages site.

## Important Note

Results are drawn from Claude's training data. Always verify critical compliance decisions against primary state agency sources. Each summary includes the relevant state agency website URL.
