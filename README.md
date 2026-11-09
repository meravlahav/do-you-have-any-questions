# do-you-have-any-questions - a Claude skill for technical interviews

**"Do you have any questions for us?"**
It's the second gift question of every interview: you know it's coming at the end, and you can prepare for it. But most candidates ask generic questions ("What's the culture like?"), and miss the chance to show they did real research.

This skill turns Claude into a research partner that helps you prepare 3-4 sharp questions. Each one ties the company's product and business to the role you're interviewing for, and fits the person interviewing you.

## What you get
- A short research pass on the company: product, customers, business model, recent news, and other open positions (they reveal a lot about internal structure and what's hard)
- The 2-3 "tension points" where the business, the product and your role meet
- 3-4 questions, each with a specific hook from the research and a one-line "why it works"
- Questions matched to the interviewer: recruiter, team lead, tech lead, VP R&D or CTO, CEO or founder
- A quality check: one breath per question, one thing per question, no generic questions, nothing the website already answers
- Optional: a document with company background, the questions, and a glossary of terms

## What you need to do
1. Tell Claude **which role** you're interviewing for (company and job title, a link to the job posting if you have one).
2. Tell Claude **who the interview is with** (recruiter, team lead, tech lead, VP R&D, CTO, founder...).
3. Read the questions and pick the ones that sound like you.

## Requirements
- **Web search must be enabled in Claude.** The skill researches the company online. Without it, it can't find the facts the questions are built on.
- Code execution enabled in your settings (required for skills).

## Install (claude.ai, about 1 minute)
1. Download `do-you-have-any-questions.zip` from this repo (don't unzip it).
2. In Claude, go to **Customize > Skills**, click **+**, then **Create skill**, then **Upload a skill**, and upload the ZIP.
3. Make sure the skill is toggled on.
4. Open a new chat and write something like: *"I have an interview for a backend developer role at [company], with the team lead. Prepare questions for the end of the interview."*

The skill is just a text file (`do-you-have-any-questions/SKILL.md`), so you can read exactly what it does before installing.

## Pairs well with
[tell-me-about-a-project](https://github.com/meravlahav/tell-me-about-a-project) - prepare the "tell me about a project you worked on" question, through the eyes of a technical interviewer.

---

*Built from a real interview preparation process. Feedback and improvements are welcome. Open an issue or a PR.*
