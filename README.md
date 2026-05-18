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

## Additional Features

- **Live Soccer Match Canvas**: Animated 11-player field with ball physics (200ms updates)
- **Mobile-First Design**: Touch-friendly, large tap targets, responsive layout
- **Offline First**: Zero external API dependencies (CDNs only for libraries)
- **Persistent Storage**: localStorage for leaderboard, emotion timeline, momentum tokens
- **Styling**: TailwindCSS for responsive UI, FontAwesome for icons
- **Code Quality**: ~420 lines, well-commented, no external build tools required

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