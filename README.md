<div align="center">

## @VeyDigital  
### Building Intelligence Layers

<br/>

# ThriveMap

**Design your future. A structured self-training platform.**

<br/>
<div align="center">
  <a href="https://your-live-demo-url.com">
    <img
      src="https://raw.githubusercontent.com/Vey-Digital/ThriveMap/last_night_ui/assets/thrivemap.app_mockup.gif"
      width="380"
      alt="ThriveMap Live Demo"
    />
  </a>
</div>

## Practice-driven. Human-led.  
AI functions as an insight layer that extracts patterns from reflection data  
and strengthens decision clarity without replacing the core exercise.

<br/>

<a href="https://your-live-demo-url.com">
  <img src="assets/thrivemap.app_mockup.gif" width="380" alt="ThriveMap Live Demo" />
</a>

<br/>
<br/>

<img src="https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=expo&logoColor=white" />
<img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Local--Only%20Data-6d28d9?style=for-the-badge" />
<img src="https://img.shields.io/badge/No%20Login%20Required-1f2937?style=for-the-badge" />

</div>

---

## The ThriveMap Loop

<div align="center">

A repeatable system designed for clarity, consistency, and momentum.

<br/>

<img src="https://img.shields.io/badge/1%20Define-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/2%20Rehearse-6d28d9?style=for-the-badge" />
<img src="https://img.shields.io/badge/3%20Track-1f2937?style=for-the-badge" />
<img src="https://img.shields.io/badge/4%20Reflect-374151?style=for-the-badge" />

</div>

---

## Why ThriveMap Exists

When people feel burned out, laid off, disconnected, uncertain about relationships, or afraid of change, the mind narrows to survival.  

ThriveMap widens the lens by turning intention into a daily, trackable practice loop.

---

## What You Get

### 🧠 Domain Sessions
1-minute imagine + 5-minute writing across:
- Personal  
- Professional  
- Social  

**Outcome:** clearer goals, stronger self-definition, better decisions.

---

### 🔁 7-Day Rotation
A guided daily practice that rotates domains automatically.

**Outcome:** consistency without overwhelm.

---

### 📊 Weekly Log Grid
A simple weekly grid to mark completion and notes.

**Outcome:** momentum you can see.

---

### 🔐 Private by Default
- No login required  
- No backend dependency  
- Data stays local  
- Export only when you choose  

**Outcome:** trust and retention.

---

<details>
<summary><strong>Why this retains</strong></summary>

ThriveMap is designed around a repeatable behavioral loop:

**Define → Rehearse → Track → Reflect**

This loop supports daily engagement, weekly completion, and long-term identity reinforcement.

AI increases perceived value over time by extracting patterns from user-generated reflection data without replacing the practice.

</details>

---

## Status

This repo is a **public prototype** used to test UX flows, copy, and visual layout.
<div align="center">

<a href="https://your-live-demo-url.com">
  <img src="./assets/thrivemap.app_mockup.gif" width="380" alt="ThriveMap Demo" />
</a>

</div>
---

## Built for Every Device

ThriveMap runs on React Native and Expo, working seamlessly across iOS, Android, and web.

The interface adapts through:

- Smart safe-area handling
- Responsive spacing
- Adaptive typography
- Flexible layouts
- Breakpoint testing across small and large devices

---

## Theme System — “Night Ritual” Palette

---

## Theme System — Night Ritual

ThriveMap’s visual system is built on a deep indigo foundation inspired by my iterative exploration inside  
[PixelBot by T.D.](https://chatgpt.com/g/g-zCVkaCE5X-pixelbot-by-t-d).

I didn’t want this to feel like another productivity dashboard.

I wanted something calmer. More immersive. Something that feels intentional when you open it at night  reflective, focused, and slightly cinematic.

The goal isn’t visual noise.  
It’s quiet clarity.

Dark gradients create depth.  
Mint highlights signal progress.  
Purple undertones add warmth without becoming loud.

The result feels less like “task management” and more like a nightly ritual for alignment.

---

## Core Palette

### Core Colors

- Deep Ink — `#0F0D1A`
- Indigo Base — `#2A245E`
- Mid Indigo — `#3A4789`
- Violet — `#5C5793`
- Plum — `#52365D`
- Soft Lavender Text — `#8B759C`
- Light Neutral — `#EEEDF0`
- Cool Gray — `#9A9BA3`

### Accent

- Mint Highlight — `#88EAB2`

---

## Accent Logic

| Meaning              | Color       |
|----------------------|-------------|
| Active / Complete    | `#88EAB2`   |
| Progress / Today     | `#88EAB2`   |
| Informational / Tag  | `#8B759C`   |
| Muted / Disabled     | `#9A9BA3`   |

Mint always signals forward movement. Never decoration.

---

## Color Token Example

```ts
export const colors = {
  bg: "#0F0D1A",
  bgGradientA: "#2A245E",
  bgGradientB: "#5C5793",

  surface: "rgba(255,255,255,0.06)",
  border: "rgba(255,255,255,0.10)",

  textPrimary: "#FFFFFF",
  textSecondary: "#C9C7D6",
  textMuted: "#9A9BA3",

  accentMint: "#88EAB2",
  accentLavender: "#8B759C",
};
