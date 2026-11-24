# AI rules

The rules file my AI reads before it does anything. Ten plain rules, with my own names and clients taken out, so you can use it as is.

It comes two ways:

- `rules.md`: the ten rules as one copy block, for any AI (Claude, ChatGPT, anything with custom instructions).
- `ai-rules/`: a Claude skill that sets the rules up for you, asks three quick questions to fit them to you, and adds new rules when your AI gets something wrong.

## Install

**Claude Code.** Paste this into Claude Code:

```
Install this skill for me: https://github.com/thomaswightt/ai-rules
```

Or copy the `ai-rules` folder into `~/.claude/skills/` yourself.

**Claude in the browser or desktop app.** Download [ai-rules.zip](https://github.com/thomaswightt/ai-rules/releases/latest/download/ai-rules.zip), then open Settings, Capabilities, Skills and upload it. (Menu names can move. Look for Skills in Settings.)

**ChatGPT, or no skills.** Open `rules.md`, copy the block and paste it into your custom instructions.

## Use it

Say "set up my rules". It asks what you use AI for, what should never happen without your yes, and how you like answers written. It shows you exactly what it will add to your `CLAUDE.md` and only writes it after you say yes. It never overwrites what's already there.

After that, whenever your AI slips, tell it. It offers to add that as a rule.

## Make it yours

The ten rules are a starting point. Change anything that doesn't fit, and add your own.

## More

I write one email every Wednesday: the AI stuff that mattered that week, what I built with it, and something you can copy. Join at [learnaiwiththomas.com](https://learnaiwiththomas.com/?utm_source=github&utm_medium=readme&utm_campaign=rules).

If something's broken, DM me on Instagram [@thomaswight__](https://www.instagram.com/thomaswight__/).
