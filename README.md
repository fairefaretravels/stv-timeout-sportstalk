# 🎙 Mindy's Interview & Show Command Center

A suite of two fully offline, single-file browser apps built for **live show production on one device** — no internet required, no app store, no installs. Open in Safari or Chrome and go.

---

## 📁 What's In This Suite

| File | Show | Purpose |
|------|------|---------|
| `InterviewConductor.html` | Professor Griff Interview | Interview question manager, media cues, live notes, music, tweets |
| `TimeoutSportsTalk.html` | TIMEOUT SPORTS TALK | Sports trivia command center, live scoreboard, music, tweets |

---

## 🎙 InterviewConductor.html
### Professor Griff Interview App

Built for a live sit-down interview. Keeps you organized, on-vibe, and never scrambling mid-conversation.

### Tabs

#### ❓ Questions
- **23 questions** organized across 7 sections: Opening, After Public Enemy, Books & Writing, Creativity & Risk, Community & Mentorship, Technology & AI, and Success & Legacy
- **Filter** by All / Remaining / Asked / ⚡ Wow Moments / 📖 Book Tie-ins
- **Tap** any card to expand it — reveals a follow-up coaching tip (hold silence on Wow questions, listen for names on standard ones)
- **Swipe left** to mark a question as asked · **Swipe right** to undo
- **Checkmark button** on every card as an alternative to swiping
- **⚡ Wow Moment** questions are color-bordered — these are the ones that make him lean forward
- **📖 Book** questions are tagged to naturally link into his published work
- **Bottom bar** always shows the next unasked question with a one-tap jump button

#### 📎 Media
- Store **audio clips and video links** to reference or play during the live interview
- Add a label, URL, and cue note (e.g. *"Play before segment 2"*)
- Tap any link to open it instantly mid-interview

#### 📝 Notes
- **Freeform live notes** area — type reactions, quotes, follow-up ideas as you go
- **Stamp Now** button drops a running timestamp so you can pin golden moments to go back to
- Running tally of questions asked vs remaining
- Full log of every question you've covered

#### 🎵 Music
- **Upload your own MP3/WAV/M4A files** — they play inside the app, no switching apps
- **Paste a direct audio URL** for SoundCloud or hosted files
- **6 preset vibe categories** to organize your playlist: Lo-Fi, Jazz Café, Neo Soul, Afrobeats, Gospel, Ambient
- Full **Play/Pause, Prev/Next, Volume slider, Loop toggle**
- **Mini player bar** floats above every tab — music never stops when you switch screens

#### 𝕏 Tweet
- **6 pre-written fire tweets** ready to fire mid-interview
- Custom tweet composer with character counter (turns red at 260, locks at 280)
- **Open in X** button launches Twitter/X with your text pre-filled — one tap to post
- Session log of every tweet you've sent

---

## 🏆 TimeoutSportsTalk.html
### TIMEOUT SPORTS TALK Trivia Command Center

Built for a high-energy, comedy-meets-heated-debate sports trivia show. 50 questions, live scoring, chaos management.

### Tabs

#### 🎯 Trivia
- **50 questions** across 7 sports categories
- **Filter by sport:** 🏈 NFL · 🏀 NBA · ⚾ MLB · 🏒 NHL · ⚽ Soccer/MLS · 🎓 College · 🥊 Combat Sports
- **Filter by difficulty:** 🟢 Easy · 🟡 Medium · 🔴 Hard
- **3 question formats mixed in:**
  - 🎙 **Open Answer** — host reads, guest answers, tap Reveal to show the answer + bonus fact
  - 📋 **Multiple Choice** — 4 options shown, tap one, app grades it instantly (green = correct, red = wrong)
  - 🔥 **DEBATE** — drops talking points and fuel for the argument, no right answer, pure television
- **Tap** to expand · **Swipe left** = mark asked · **Swipe right** = undo
- Every question includes a 💡 **bonus fact** for extra commentary and dead air killer
- **Bottom bar** shows the next question with a jump button

#### 🏆 Score
- **Live scoreboard** — add as many players or teams as you need
- Tap **+** and **−** to adjust scores in real time
- Auto-ranks with 🥇🥈🥉 medals
- **Per-sport progress bars** so you can see which categories you've hit
- Running total of all points in play

#### 🎵 Music
- Same full player as the Interview app
- Upload files, paste URLs, or pick from preset vibe categories
- Floating mini player bar across all tabs

#### 📝 Notes
- Live freeform notes + **🔥 Hot Moment Stamps** with running timestamps
- Track asked vs remaining at a glance

#### 𝕏 Tweet
- **7 pre-written hype tweets** tuned for the show's energy (trash talk, hype, reactions)
- Custom composer + Open in X one-tap posting
- Session tweet log

---

## 📱 How to Use on One Device

This whole suite is built so **one device runs the show** while the other handles filming or hotspot only.

1. **Download** either `.html` file to your phone
2. **Open** in Safari (iPhone) or Chrome (Android)
3. Everything works **offline** — no wifi needed once the file is open
4. Keep the browser open the whole show — state saves in memory for the session
5. Use your **second device for camera only** 🎬

---

## ⚡ Question Highlights

### Professor Griff — Wow Moments
These are the questions built to make him say *"wow, Mindy asked me THAT?"*
- *"Who was YOUR voice when you were going through it?"*
- *"Is there a moment where you almost quit?"*
- *"What's something you created that the world got completely wrong?"*
- *"Is there something you've never said publicly that you've always wanted to say — and would you say it right now?"*

### TIMEOUT SPORTS TALK — Scorched Earth Debates
Drop these when the energy needs to explode:
- 🔥 LeBron vs Jordan GOAT debate
- 🔥 Is MMA making boxing irrelevant?
- 🔥 Should college athletes be paid beyond NIL?
- 🔥 Is load management ruining the NBA?
- 🔥 Will soccer ever rival the NFL in America?
- 🔥 The ultimate combat sports GOAT closer

---

## 🛠 Technical Notes

- **Single `.html` files** — everything (HTML, CSS, JavaScript, all content) is in one file
- **No frameworks, no build steps, no dependencies** — pure HTML/CSS/JS
- **No internet required** after download
- **Audio playback** uses the browser's native `<audio>` element — supports MP3, WAV, M4A, AAC, OGG
- **State is session-based** — refreshing the page resets progress (by design — each show is a fresh start)
- Tested in **Safari and Chrome** on mobile and desktop
- Twitter/X posting uses the native **Web Intent URL** — opens the X compose window with text pre-filled

---

## 🚀 Future Upgrades (When You're Ready)

- [ ] Direct X/Twitter posting without leaving the app (requires Twitter API connector)
- [ ] Export interview recap to PDF after the show
- [ ] Teleprompter mode for scripted segments
- [ ] Add your own custom trivia questions to the sports app
- [ ] Guest name and show date saved to the file
- [ ] Score history across multiple episodes

---

*Built for Mindy · Powered by Claude · Made to run a whole show from one screen* 🎙🏆
