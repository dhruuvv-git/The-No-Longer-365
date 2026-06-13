
# The No Longer 365

> *A habit tracking system built like an RPG. Every task you log earns XP across five stats. Your stats level up. Your character grows. Simple on the surface. Deep underneath.*

---

## What Is This?

**The No Longer 365** is a personal growth tracker built with the depth and aesthetic of an RPG — It leans into heavy gamification mechanics, featuring a distinct UI deeply inspired by the high-contrast, stylized aesthetic of **Persona 5**. Available as a **Window**s desktop application and an **Android** app...

Every task you complete earns XP across five character stats. Those stats level up, unlock trophies, and feed into a weekly boss battle you either win or lose. You track your mood, write weekly reflections, manage real-world commitments (Mementos), build meaningful bonds (Confidants), and log your shadow self — the patterns that work against you. Your progress is visualised, archived, and reflected back at you through a cast of mentors who speak in their own voice about your actual week.

It is not a to-do app. It is a system for taking your own life seriously.

---

## Platforms

| Platform | Format |
|---|---|
| **Windows** | Electron desktop application |
| **Android** | Android app (APK) |

---

## Installation

### Windows
1. Download the latest Windows release.
2. Run the installer and follow the setup prompts.
3. Launch **The No Longer 365** from the Start Menu or desktop shortcut.

### Android
1. Download the latest `.apk` release.
2. On your device, enable **Install from Unknown Sources** if prompted (Settings → Security → Unknown Sources).
3. Open the `.apk` file to install.
4. Launch from your home screen or app drawer.

---

## Core Philosophy

| Principle | How It's Applied |
|---|---|
| **Every action is meaningful** | Tasks earn XP in one of five real-life skill areas |
| **Rest is part of the system** | SP, Grace Days, Rest Periods, and Burnout Mode are all designed to reward recovery |
| **Honest self-tracking** | The Shadow Meter, Reflection, and Mood logs are not optional polish — they are the system |
| **Long-term over short-term** | Palace history, Transformation Archive, and the Testament are permanent records |
| **No gamification tricks** | No punishing streaks for genuine rest. No notifications. No artificial urgency |

---

## The Five Stats

All tasks are assigned to one of five core stats modelled on real-world personal development:

| Stat | What It Represents |
|---|---|
| **Knowledge** | Learning, reading, studying, research |
| **Charm** | Social skills, communication, presence |
| **Guts** | Courage, discipline, hard things done anyway |
| **Proficiency** | Technical skill, craft, execution |
| **Discipline** | Routine, consistency, self-control |

Each stat has its own XP bar and level. Trophies unlock at levels 3, 6, 9, 12, and 15.

---

## Features

### Task Logging

Log any action with a name, a stat, and a difficulty rating:

- **Easy** → 1 XP
- **Medium** → 2 XP
- **Hard** → 3 XP

Tasks appear in your history panel. Click any logged task to **tag it** (Flow, Deep Work, Quick Win, Breakthrough, etc.) and add a short note about what shifted. Tagged tasks feed into the Timeline for long-term pattern tracking.

**Habits / Shortcuts** — create recurring tasks and they appear as one-tap quick-log buttons below the form. No retyping.

---

### The Palace — Weekly Boss

Each week a Palace spawns with a boss calibrated to your previous week's XP output. Log tasks throughout the week to deal damage. Clear the boss before Sunday ends and the week is marked **Defeated**. Fail and it closes as **Failed**.

Palace history is permanent and cumulative — it tells the story of every week you fought, won, or lost.

---

### SP — Sanity Points

The SP bar (0–100) tracks your mental energy. It drains when you push hard and recovers when you rest.

| Recovery Action | SP Gain |
|---|---|
| ☕ Coffee | +15 (quick break) |
| 🎮 Games | +30 (proper downtime) |
| 💤 Sleep | Full restore to 100 |

SP can also be set manually each Monday via a prompt — useful for resetting at the start of a new week.

**Security Panel** — SP directly feeds the Security display. Low SP = high security risk. It's a live visual read on how close to the edge you're running.

**SP Burnout** — when SP drops below 20, the entire interface enters Burnout Mode. Every panel flips red, the header flickers, and in Phantom Red theme blood and crack overlays appear on screen. It is intentional. The system is telling you to rest.

---

### Heist Mode

A focused grind state for sprints. Activate Heist to lock in. When you end it, a mandatory **Rest Period** begins automatically, scaled to how long the heist ran. During rest, XP is capped at 15 per task. You cannot start a new heist while resting.

---

### The Soul Overlay

The emotional and reflective core of the system. Open it by clicking the card icon on the quote panel, clicking the Palaces Cleared counter, or selecting it from the side navigator. Inside:

- **Connection** — your assigned mentor for the day speaks in their own personality about your actual week: goal outcome, reflection, upcoming mementos, palace result.
- **Mood Tracker** — log one of 7 moods per day. Click any day to pick. Moods appear as coloured dots on the Calendar.
- **Weekly Goal** — set a single goal for the week. Mark it Done or Failed at the end.
- **Reflection** — write what the week meant. Auto-saves as you type.
- **Transformation Archive** — every past week's goal, reflection, and XP permanently archived. Your history, readable from week one.
- **Bucket List** — life goals outside the daily loop. Tick them off. They stay crossed.
- **Shadow Archive (What's Cooking?)** — a private 280-character scratchpad for whatever you're working through.

---

### The Shadow Meter

Tracks the side of you that works against you. Three sections:

- **Sabotage** — things you did that hurt your own progress. Tick ✓ if you overcame the same pattern later.
- **Avoidance** — things you needed to do but didn't. Honest logging only.
- **Deceit (Mask)** — behaviours or faces you put on to hide. Tick ✓ when you dissolved one.

The navigator comments on your shadow when it gets heavy. It will not lecture you — it will simply observe.

---

### Confidants

Bonds that cost SP to level. Each Confidant is assigned to an arcana that maps to one of the five stats. Up to 15 Confidants total, capped per stat to force balance.

Maxing a Confidant to full rank earns an **arcana trophy** in the Badge panel and triggers a ceremony animation.

---

### Mementos

Commitments with deadlines — not tasks, but promises. Add a name and a due date. When a deadline approaches (within 3 days) your daily mentor mentions it directly in their Connection message. Complete them by ticking the box.

---

### The Testament — One Hundred Deeds 'Ere Death

A permanent list of up to 100 things you want to do, be, or become before you're gone. Not tasks. Not goals with deadlines. Intentions.

Add anything. Tick it off when fulfilled. Each entry you complete counts toward your hundred.

---

### Phantom Record — Activity Heatmap

A 52-week grid showing a full year of XP output at a glance:

- **5 intensity levels** — empty through four shades of green, scaled dynamically against your own personal best
- **Grace days** appear in a distinct colour — intentional rest is not the same as inactivity
- **Heist days** are marked separately — visible sprints in the record
- Hover any cell to see the exact date and XP earned

---

### Charts & Analytics

Switch between **Bar** and **Line** view:

- **Bar** — last 7 days at a glance
- **Line** — trends over Days, Weeks, or Months

Cycle the stat pill to see XP broken down by Knowledge, Charm, Guts, Proficiency, or Discipline individually, or view all five combined.

---

### Weather & Security Panels

Two live-read panels at the top of the task column:

- **Weather** — reflects XP output relative to your own average. Sunny ☀️ means above average. Cloudy ☁️ is steady. Rainy 🌧️ means today's output is below your usual low. New users see Cloudy until 3+ days of data accumulate.
- **Security** — rises as SP drains. A visual warning that you're running on empty. Click to expand the SP-to-security breakdown.

---

### Mentor System

Each day of the week is assigned a mentor character who speaks in the Connection panel of the Soul Overlay.By Default the system has its own mentors with their own personality. Custom mentors can be added with customizable personality from a wide choice of personalities to choose from. The mentor references your actual data: this week's goal, last week's palace result, upcoming mementos, mood pattern.

The schedule is fully customisable — open the Soul Overlay, find the Connection panel, and click **Edit Schedule** to assign any available character to any day.

---

### Approval Rating & The Phan-site Console

A stylised news feed reflecting how the world sees your group:

- **Approval Bar** — rises when you log tasks and level up. Drops when you use Grace Days, take auto-grace penalties, or let the Shadow Meter run heavy.
- **Latest Activity** — the most recently logged task as a live bulletin.
- **Anonymous Comment** — public reaction tone-shifted by rating: hostile below 30%, warming as you climb toward 100%.
- **Group Name** — defaults to *The Phantom Thieves*. Change it in the Soul Overlay settings.

---

### Bulletin Board

Four live stats updated every session:

- **Streak** — consecutive active days
- **Last Week XP** — total XP from the previous week
- **Weakness** — the stat you've invested in least
- **Critical Day** — the weekday where your output historically dips lowest

---

### Star Graph (Persona Spread)

A radar chart showing your spread across all five stats at a glance. Updates live as XP is added.

---

### Calendar

Monthly view with two layers:

- Days with logged mementos show a coloured dot — hover to see the mood label
- Click any day to see every memento due or completed on that date

---

### Trophies & Personal Records

**Trophies** unlock at stat levels 3, 6, 9, 12, and 15. Maxing a Confidant earns an arcana trophy.

**Personal Records** — inside the Trophy Case, the Records tile opens a live dashboard showing every key number in your current run: streak, palaces cleared, total XP, top stat, badges, confidants, goal history, mood days logged, bucket list progress, shadow entries, approval rating, and more. Updates automatically.

---

### Grace Day

One protected skip per week (resets Monday). Activating **REST DAY** preserves your active streak even if you log nothing that day. Cost: –10% Approval Rating and one Grace Day token.

If you miss a day, the app can auto-use your Grace Day overnight and notify you the next time you open it. Once the token is spent, missing a day breaks the streak.

---

### New Year+ (NG+)

When a year ends, New Year+ lets you start fresh without losing everything. Stats and Palaces reset. All other data — task history, trophies, mementos, confidants, reflections — carries forward.

Before the reset, a **Yearly Wrapped Diary** opens: a handwritten-style spread summarising your year — total XP, tasks completed, stat highlights, palace record, mood history, top reflection. The reset cannot be undone.

---

### Thieves Den (Notes)

Freeform sticky-note scratchpad at the bottom of the app. Type anything and hit **STICK IT** — notes appear as slightly tilted stickies. Click X to remove. The Den also houses Save Data and Load Data controls and the Rest Day toggle.

---

### Countdowns & Special Events

- **Countdowns** — set one active deadline (exam, trip, release date) visible on the home bar. Configured in What's Cooking → Countdowns tab.
- **Special Events** — birthdays, holidays, milestones. Your mentor greets these days in their own voice.

---

## Themes

Three visual themes togglable via the switch in the header:

| Theme | Aesthetic |
|---|---|
| **Default** | Neon green on black — cyberpunk terminal |
| **Phantom Red** | Red and black — Persona 5 aesthetic with bold slash geometry |
| **Light** | Warm parchment and brown — analogue, paper, readable in bright light |

All panels, charts, animations, and overlays respond fully to the active theme. Transitions are smoothly crossfaded.

---

## Data & Privacy

All data is stored **locally on your device** — nothing is sent anywhere. No accounts. No internet required after installation. No tracking of any kind.

### Backup & Restore

The Thieves Den panel houses manual save controls:

- **SAVE DATA 📥** — exports your complete state as a dated `.json` file (e.g. `n365_backup_2025-06-01.json`). Includes all tasks, stats, palace history, mementos, soul data, shadow meter state, and your start date.
- **LOAD DATA 📤** — imports a previously saved file and restores your full state. Compatible with all previous save formats — older files are automatically repaired and extended with safe defaults for any newer fields.

> ⚠️ Loading data overwrites your current session. Export first if you want to keep what you have. Your backup file is the only copy outside the app — keep it somewhere safe.

---

## Version

**v1.0.0** — current release.

---

## Credits & Inspiration

Thematically inspired by *Persona 5* (Atlus). No code, assets, or proprietary content from any commercial product is included. All mechanics, writing, and implementation are original.

---

*The Palace is already open. What are you waiting for?*
