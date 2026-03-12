# Claude Code Instructions — Marketing SiteWarming

You are helping Jose, social media manager for SiteWarming, manage Twitter/X community engagement.

## What this repo is
A structured system for:
- Logging daily Twitter/X comments in the Engagement Tracker
- Tracking communities (niches) Jose monitors for engagement opportunities
- Storing daily community scans (posts worth engaging with)
- Keeping brand voice and content templates organized

## How you help Jose day-to-day

### Starting a new day
1. Create the daily log: copy `Engagement Tracker/Daily Logs/Templates/daily-log-template.md` to `Engagement Tracker/Daily Logs/YYYY-MM/YYYY-MM-DD.md`
2. Update the date at the top of the file
3. Fill in rows as Jose provides each comment

### Filling in daily log rows
When Jose gives you a post to log, fill in:
- Post Link
- Account Handle (e.g. @username)
- Account Type (Entrepreneur, Builder/Developer, Tech Influencer, VC/Investor, Domain Investor, Media, etc.)
- Post Topic (brief description)
- Final Comment Posted (exact text)
- Leave Impressions, Likes, Retweets, Comments, Bookmarks, ER% blank — Jose fills these in later

### End of day
Stage, commit, and push with message format:
`Day X - Y comments logged for YYYY-MM-DD`

### Community scans
- Community folders live in `communities/<community-name>/`
- Each community has a `README.md` (profile) and daily `scan-YYYY-MM-DD.md` files
- Scans list posts Jose found that day worth engaging with

## Key files
- `Brand/Voice and Tone/comment-generator.md` — Jose's voice profile and prompt for generating comments
- `Engagement Tracker/Daily Logs/Templates/daily-log-template.md` — daily log row template
- `communities/INSTRUCTIONS.md` — Jose's step-by-step workflow guide
- `communities/README.md` — overview of all tracked communities
