# Red-Teaming: Adversarial LLM Testing Challenge

**Day 8 of 100** · Last updated 19 of August 2026

An ongoing, public challenge in adversarial testing of large language models — probing jailbreaks, prompt injection, and safety-boundary failures across GPT, Claude, and Gemini, with a focus on multi-turn attack chains.

This isn't a tutorial log. Each day documents a specific technique tested, what happened, and what it reveals about model behavior. The goal is a public, reproducible body of work in LLM red teaming — built one finding at a time.

## Highlights

- **https://snehasaravaiya.github.io/posts/day-07-conversation-level-drift/** — a stacked false-authority + time-pressure + academic-reframing jailbreak that reproduced across GPT-5.5 and Gemini. 


## Structure

```
/findings/       Polished writeups of significant discoveries — the good stuff, curated
/days/           Daily log, chronological, less polished — the raw record of the challenge
/techniques/     Attacks organized by category (prompt injection, role-play exploits, etc.)
Findings.csv     Tracked log of tested cases: technique, model, result, severity
```

## Why this exists

I'm building toward AI safety / red-teaming roles (targeting NVIDIA, Anthropic, OpenAI, DeepMind). This repo is the public proof-of-work: a running, honest record of adversarial testing practice — including the slow days, not just the wins.

## Links

- Blog: [SnehaSaravaiya.github.io](https://SnehaSaravaiya.github.io)
- LinkedIn: https://www.linkedin.com/in/sneha-saravaiya-624658383/


## Frameworks referenced

OWASP Top 10 for LLM Applications · NIST AI RMF · MITRE ATLAS
