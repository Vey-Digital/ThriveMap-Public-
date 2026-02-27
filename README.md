<div align="center">

## @VeyDigital  
### Building Intelligence Layers

<br/>

# ThriveMap

**Design your future. A structured self-training platform.**

<br/>

<p>
Practice-driven. Human-led.<br/>
AI functions as an insight layer that extracts patterns from reflection data<br/>
and strengthens decision clarity without replacing the core exercise.
</p>

<br/>

<img
  src="https://github.com/user-attachments/assets/ad9210ab-ce3c-4d5f-a031-e74aaa2778e3"
  alt="ThriveMap Home"
  width="380"
/>

<br/>
<br/>

<img src="https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=expo&logoColor=white" />
<img src="https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Local--Only%20Data-6d28d9?style=for-the-badge" />
<img src="https://img.shields.io/badge/No%20Login%20Required-1f2937?style=for-the-badge" />

<br/>
<br/>

</div>
<div align="center">
  <a href="https://your-live-demo-url.com" target="_blank">
    <img src="assets/thrivemap.app_mockup.gif" width="380" alt="ThriveMap Live Demo" />
  </a>
</div>
---

<div align="center">

## The ThriveMap Loop

<p>
A repeatable system designed for clarity, consistency, and momentum.
</p>

<br/>

<img src="https://img.shields.io/badge/1%20Define-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/2%20Rehearse-6d28d9?style=for-the-badge" />
<img src="https://img.shields.io/badge/3%20Track-1f2937?style=for-the-badge" />
<img src="https://img.shields.io/badge/4%20Reflect-374151?style=for-the-badge" />

<br/>
<br/>

</div>

---

## Why ThriveMap Exists

When people feel burned out, laid off, disconnected, uncertain about relationships, or afraid of change, the mind narrows to survival.  
ThriveMap widens the lens by turning intention into a daily, trackable practice loop.

---

## What You Get

### 🧠 Domain Sessions
**1-minute imagine + 5-minute writing** across:
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
<summary><strong> Why this retains</strong></summary>

ThriveMap is designed around a repeatable behavioral loop:
Define → Rehearse → Track → Reflect.

This loop supports daily engagement, weekly completion, and long-term identity reinforcement.
AI increases perceived value over time by extracting patterns from user-generated reflection data without replacing the practice.
</details>

---

## Status

This repo is a **public prototype** used to test UX flows, copy, and visual layout.


## Built for Every Device. 
ThriveMap runs on React Native and Expo, which means it works seamlessly across iOS, Android, and web. Whether someone is using a compact phone or a larger display, the experience stays consistent and intentional.
The interface adapts intelligently through:
• Smart safe-area handling for edge-to-edge screens
• Responsive spacing and adaptive typography for smaller devices
• Flexible layouts without rigid pixel constraints
• Careful testing across common breakpoints, from small Android devices to iPhone SE and larger iPhone or Pixel screens

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/178102eb-18f5-455d-9ea5-8e9cc18a91ed" width="300" />
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/fc1b3736-a293-4ee1-b376-eee8840c103c" width="300" />
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/e5d2aae8-a777-478c-8c38-2bf66ab87b22" width="300" />
    </td>
  </tr>
</table>

</div>

## Theme System — “Night Ritual” Palette

The visual system uses a premium deep-indigo foundation inspired by exploration and iterative refinement inside **PixelBot by T.D.**

Reference:
https://chatgpt.com/g/g-zCVkaCE5X-pixelbot-by-t-d

The goal is to create a calm, modern, and brandable interface that feels reflective, intentional, and high-end — more “night ritual” than “productivity dashboard.”

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

- Mint Highlight (Progress / “Today”) — `#88EAB2`

---

## Why This Theme Works

- Dark gradient + strong white typography creates **calm authority**
- Mint accent signals **progress and clarity** without neon harshness
- Restrained dark UI allows imagery and content cards to stand out
- Purple undertones add warmth without losing depth

The result feels intentional, immersive, and premium.

---

## Production Refinements

### 1️⃣ Increase Secondary Text Contrast

Use:
- `#C9C7D6` for secondary text  
- `#9A9BA3` strictly for tertiary/muted labels  

This improves accessibility while preserving softness.

---

### 2️⃣ Unify Accent Logic

Accent colors follow strict semantic rules:

| Meaning              | Color       |
|----------------------|-------------|
| Active / Complete    | `#88EAB2`   |
| Progress / Today     | `#88EAB2`   |
| Informational / Tag  | `#8B759C`   |
| Muted / Disabled     | `#9A9BA3`   |

Mint is never decorative.  
It always signals state or forward movement.

---

### 3️⃣ Reduce Visual Saturation Layers

The UI includes:
- Background gradient
- Decorative circle overlays
- Card glow
- Elevation layers

To maintain calm layering:

- Reduce decorative circle opacity by ~15–25%
- Keep card glow subtle
- Preserve depth without increasing noise

---

##  Set

```ts
export const colors = {
  // Background
  bg: "#0F0D1A",
  bgGradientA: "#2A245E",
  bgGradientB: "#5C5793",

  // Surfaces
  surface: "rgba(255,255,255,0.06)",
  border: "rgba(255,255,255,0.10)",

  // Text
  textPrimary: "#FFFFFF",
  textSecondary: "#C9C7D6",
  textMuted: "#9A9BA3",

  // Accents
  accentMint: "#88EAB2",
  accentLavender: "#8B759C",
};

