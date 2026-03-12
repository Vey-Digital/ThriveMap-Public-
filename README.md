<div align="center">

# ThriveMap™

**Structured reflection for clarity, resilience, and intentional decision-making.**

Developed by **VeyDigital**

<br>

<img src="https://img.shields.io/badge/Expo-000000?style=flat&logo=expo" alt="Expo">
<img src="https://img.shields.io/badge/React%20Native-20232A?style=flat&logo=react" alt="React Native">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript" alt="TypeScript">

<br><br>

## Product Walkthrough

**Guided walkthrough · 55 seconds**

<video src="assets/DamneunThriveMap_2026-03-11%2016-47-48.mp4" controls width="100%"></video>

</div>

---

## Overview

**ThriveMap** is for people who want more than a blank page.

When life feels uncertain, stressful, or hard to sort through, ThriveMap helps users slow down, reflect with structure, and move forward with greater intention. Instead of relying only on open-ended journaling, the app guides reflection through thoughtful prompts that support clarity, emotional steadiness, and better decision-making over time.

ThriveMap can be especially helpful during:

- career transitions  
- layoffs or organizational change  
- leadership growth  
- personal reflection and life direction  

At its core, ThriveMap is about one thing:

**turning reflection into meaningful action.**

---

# The ThriveMap Loop

<div align="center">

A repeatable system designed for clarity, consistency, and momentum.

<br/>

<img src="https://img.shields.io/badge/1%20Define-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/2%20Rehearse-6d28d9?style=for-the-badge" />
<img src="https://img.shields.io/badge/3%20Track-1f2937?style=for-the-badge" />
<img src="https://img.shields.io/badge/4%20Reflect-374151?style=for-the-badge" />

</div>

---

# Why ThriveMap Exists

When people feel burned out, laid off, disconnected, uncertain about relationships, or afraid of change, the mind narrows to survival.

ThriveMap widens the lens by turning intention into a **daily, trackable practice loop**.

---

# What You Get

## 🧠 Domain Sessions

**1-minute imagine + 5-minute writing** across:

- Personal  
- Professional  
- Social  
- Integrated

**Outcome:** clearer goals, stronger self-definition, and better decisions.

---

## 🔁 7-Day Rotation

A guided daily practice that rotates domains automatically.

**Outcome:** consistency without overwhelm.

---

## 📊 Weekly Log Grid

A visual weekly grid to mark completion and notes.

**Outcome:** momentum you can see.

---

## 🔐 Private by Default

- No login required  
- No backend dependency  
- Data stays local  
- Export only when you choose

**Outcome:** trust and long-term retention.

---

<details>
<summary><strong>Why this retains users</strong></summary>

ThriveMap is designed around a repeatable behavioral loop:

**Define → Rehearse → Track → Reflect**

This loop supports daily engagement, weekly completion, and long-term identity reinforcement.

AI increases perceived value by extracting patterns from reflection data without replacing the practice itself.

</details>

---

# Getting Started

Install dependencies:

```bash
npm install



## What’s next is launch packaging + final smoke test, not more code.
1) Do a 12-minute smoke test (must do)
On each platform you will ship (at minimum iOS + web, ideally Android too):
Open app → no blank screen
Home shows Cycle label + Start Today/Review Today
Tap Start Today → lands on correct /exercise/<domain>
Complete flow → go back Home → CTA flips to Review Today
Tap Review Today → lands on Log
Go Profile → scroll to bottom (no layout jumps)
Export → generate/export (or at least open export screen)
Reset modal opens and cancels correctly (don’t actually reset unless you want)
If any one of these fails, fix only that.
2) Decide what you’re shipping first
Web-only launch (fastest) via Vercel/static hosting
Mobile store launch via EAS build + TestFlight/Play Console
If you’re doing stores, the next steps are store assets and policies.
3) Store assets you need (minimum)
App icon (already)
Splash (already)
6 screenshots (Home, Exercise, Profile, Domain Architecture, Weekly Consistency, Export/Privacy)
Short description (1–2 lines)
Full description (8–12 lines)
Privacy Policy URL + Terms URL
If you don’t have hosted policy pages yet, that’s the #1 blocker for App Store submission.
4) Clean warnings (optional, but recommended)
Warnings won’t block you, but for “v1.0 polish”:
Remove unused constants/components OR move them to a design/ scratch file
Leave react-hooks/exhaustive-deps warnings only if intentional (add inline disables with a comment)
5) The “3-line Home header premium” tweak
If you still want that last perceived-quality bump: do it now, then stop touching UI.
Only do this if it doesn’t cascade. Otherwise, ship.
If you tell me which launch you’re doing first:
(A) Web launch or (B) App Store / Play Store,
I’ll give you the exact next checklist with the commands (EAS build/TestFlight/Play Console or Vercel deploy) and the copy you need.


## What you personally should do next (outside the agent)
1. Record a 20-second demo video
Show:
1️⃣ Cycle screen
2️⃣ Start Today
3️⃣ Visualization exercise
4️⃣ Profile system
This becomes:
App Store preview
website video
product tweet
2. Create screenshots (6)
Home — Cycle + Start Today
Exercise visualization
Domain Architecture
Cycle Progress
Weekly Consistency
Data Sovereignty
3. Tag the release
Commit:
v1.0.0
Initial public release of ThriveMap
Structured identity training system
Honest product evaluation
What you built is not a typical habit app.
It’s closer to a structured cognitive training tool.
That positioning is actually stronger if marketed correctly.


3. App Store readiness
You need 6–8 screenshots.
Recommended set:
1️⃣ Home screen (Cycle + Start Today)
2️⃣ Visualization exercise
3️⃣ Domain Architecture
4️⃣ Cycle Progress
5️⃣ Weekly Consistency
6️⃣ Data Sovereignty
7️⃣ Export / Privacy
Caption example:
Design your future.
Practice it daily.
4. App description (short version)
You will need this.
Title
ThriveMap — Design Your Future
Tagline
A structured self-training system for clarity, focus, and intentional growth.
Short description
ThriveMap helps you design and practice your future through a structured weekly reflection cycle.

Each day you visualize and write about one life domain:
Personal
Professional
Social
Integrated

## The system uses repetition to strengthen clarity and decision making.

No accounts.
No cloud tracking.
Your data stays on your device.
5. Privacy / trust signals
This is important for credibility.
You already have:
Data Sovereignty
System Boundaries
Local Export
Before release add one short privacy line on the store page:
ThriveMap stores your data locally on your device.
Nothing is uploaded or tracked.
6. Analytics (optional but recommended)
Even if privacy-focused, you should track basic events.
Examples:
app_open
start_today_pressed
exercise_completed
export_pressed
reset_pressed
Expo + PostHog works well for this.


## Example flow for demo:
Home screen
Exercise intro
Personal domain timer
Writing section
Visualization timer
