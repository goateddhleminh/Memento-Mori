# ⚡ Memento Mori — Mastery Through Disciplined Focus

A modern, self-contained single-file study tracking and gamified productivity web application. Featuring deep-work focus timers, a comprehensive planner, document & link resources, a dual-section academic and life journal, reward vault, minigames, and cloud synchronization — all contained in a single `index.html` with zero build steps or package dependencies.

---

## 🧭 Navigation & Core Tabs

The dock at the top of the interface provides quick access to 9 dedicated sections:

```
[ Dashboard ]  [ Planner ]  [ Resources ]  [ Journal ]  [ Focus ]  [ Minigames ]  [ Extra ]  [ Stats ]  [ Profile ]
```

1. **Dashboard** — Daily motivation quotes, active companion stage with feeding & buffs, weekly overview chart, and 13-week study activity heatmap.
2. **Planner** — Interactive daily To-Do List and 7-day Weekly Schedule with priority tags and milestone completion rewards.
3. **Resources** — Academic subject folders with link and document management, including a full untruncated subject detail view.
4. **Journal** — Academic Test History (with 0–10 numeric marks measure and mistake reviews) and personal Life reflections.
5. **Focus** — Pomodoro/stopwatch focus timer, daily study targets, fullscreen immersive focus overlay, and live XP/coin/token reward counters.
6. **Minigames** — Consolidated gambling and luck arena featuring the **Dice Arena** and **Lucky Wheel** (with bulk multiplier spins).
7. **Extra** — Consolidated utility and progression hub featuring the **Reward Shop**, **Break Vault**, and **Trophy Cabinet** (70 achievements).
8. **Stats** — Long-term analytics including 14-day study duration bars, subject breakdown distribution, and full session history.
9. **Profile** — Balanced 2-column identity hub featuring avatar customization, cosmetic themes, avatar borders, account sync, and lifetime metrics.

---

## ✨ Feature Deep Dive

### ⏱ Focus Timer & Study Goals
- **Drift-Free Wall-Clock Engine** — Uses timestamp delta calculations to guarantee exact, continuous time tracking even when browser tabs are throttled in the background or mobile screens sleep.
- **Adaptive Timer Modes** — Supports count-up (stopwatch) and countdown (Pomodoro / rest) study sessions with visual circular progress ring.
- **Daily Target Goal** — Set custom daily targets (e.g., 2h 00m) with automatic progress percentage tracking on both the timer and dashboard.
- **Fullscreen Immersive Mode** — Distraction-free full-viewport overlay optimized for low compositor overhead on mobile and desktop.
- **Vietnamese GMT+7 Timeline** — Day roll-overs, streaks, and calendar-based progress consistently compute against the Ho Chi Minh City timezone (GMT+7).

### 🗂 Planner & Milestone Rewards
- **To-Do List** — Create, prioritize (High, Medium, Low), filter, and manage tasks across 5 distinct states: *To Do*, *In Progress*, *Later*, *Blocked*, and *Done*. Includes 1-click **Clear Completed** archiving.
- **Weekly Schedule** — 7-day calendar (Monday through Sunday) with automatic Monday rollover, per-day task checklists, and auto-saving free-text notes.
- **Instant Stacking Rewards**:
  | Action | Study Coins | Spin Tokens | Focus XP |
  | :--- | :---: | :---: | :---: |
  | Complete a To-Do item | +100 🪙 | +1 🎡 | +200 ✦ |
  | Complete a Weekly Schedule item | +150 🪙 | — | +200 ✦ |
  | Finish 100% of a day's tasks | — | +2 🎡 | +500 ✦ |
  | Finish 100% of the entire week | +1,000 🪙 | +5 🎡 | +1,000 ✦ |

### 📁 Study Resources & Cloud Drives
- **Subject Organization** — Create custom academic subjects (e.g., Mathematics, Computer Science, Physics).
- **Cloud Links & Drives** — Attach Google Drive files/folders, Terabox links, Notion pages, and study websites with intelligent cloud provider badges (`📂 Google Drive`, `📦 Terabox`, `📝 Notion`, `📦 Dropbox`, `🔗 Web Link`).
- **Full Subject Detail View** — Click into any subject folder to open an untruncated view displaying complete resource titles, full URLs, 1-click open link `↗`, and copy link `📋` actions.

### 📖 Journal: Test History & Life Notes
The **Journal** tab consolidates academic performance analysis and personal reflection into two clean sub-sections:

#### 1. 📊 Test History
- **Subject Organization** — Group past exams, quizzes, and mock tests by subject.
- **0–10 Mark Measure** — Assign test scores using a dedicated 0.0 to 10.0 numeric measure slider with quick-select pill presets (`5.0`, `7.0`, `8.0`, `9.0`, `10.0`). The test score is displayed prominently next to the title in folder listings.
- **Mistake & Review Tracking** — Record errors, missed steps, and lessons learned for systematic exam reviews.
- **Cloud Exam Link** — Connect test papers, online solutions, Google Drive folders, or Terabox scoring rubrics with quick-open pills.
- **Chronological Sorting** — Tests within each subject are sorted from newest to oldest.

#### 2. 📝 Life & Thoughts
- **Folder Organization** — Categorize entries into custom folders (e.g., *Reflections*, *Mindset*, *Personal*, *Ideas*).
- **External Note Links** — Link external Notion pages, Google Docs, or Terabox documents directly to your reflections.
- **Categorical Tags** — Tag notes with visual markers (🌟 Reflection, 💡 Idea, 🎯 Goal, 🧠 Mindset, 🌿 Personal, ⚡ Productivity).
- **Search & Reader Modal** — Instant keyword search and distraction-free modal reader with direct external link launcher and delete options.

### 🎲 Minigames
Consolidates all chance and token entertainment into one tab:
- **Dice Arena (Gamble)** — Bet Study Coins, Spin Tokens, or Break Minutes on Over (11–17), Under (4–10), Even, Odd, or Any Triple (30x payout). Powered by verifiable client/server seed hashing and nonces.
- **Lucky Wheel (with Bulk Spins)** — 30 weighted segments awarding break time, coins, consumables (soda, snacks), and rare cosmetics.
  - **Bulk Multiplier**: Spin with `1×`, `5×`, `10×`, `25×`, `MAX`, or enter any custom spin quantity. Rewards are multiplied directly by the tokens spent in a single roll.

### 🛍 Extra (Utility & Progression Hub)
Consolidates progression features into three sub-sections:
- **Reward Shop** — Spend earned Study Coins to adopt companions (Fox, Owl, Deer, Wolf, Penguin, Bear, Tiger, Dragon), purchase XP boosters, unlock themes, and acquire avatar borders.
- **Break Vault** — Visual "Break Jar" tracking accumulated rest time earned from study sessions and wheel rewards. Includes quick break timer launcher.
- **Trophy Cabinet (Awards)** — 70 unlockable achievements rewarding bonus coins, tokens, and prestigious titles (e.g., *Centurion*, *Flow Titan*, *Specialist*).

### 👤 Profile & Analytics
- **Balanced 2-Column Layout** — Left sidebar holds Theme Swatches, Avatar Border selector, and Account cloud management; right column displays the "Your Journey" metrics cards and editable biography.
- **Customizable Identity** — Choose from 40+ emoji avatars, custom display names, personal motto quotes, and unlockable titles.
- **Full History & Stats** — 14-day study duration bars, subject time breakdown, and paginated chronological session logs optimized for multi-year usage without DOM lag.

### ⚡ Test Mode (Instant Full Unlock)
For rapid evaluation and UI testing, the website includes a built-in demo environment:
- **Instant Unlocks** — Pre-loads Level 50, 50,000 Study Coins, 50 Spin Tokens, all companions, all themes, all borders, mock test histories, and 14 days of realistic study sessions.
- **Seamless Account Switching** — Prominent "🚪 Switch to Main Account" topbar button and settings control allows toggling back to your personal Supabase account without clearing your local test data.
- **Independent Storage** — Test data is maintained safely in `localStorage` without impacting cloud data.

---

## 🎨 Themes & Design System

- **Dark Minimal (Default)** — Ultra-clean zinc background (`#09090b`), liquid glass containers with subtle inner highlights, and crisp white typography.
- **Minimalist White** — High-contrast light theme engineered for legibility, featuring dark slate headers, slate-600 subtext, and high-visibility dark gradient chart bars.
- **Cyberpunk, Forest, and Arcade** — Alternative accent themes unlocked through progression.

---

## 🛠 Tech Stack

- **Zero Build Tools** — Pure HTML5, CSS3, and modern ES6+ JavaScript in a single self-contained `index.html`.
- **Supabase Cloud Sync** — Optional cloud persistence with multi-device conflict detection, 60s session auto-sync, and automatic token refresh.
- **Canvas API** — Smooth 60 FPS animation for the Lucky Wheel.
- **Web Audio API** — Synthesized audio chimes for session completion and minigame rolls.

---

## 🚀 Getting Started

1. Download or clone this repository.
2. Double-click `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Safari, Zen).
3. Click **⚡ Test Account** to instantly explore all unlocked features, or sign in with your email to start your cloud-synced study journey.

---

## 🗄 Optional Supabase Setup

To sync data across multiple devices, run this SQL in your Supabase SQL Editor:

```sql
create table if not exists studyflow_state (
  user_id uuid references auth.users(id) on delete cascade primary key,
  data jsonb not null default '{}'::jsonb,
  updated_at timestamptz default now()
);

alter table studyflow_state enable row level security;

create policy "Users read own state"
  on studyflow_state for select using (auth.uid() = user_id);
create policy "Users insert own state"
  on studyflow_state for insert with check (auth.uid() = user_id);
create policy "Users update own state"
  on studyflow_state for update using (auth.uid() = user_id);
create policy "Users delete own state"
  on studyflow_state for delete using (auth.uid() = user_id);
```

---

## 📄 License

MIT — free to use, modify, and share.
