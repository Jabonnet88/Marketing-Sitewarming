# How to Use the Communities System

This is your step-by-step daily workflow for finding posts, logging scans, and tracking engagement.

---

## Step 1 — Start your day in Claude Code

Tell Claude Code:
> "Create today's daily log"

Claude will copy the template and set up `Engagement Tracker/Daily Logs/YYYY-MM/YYYY-MM-DD.md` with today's date.

---

## Step 2 — Scan your Twitter/X feed

Go through your feed and find 15 posts worth engaging with. Focus on:
- Posts with strong opinions you can push back on or build on
- Posts where your comment can add a stat, a story, or a deeper angle
- Accounts in your 5 communities (see `communities/README.md`)

---

## Step 3 — Log a scan (optional but recommended)

If you want to keep a record of what you found before commenting, tell Claude:
> "Create a scan for [community name] for today"

Or paste this format directly into a new file:

```
# Scan — [Community Name] — YYYY-MM-DD

| # | Post Link | Account | Post Topic | Engaged? |
|---|---|---|---|---|
| 1 | | | | Yes / No |
```

Save it as `communities/[community-name]/scan-YYYY-MM-DD.md`

---

## Step 4 — Write your comments

Use `Brand/Voice and Tone/comment-generator.md` if you need help drafting:
1. Open the file
2. Copy everything from "YOUR TASK" down
3. Paste it into Claude (browser or Claude Code)
4. Add the tweet text at the bottom
5. Get Option A (analytical) and Option B (contrarian) back
6. Pick one, tweak one word if needed, post it

---

## Step 5 — Log each comment

After posting, tell Claude Code:
> "Fill in row X with: [details]"

Provide:
- Post Link
- Account Handle
- Account Type
- Post Topic
- Final Comment Posted (exact text you posted)
- Leave Impressions, Likes, RTs, Comments, Bookmarks, ER% blank

---

## Step 6 — End of day: commit and push

Tell Claude Code:
> "Stage, commit, and push all changes with the message 'Day X - Y comments logged for YYYY-MM-DD'"

---

## Account Type Reference

Use these exact labels in the Account Type column:

- `Entrepreneur`
- `Builder/Developer`
- `Tech Influencer`
- `VC/Investor`
- `Domain Investor`
- `Media`
- `Motivational/Mindset`

---

## Tips

- Aim for 15 comments per day
- Mix comment styles: CONTRARIAN, DATA, AFFIRMATION, STORY, QUESTION
- Don't mention SiteWarming unless it's directly and naturally relevant
- Short is better — under 280 characters if possible, never over 400
