# Job Concierge: a job search run like a product

A Claude skill that runs a job search in seven stages and keeps everything in **your own Google Drive**.

- **Live demo (sample data):** https://n-tunison-test.github.io/job-concierge-agent-demo/
- **Download the skill:** [`job-search-coach.zip`](job-search-coach.zip)

## The seven stages
1. **What you're looking for**: builds a verified Profile from your resume and answers.
2. **How to find it**: a twice-daily digest of new roles, ranked by recency, then fit, then pay.
3. **How and when to customize**: a fit call decides how much to tailor your resume.
4. **Warm contacts**: who you know at each company, with a short honest note to send.
5. **Interview prep**: prep docs, practice rounds and speaking points.
6. **Negotiation**: what an offer is worth, your target and walk-away, a drafted reply.
7. **Market check**: researches the current market for your role, compares it with your own funnel, and ranks where to focus.

A dashboard shows what is working, built from counts only.

## Install
1. Download `job-search-coach.zip`. Do not unzip it.
2. In Claude: **Customize > Skills**, upload the ZIP.
3. In a new chat, turn on Google Drive, Docs, Sheets and (optionally) Gmail.
4. Say **"set up my job search"**. Setup takes about 30 minutes.
5. Every 4 to 6 weeks, say **"run a market check"**.

## Privacy and safety
- Your data stays in your Drive. This repo contains only fictional sample data.
- Claude never applies, sends or contacts anyone for you. Gmail use is limited to drafts addressed to you.
- Market figures in the demo are illustrative. The skill researches current sources each time it runs.

## What's here
- `index.html`: the demo site (static, no build step)
- `job-search-coach.zip`: the installable skill
