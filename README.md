# FanDuct – The Sympathetic Nervous System

A complete, standalone HTML/CSS/JS web application that redefines the second-screen sports experience. This is not a prediction game or chat app—it's an emotional + auditory + tactical companion that makes the fan feel inside the game's nervous system.

## Features

### 1. **Emotion Sync Engine** 🫀
- Web Audio API microphone simulator with visual feedback
- Real-time emotion spike tracking (0-100 scale)
- Emotion timeline with historical replay
- Vibration API integration for haptic replay patterns
- Data persists in localStorage

### 2. **Augmented Audio Canvas** 🔊
- 3x3 interactive sound pad matrix (9 different sounds)
- Sounds: BOO, WAVE CLAP, OLE, DRUM, WHISTLE, CHANT1, CHANT2, AIR HORN, SILENCE
- Click to select sound, then tap the live video to trigger
- Sound Tags timeline with timestamps

### 3. **Collective Decision Moments** 🗳️
- Dynamic popup polls every 30 seconds
- Real-time vote tallies (simulated crowd feedback)
- Ghost Arrow overlay showing chosen strategy for 3 seconds
- Multiple decision scenarios (VAR checks, corner strategy, goal line calls)

### 4. **Butterfly Micropredictions** 🦋
- Next-action prediction widget (e.g., "Throw-in direction?")
- Simple binary choice interface
- Points awarded for correct predictions (10 tokens per correct)
- Tokens stored as "Momentum" currency
- Spend momentum to unlock alternate commentary

### 5. **Reality Rewind Collage** 📸
- Capture current frame from live match canvas
- Generate shareable card with screenshot + fake waveform
- Download card as PNG image
- Timestamp included for social sharing

### 6. **Haptic Storyline** 📳
- Three narrative arcs: Tension Build, Climax, Relief
- Arc changes every 30 seconds
- Unique vibration patterns per arc:
  - Tension: 100ms buzz, 200ms gap, 100ms buzz
  - Climax: 500ms long buzz
  - Relief: 150ms, 100ms gap, 150ms
- Toggle haptics on/off

### 7. **Momentum Mirror** 🪞
- Real-time game momentum tracking (simulated ball possession, shots)
- Personal "Fan Momentum" accumulation through tap interactions
- "Flow State" activation when personal momentum matches game momentum
- Screen fireworks and special vibration patterns on sync
- Momentum data tracked in real-time visualization

### 8. **Rival Room** 🗣️
- Choose a rival team to hear anonymized crowd reactions
- Simulated rival fan reactions (boos, chants, crowd sounds)
- "Boo Back" counter-cheer button with haptic feedback
- Creates virtual stadium rivalry experience without chat
- Momentum rewards for successful counter-cheers

### 9. **Instant Ref Cam** 🎥
- Trigger controversial play review with AI slow-mo visualization
- Heatmap-based analysis display (simulated)
- Three voting options: "Clear Foul", "Dive", "Unsure"
- Track referee decision scores and statistics
- Decision history stored for future reference

### 10. **Time-Travel Comments** ⏳
- Record 5-second voice notes during live match
- Timestamp each voice note with match time
- Playback voice notes on demand during session (stored in memory)
- Voice note metadata (timestamps) are saved to localStorage for reference
- Audio data persists only while browser tab is open (lost on page reload/close)

### 11. **Crowd DJ Mode** 🎧
- Apply audio filters to stadium sound: Bass boost, Echo, Remove commentator
- Toggle filters individually to build custom audio experiences
- "Ole Ole" crowd sync button for simulated group cheering
- Track active filters in real-time UI
- Momentum rewards for crowd engagement interactions

### 12. **Post-Match Therapy** 🛋️
- Auto-generate "Fan Wound Report" after match ends
- Simulate heart rate spikes, emotional peaks, tap intensity metrics
- ML-style suggestions: rest recommendations or rewatch suggestions
- Shareable meme format with emotional impact graphs
- Recovery time estimation based on match intensity

## Additional Features

- **Live Soccer Match Canvas**: Animated 11-player field with ball physics (200ms updates)
- **Mobile-First Design**: Touch-friendly, large tap targets, responsive layout
- **Offline First**: Zero external API dependencies (CDNs only for libraries)
- **Persistent Storage**: localStorage for leaderboard, emotion timeline, momentum tokens, voice notes, ref decisions
- **Styling**: TailwindCSS for responsive UI, FontAwesome for icons
- **Code Quality**: ~1000 lines, well-commented, no external build tools required
- **MediaRecorder API**: Native browser voice recording for Time-Travel Comments
- **Haptic Vibration**: Full vibration pattern support across all features

## Complete Feature Summary

| # | Feature | One-Line Magic |
|---|---------|--------|
| 1 | Emotion Sync | Phone remembers your excitement, replays it later with vibrations |
| 2 | Augmented Audio | Paint sound on video – select a sound, tap to trigger |
| 3 | Collective Decisions | Vote together, see ghost arrows, feel crowd consensus |
| 4 | Butterfly Micropredictions | Micro-predictions earn momentum tokens for unlock rewards |
| 5 | Reality Rewind | Auto-capture your reaction during goals as a shareable card |
| 6 | Haptic Storyline | Feel momentum shifts through vibration patterns (Tension → Climax → Relief) |
| 7 | Momentum Mirror | Your momentum syncs with game → fireworks & special haptics |
| 8 | Rival Room | Hear rival fans boo, then hit "Boo Back" for counter-cheer |
| 9 | Instant Ref Cam | Be the VAR judge – decide if it's a foul, dive, or unclear |
| 10 | Time-Travel Comments | Record voice notes now, play them back during current session |
| 11 | Crowd DJ Mode | Toggle audio filters and sync crowd cheers locally |
| 12 | Post-Match Therapy | Get an emotional wound report showing how much the match destroyed you |

## Quick Start

1. Open `index.html` in any modern web browser
2. All features work immediately—no installation or server required
3. Use localStorage (DevTools → Application → Local Storage) to inspect saved data

## Technology Stack

- **HTML5**: Canvas API, Web Audio API, Vibration API
- **CSS**: TailwindCSS, custom animations
- **JavaScript**: Vanilla JS (no frameworks), localStorage API
- **Audio**: Web Audio API for oscillator-based sound generation
- **Styling**: FontAwesome 6.4 icons

## Browser Compatibility

- Chrome/Chromium: Full support
- Firefox: Full support
- Safari: Full support (haptics limited on iOS)
- Edge: Full support

## Use Cases

- Second-screen experience during live sports
- Emotional engagement metrics
- Crowd-sourced tactical insights
- Interactive fan engagement
- Accessible sports commentary alternative