---
name: ai-rules
description: Sets up a short rules file that your AI reads before every task (drafts not actions, true claims only, ask when unsure, no secrets in files, plan first, prove it works, plain English, learn from corrections). Use it when someone says "set up my rules", "install my AI rules", "add rules to my CLAUDE.md", "make Claude follow my rules", or when they correct Claude and want the correction remembered as a rule.
---

# AI rules

This skill gives Claude ten plain working rules and helps the person make them their own. The rules live in their `CLAUDE.md`, which Claude Code reads at the start of every session, so they apply to every task without being repeated.

The ten rules are in `rules.md` next to this file. Read it first.

## Setting up the rules

1. Read `rules.md`.
2. Ask three short questions, one message, and wait for the answers:
   - What do you mostly use AI for (your work or business, in a line)?
   - What should never happen without your yes (for example sending emails, posting, spending money, deleting files)?
   - How do you like answers written (short and plain, detailed, bullets, your spelling)?
3. Adjust the rules to fit the answers. Keep them short. Rule 1 should name the things they said need their yes. Rule 9 should match how they like answers written. Add a line at the top saying what they use AI for, if they gave one. Don't invent anything they didn't say.
4. Ask where the rules should go:
   - this project only: `CLAUDE.md` in the current folder, or
   - every project: `~/.claude/CLAUDE.md`.
5. If that file already exists, read it. Never overwrite or reorder what's there. Plan to add a section called `## My AI rules` at the end. If a section with that name already exists, plan to update only that section.
6. Show the exact text you will add (or the before and after of the section) and ask "Add this?" Write nothing until they say yes. This matters because `CLAUDE.md` steers every future session, and the person should know exactly what's in it.
7. After writing, read the file back and confirm the section is there. Tell them the one thing to remember: whenever the AI gets something wrong, say so, and you'll offer to add it as a rule.

## Adding a rule later

When the person corrects you ("don't do that", "I told you to...", "always...", "never..."), finish fixing the mistake first. Then offer, in one line: "Want me to add that as a rule so I don't do it again?" If they say yes, write the rule as one short sentence, show it, and add it to the end of their `## My AI rules` section after a yes. Number it after the last rule. Don't offer for one-off preferences that only matter for this task.

## If they don't use Claude Code

If they are in a chat app (Claude in the browser, ChatGPT), there is no file to write. Give them the adjusted block from step 3 as one copy block and tell them where to paste it, using the "Where to paste it" part of `rules.md`.
