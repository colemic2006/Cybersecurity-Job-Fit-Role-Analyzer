# Job Role Fit Analyzer

A Claude project that evaluates job postings against a senior cybersecurity executive's background. Drop in a job posting URL and get a structured fit analysis back, scored across eight dimensions, with a plain-language verdict on whether to apply.

Built for my own job search. Shared in case it's useful to adapt for yours.

---

## What it does

Paste a job posting URL or just the job desciption text into Claude. The project fetches the description, scores it across eight dimensions (domain expertise, executive communication, technical depth, commercial motion, etc.), and renders an interactive widget showing:

- An overall fit percentage with color-coded badge
- Horizontal bar chart of dimension scores
- Strengths vs. gaps breakdown, written honestly
- A bottom-line verdict with a clear apply/don't apply recommendation

It tracks roles across the project, so if you've evaluated five positions it'll tell you where the new one ranks.

---

## How to use it

1. Download [`cybersecurity-job-fit-analyzer-setup.html`](https://raw.githubusercontent.com/colemic2006/Cybersecurity-Job-Fit-Role-Analyzer/main/cybersecurity-job-fit-analyzer-setup.html) — open it in a browser and follow the instructions to copy the project prompt
2. Create a new Claude project at [claude.ai](https://claude.ai)
3. Paste the project instructions into your project's system prompt
4. Update the **My Background** section with your own experience, credentials, and known gaps
5. Drop job posting URLs into the chat

That's it. The project handles the rest.

---

## Adapting it for your background

The instructions have a clearly marked profile section. Replace:

- Credentials and years of experience
- Current and past roles
- Core strengths (the things you'd put in a cover letter)
- Known gaps (be honest here — the gap assessment is only useful if it reflects reality)
- Job search targets

The scoring weights are set for advisory and GRC roles. If you're in a different field, adjust the eight dimensions and the weighting guidance to match what actually matters for your target roles.

---

## Files

| File | Purpose |
|---|---|
| [`cybersecurity-job-fit-analyzer-setup.html`](https://github.com/colemic2006/Cybersecurity-Job-Fit-Role-Analyzer/blob/main/cybersecurity-job-fit-analyzer-setup.html) | Open this to get the Claude project instructions |
| `LICENSE` | MIT |

---

## License

MIT. Use it, modify it, share it.
