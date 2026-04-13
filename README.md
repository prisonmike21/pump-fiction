# Pump Fiction

A personalized daily workout and meal-planning app that adapts to your goal, schedule, equipment, energy, injuries, and available food. Built for a live class demo.

## Setup

**Zero dependencies. No install required.**

```bash
open index.html
```

## What's New (v2)

- **Schedule-Aware Timing** — enter your wake/sleep times, busy blocks, and preferred window. The app recommends the best workout slot and effort level.
- **Injury & Limitation Awareness** — flag issue areas (knee, shoulder, lower back, etc.) and movement restrictions. The app filters out aggravating exercises, explains why, and offers light mobility suggestions.
- **Coach Chat** — after generating a plan, refine it conversationally. Say "I only have 20 minutes", "my knee hurts", "make this upper body", "I don't have a bench", or "make meals simpler". The chat actually updates the visible plan.
- **Stronger Workout Engine** — workout title, training intent, time-aware compression (20 min = express), energy/stress/soreness adjustments, injury filtering.
- **Stronger Meal Engine** — "best next meal" suggestion, food matching, pre/post workout snacks from your available foods.
- **Upgraded Demo Mode** — realistic persona with recomp goal, mild knee issue, schedule blocks, and food list. Produces excellent output every time.
- **Upgraded Presenter Mode** — larger type, card-by-card stepping with arrow keys.
- **Static Fallback** — hardcoded output ensures the demo never fails.

## 2-Minute Live Demo Script

### Setup (30 seconds before)
1. Open `index.html` in Chrome/Safari
2. Click **Presenter Mode** (top right)

### Demo Flow

**[0:00] Intro** (10s)
> "This is Pump Fiction - a personalized fitness copilot that adapts to how you actually feel today, what equipment you have, your schedule, and even your injuries."

**[0:10] Demo Mode** (10s)
> Click **Demo Mode**. The form fills with a realistic profile.
> "Here's someone doing body recomp, 45 minutes, has dumbbells and bands, mild knee issue - no jumping or deep squats. They have classes until 4pm."

**[0:20] Generate** (10s)
> Click **Generate Today's Plan**. Wait for loading.

**[0:30] Walk Through** (50s)
> Use **Arrow keys** to step through cards:
> 1. **Timing** — "It found the best workout slot at 4:30pm - after their classes, before dinner."
> 2. **Workout** — "Notice: no jump squats, no deep lunges. All knee-friendly. Hip thrusts, lateral walks, calf raises."
> 3. **Intensity** — "Moderate effort recommended given their stress level."
> 4. **Injury Adjustments** — "It explains exactly what it changed and why. Plus light mobility for the knee."
> 5. **Meals** — "Built from foods they actually listed - eggs, chicken, yogurt, tortillas."
> 6. **Snacks** — "Pre and post workout matched to their pantry."

**[1:20] Coach Chat** (30s)
> Scroll to Coach Chat. Click "I only have 20 minutes now".
> "Watch - it regenerates the workout in real time. Fewer exercises, compressed format."
> Click "My knee feels worse".
> "Now it tightens the restrictions further and adds more mobility work."

**[1:50] Close** (10s)
> "Every output adapts to real constraints - schedule, injuries, time, food. That's what makes it a copilot, not a template."

## Technical Details

- Single HTML file, zero dependencies, works fully offline
- All logic is deterministic and local - no external APIs
- Exercise database with injury tags for intelligent filtering
- Rule-based coach chat with intent detection
- Static fallback output ensures demo reliability
