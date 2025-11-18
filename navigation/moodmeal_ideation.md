---
toc: True
layout: post
data: tools
title: MoodMeal
permalink: /MoodMeal
breadcrumb: True 
---

<div style="background:#111; padding:50px 40px; border-radius:18px; color:#F8F5EF; text-align:center; box-shadow:0 30px 60px rgba(0,0,0,0.35);">
  <div style="font-size:60px;">🍽️ MoodMeal</div>
  <div style="font-size:26px; letter-spacing:0.2em; text-transform:uppercase; margin-top:12px; color:#E2C9A5;">Eat How You Feel</div>
  <div style="margin-top:30px; font-size:16px; letter-spacing:0.08em;">Concept board · Visual UX sketch · Emotion-driven dining</div>
</div>

---

<div style="display:grid; grid-template-columns:2fr 1fr; gap:20px; margin:40px 0;">
  <div style="background:#1A1F2B; padding:30px; border-radius:18px; color:#F7EFE3;">
    <div style="font-size:14px; letter-spacing:0.2em; color:#C3B186; text-transform:uppercase;">Style board</div>
    <div style="display:flex; gap:16px; margin-top:16px;">
      <div style="flex:1; background:#2D4356; border-radius:12px; height:110px; display:flex; align-items:flex-end; padding:12px; font-weight:600;">#2D4356<br/>Deep Slate</div>
      <div style="flex:1; background:#8B6F47; border-radius:12px; height:110px; display:flex; align-items:flex-end; padding:12px; font-weight:600;">#8B6F47<br/>Warm Clay</div>
      <div style="flex:1; background:#E8DCC4; border-radius:12px; height:110px; display:flex; align-items:flex-end; padding:12px; color:#2D2A24; font-weight:600;">#E8DCC4<br/>Soft Cream</div>
    </div>
    <div style="display:flex; gap:20px; margin-top:28px;">
      <div style="flex:1; background:#131824; border-radius:12px; padding:20px;">
        <div style="font-size:32px; font-family:'Poppins','Nunito',sans-serif;">Aa</div>
        <div style="margin-top:6px; letter-spacing:0.08em;">Rounded headings · Friendly accent lines</div>
      </div>
      <div style="flex:1; background:#1F2937; border-radius:12px; padding:20px;">
        <div style="display:flex; gap:14px; flex-wrap:wrap;">
          <div style="padding:10px 20px; border-radius:999px; background:#8B6F47; color:#F7EFE3;">Primary Button</div>
          <div style="padding:10px 20px; border-radius:20px; border:1px dashed #E8DCC4;">Ghost Tag</div>
          <div style="width:100px; height:60px; border-radius:24px; border:2px solid #E8DCC4;"></div>
        </div>
        <div style="margin-top:10px; font-size:12px; letter-spacing:0.2em; color:#C3B186;">Soft edges · pill buttons · airy cards</div>
      </div>
    </div>
  </div>
  <div style="background:#F0EBE0; color:#2B2117; border-radius:18px; padding:24px; box-shadow:0 20px 50px rgba(0,0,0,0.15); display:flex; flex-direction:column; justify-content:space-between;">
    <div style="font-size:13px; letter-spacing:0.2em; text-transform:uppercase; color:#8B6F47;">Mood vibe</div>
    <div style="font-size:48px; margin-top:8px;">😌 ↔ 😋</div>
    <div style="font-size:18px;">Smoothed gradients, hand-drawn icons, tactile touch points.</div>
    <div style="margin-top:20px; font-size:13px; letter-spacing:0.2em;">minimal copy · lush UI widgets · playful motion</div>
  </div>
</div>

---

## Visual Flow (Mood → Meal Suggestions → Pantry Sync → Shopping List)

<div style="background:#0F141F; padding:36px; border-radius:18px; color:#F7EFE3; display:flex; gap:24px; align-items:center; flex-wrap:wrap;">
  <div style="flex:1; min-width:220px; background:#2D4356; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:42px;">🎚️</div>
    <div>Mood Selector</div>
  </div>
  <div style="font-size:48px; color:#8B6F47;">➜</div>
  <div style="flex:1; min-width:220px; background:#1E2634; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:42px;">🍜</div>
    <div>Meal Feed</div>
  </div>
  <div style="font-size:48px; color:#8B6F47;">➜</div>
  <div style="flex:1; min-width:220px; background:#23313E; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:42px;">📦</div>
    <div>Pantry Sync</div>
  </div>
  <div style="font-size:48px; color:#8B6F47;">➜</div>
  <div style="flex:1; min-width:220px; background:#2D4356; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:42px;">🛒</div>
    <div>Smart List</div>
  </div>
</div>

---

## Mood Capture Screen

<div style="background:#E8DCC4; padding:40px; border-radius:18px; display:grid; grid-template-columns:1.3fr 1fr; gap:30px; align-items:center;">
  <div>
<pre style="background:#F9F5EB; color:#2C2A26; padding:30px; border-radius:18px; font-size:15px; line-height:1.4;">
┌────────────────────────────────────────────┐
│ today i'm feeling...                      │
│                                            │
│ 😊 chilled      😰 stressed      🤗 cozy   │
│ ⚡ energetic    😴 drained       😌 calm    │
│                                            │
│ energy        ●───────╴ 72%               │
│ comfort       ─────●──╴ 58%               │
│ adventurous   ─●──────╴ 30%               │
│                                            │
│ [ pulse check ]   [ randomize moods ]      │
└────────────────────────────────────────────┘
</pre>
  </div>
  <div style="color:#3A2E20;">
    <div style="font-size:34px; margin-bottom:12px;">Tap · Slide · React</div>
    <div style="font-size:16px; letter-spacing:0.08em;">Emoji toggles float over cream gradient, sliders glow in Warm Clay, and CTA buttons feel pillowy with soft shadows.</div>
    <div style="margin-top:20px; font-size:12px; text-transform:uppercase; letter-spacing:0.3em; color:#8B6F47;">micro-animations · tactile audio hints · ambient gradients</div>
  </div>
</div>

---

## Meal Suggestion Cards

<div style="background:#111; padding:40px; border-radius:18px; color:#F7EFE3;">
<pre style="background:#1B1B1B; border-radius:18px; padding:30px; font-size:15px; line-height:1.5;">
╔══════════════════════════════════════════════════════════╗
║ cozy comfort picks 🤗                                     ║
╚══════════════════════════════════════════════════════════╝

┌───────────────┐  ┌───────────────┐  ┌───────────────┐
│   [ steam ]   │  │   [ swirl ]   │  │   [ glow  ]   │
│ squash soup   │  │ truffle mac   │  │ miso lentils  │
│ 🕐 25m         │  │ 🕐 30m         │  │ 🕐 35m         │
│ 😌 comfort     │  │ 🤗 cozy        │  │ ⚡ warm boost  │
│ ✓ pantry 4/5   │  │ ✗ need 2       │  │ ✓ pantry full  │
│ [ cook ]       │  │ [ add list ]   │  │ [ cook ]       │
└───────────────┘  └───────────────┘  └───────────────┘
</pre>
  <div style="margin-top:18px; font-size:14px; letter-spacing:0.08em; color:#C3B186; text-align:center;">cards float, hero images bleed edge-to-edge, pantry badges pulse when synced.</div>
</div>

---

## Pantry + Shopping Ecosystem

<div style="display:grid; grid-template-columns:1fr 1fr; gap:30px; margin:40px 0;">
  <div style="background:#8B6F47; padding:32px; border-radius:18px; color:#F7EFE3;">
<pre style="background:#7C613C; padding:26px; border-radius:18px; font-size:15px; line-height:1.4;">
╔ pantry inventory ═══════════════════╗
║ 🔍 garlic, grains, spices...        ║
╟─────────────────────────────────────╢
║ essentials     [ + ]                ║
║  ✓ olive oil     pantry             ║
║  ✓ garlic        fridge             ║
║  ✗ ginger        + add              ║
║ proteins                           ║
║  ✓ eggs          fridge             ║
║  ✗ tofu          auto recommend     ║
║ grains                             ║
║  ✓ basmati       pantry             ║
║  ✗ quinoa        add to list        ║
╚─────────────────────────────────────╝
         [ sync to mood plan ]
</pre>
    <div style="font-size:13px; letter-spacing:0.15em; text-transform:uppercase;">drag items between shelves · little checkmarks bounce when stocked</div>
  </div>
  <div style="background:#2D4356; padding:32px; border-radius:18px; color:#F7EFE3;">
<pre style="background:#23354A; padding:26px; border-radius:18px; font-size:15px; line-height:1.4;">
╔ shopping list · auto grouped ═══════╗
║ produce          meal view ⇵        ║
║  ☐ butternut squash (1)             ║
║  ☐ cherry tomatoes (1 lb)           ║
║ dairy                               ║
║  ☐ heavy cream (1 cup)              ║
║  ☐ parmesan (8 oz)                  ║
║ pantry                              ║
║  ☐ veg broth (1 carton)             ║
║  ☐ coconut milk (1 can)             ║
║ ----------------------------------- ║
║ mac & cheese ▶  ☐ heavy cream       ║
║ squash soup ▶   ☐ thyme bunch       ║
║ lentil curry ▶  ☐ coconut milk      ║
╚═════════════════════════════════════╝
      [ 📱 send ]  [ 🖨 print ]  [ share ]
</pre>
    <div style="font-size:13px; letter-spacing:0.15em; text-transform:uppercase;">toggle between aisle + meal, export to phone with one tap</div>
  </div>
</div>

---

## Story Tiles

<div style="display:grid; grid-template-columns:repeat(3,1fr); gap:20px; margin-bottom:30px;">
  <div style="background:#2D4356; color:#F7EFE3; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:38px;">🎯</div>
    Mood-first logic wires the entire journey.
  </div>
  <div style="background:#8B6F47; color:#F7EFE3; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:38px;">🔄</div>
    Pantry sync avoids waste, props live-scan moments.
  </div>
  <div style="background:#2D4356; color:#F7EFE3; padding:24px; border-radius:18px; text-align:center;">
    <div style="font-size:38px;">🎨</div>
    UI stays tactile, cozy, illustration-forward.
  </div>
</div>

---

<div style="background:#111; color:#E9DBC5; padding:40px; border-radius:18px; text-align:center;">
  <div style="font-size:32px;">Mood → Meal Engine</div>
<pre style="margin-top:20px; background:#181818; padding:24px; border-radius:18px; font-size:15px; line-height:1.6;">
😰 stressed  →  one-pot, minimal prep, grounding aromas
😴 tired     →  slow-cooker, reheatable comfort
😊 happy     →  adventurous color pops + shared plates
🤗 cozy      →  nostalgic soups, oven bakes, warm bowls
⚡ energetic →  vibrant, crunchy, prep-intensive
😌 calm      →  meditative recipes, plating focus
</pre>
  <div style="margin-top:20px; font-size:13px; letter-spacing:0.2em;">behavioural cues · adaptive recipe tags · emotional telemetry</div>
</div>

---


