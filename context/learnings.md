# Learnings

## Copilot Tips

- **Auto-loaded context is everything** — `.github/copilot-instructions.md` is the equivalent of CLAUDE.md. If context doesn't load automatically, people won't use it. *Why it matters:* manual context loading kills adoption for non-technical teams.
- **Layered context beats one big file** — point the instructions file at separate context files (me, projects, learnings) instead of cramming it all in one place. *Why it matters:* keeps each file maintainable and lets Copilot read only what's relevant.

## Workflow Tips

- **Bake maintenance into the AI's behavior, not the user's** — tell Copilot to update context files as part of every interaction. People don't maintain docs manually, but AI will if you instruct it. *Why it matters:* learned from Arbiter's CLAUDE.md pattern — the "always update documentation after making changes" rule is what keeps context fresh.
- **Pattern detection drives skill creation** — watch for repeated tasks, then promote them to reusable skills. Three occurrences = time to automate. *Why it matters:* skills should emerge from real usage, not be designed upfront.

## Tool Tips

- **Copilot CLI for terminal-shy users** — `gh copilot suggest` and `gh copilot explain` are the gateway for people who aren't comfortable with shell commands. Start here, not with code completion. *Why it matters:* the creative team's first win should be "I can do terminal things without memorizing commands."
