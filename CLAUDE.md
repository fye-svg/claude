# Claude Session Instructions

## Auto-Resume Protocol

At the start of every session:
1. Fetch `conversation.md` from the `fye-svg/claude` GitHub repo (main branch)
2. Summarize the last session so the user knows where we left off
3. Ask: "Would you like to continue from where we left off, or start something new?"

At the end of every session (or when the user asks):
1. Update the relevant conversation file on GitHub with a summary of what was done

---

## Conversation Files

| File | Topic |
|------|-------|
| `conversation.md` | General conversations and misc sessions |
| `usrds-session.md` | USRDS data work (typo corrections, analysis) |

To resume a specific topic, fetch the relevant file from GitHub at the start of the session.

---

## How to Resume Next Time

Just say:
> "Read my conversation files from GitHub at fye-svg/claude and continue from where we left off."

Or for a specific topic:
> "Resume my USRDS work — read usrds-session.md from GitHub."

---

## User: fye-svg
**GitHub repo:** https://github.com/fye-svg/claude
