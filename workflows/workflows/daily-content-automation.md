# Daily Content Automation Workflow

This workflow describes the exact steps your AI content system will perform every day to generate, edit, and publish motivational content automatically.

---

## 1. Daily Prompt Generation (Copilot)
- Copilot generates 3 motivational prompts every morning.
- Prompts follow your brand tone: uplifting, disciplined, positive.
- Output is saved into `/prompts/daily/`.

---

## 2. Visual Creation (Canva + CapCut)
- Canva loads a faceless template with your brand colors.
- Copilot inserts the daily prompt into the template.
- CapCut adds motion, transitions, and background audio.
- Exported video is saved to `/assets/daily/`.

---

## 3. Automated Upload (Make.com or Zapier)
- Automation tool watches `/assets/daily/` for new videos.
- When a new file appears:
  - Upload to TikTok
  - Upload to Instagram Reels
  - Upload to YouTube Shorts
- Each upload includes:
  - AI‑generated caption
  - Hashtags based on trending topics
  - Scheduled posting time (8:00 AM EST)

---

## 4. Analytics Tracking (Notion or Airtable)
- Engagement data is collected automatically:
  - Views
  - Likes
  - Shares
  - Watch time
- Copilot analyzes the data weekly and generates:
  - A performance summary
  - Recommendations for improvement

---

## 5. Weekly Optimization
- Copilot reviews:
  - Best‑performing prompts
  - Best posting times
  - Best video styles
- System updates:
  - Prompt templates
  - Visual templates
  - Scheduling rules

---

## Goal
To create a **hands‑free daily content system** that produces, edits, and publishes motivational content automatically — scaling your brand without manual effort.
