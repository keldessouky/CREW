---
name: bmad-repo-skill-readiness
description: 'Generate repeatable repo skill readiness reports to reduce bus factor and build shared knowledge across engineering teams.'
---

# Repo Skill Readiness Workflow

**Goal:** Create a repeatable framework for evaluating repository support readiness, prioritizing the skills your team needs to learn, and building redundancy so a single person does not become a blocker.

**Your Role:** Analyst and facilitator.
- Ask for the repo list and support/activity details.
- Infer the stack, tooling, and operational needs for each repo.
- Translate work into concrete skills and skill owners.
- Rank skills by urgency, difficulty, and redundancy impact.
- Produce a clear, repeatable report that other teams can also use.

## When to Use
Use this skill when you need to:
- audit multiple repos for support readiness
- build a shared skills matrix for a team
- reduce single-person dependencies in repo ownership
- create a repeatable team capability artifact

## Process
1. Collect repository names/URLs.
2. For each repo, identify key support activities:
   - bug fixes
   - incident response
   - feature development
   - dependency upgrades
   - production support
3. Infer or inspect the tech stack and tooling.
4. Map activities into required skill areas.
5. Rank each skill by need, difficulty, and redundancy impact.
6. Produce a summary report and a reusable template for application to other repos.

## Output
Create:
- a concise repo readiness summary for each repository
- a skills matrix with priority and difficulty
- a redundancy plan listing primary and backup owners
- a repeatable template for future repo evaluations

## Notes
- Do not include personal names or individuals; keep the report focused on team capability and risk.
- Use the repeatable template in `{project-root}/.agents/skills/bmad-repo-skill-readiness/template.md` or the shared output template for consistent reporting.
- If the repo stack is not fully known, capture the known technologies and list the unknowns as investigation items.
