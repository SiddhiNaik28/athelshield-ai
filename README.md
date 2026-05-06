# AthleShield AI ⚽

**Real-time AI-driven training load and injury risk management for grassroots football teams.**

> "Democratising sports science for every grassroots football team."

Live demo: [your-username.github.io/athleshield-ai](https://your-username.github.io/athleshield-ai)

---

## What It Does

AthleShield AI gives every grassroots football coach the injury prevention intelligence of a professional sports science team — free, on their phone.

- **Players** log 6 wellness metrics in 60 seconds each morning
- **AI analyses** 7-day load trends using the Acute:Chronic Workload Ratio method
- **Coach sees** a colour-coded squad dashboard with position-specific injury warnings
- **Training plan** generated with one tap, adjusted per player's risk level

---

## Deploy to GitHub Pages (3 steps)

### Step 1 — Create a GitHub repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `athleshield-ai`
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Upload the file
1. Click **Add file → Upload files**
2. Drag and drop `index.html`
3. Commit with message: `Initial deploy`

### Step 3 — Enable GitHub Pages
1. Go to **Settings → Pages**
2. Under Source, select **Deploy from a branch**
3. Select branch: `main`, folder: `/ (root)`
4. Click **Save**
5. Wait 60 seconds → your site is live at `https://your-username.github.io/athleshield-ai`

---

## Using the Live AI Demo

1. Open the **Player Log** tab
2. Enter your **Anthropic API key** (get one free at [console.anthropic.com](https://console.anthropic.com))
3. Adjust the sliders for any player
4. Click **Analyse with AI Physio**
5. The AI returns a real Readiness Score + injury risk + position-specific recommendations in real time

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| AI Engine | Claude API (claude-sonnet-4) |
| Backend | Firebase Firestore + Functions |
| Frontend | HTML + CSS + Vanilla JS (this prototype) |
| Hosting | GitHub Pages / Firebase Hosting |

---

## The AI System Prompt (Core Engine)

```
You are a certified sports physiologist specialising in football injury 
prevention for grassroots teams. Apply the acute:chronic workload ratio 
(ACWR) method. Map position-specific injury risks (hamstring/groin for 
wingers, knee for defenders, shoulder for goalkeepers). Flag cumulative 
fatigue spikes. Output: Readiness Score, Risk Level, specific injury 
prediction, adjusted training recommendation.
```

---

## Hackathon Submission

- **Track:** Sports Innovation
- **Category:** AI-First Application
- **Sport:** Football (Soccer)
- **Problem:** Grassroots coaches manage 15–25 players with zero fatigue monitoring tools
- **Solution:** AI physiologist that predicts injuries before they happen

---

Built in 24 hours for the Sports Hackathon 2025.
