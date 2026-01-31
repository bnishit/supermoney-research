# Super Money User Research - Interview Player

Interactive audio player with synced, clickable transcripts for user research interviews.

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/bnishit/supermoney-research.git
cd supermoney-research
```

### 2. Add audio files
Place the following audio files in the root folder (same level as `player.html`):

| File | Interviewee | Duration |
|------|-------------|----------|
| `Sidh 1 Blr.m4a` | Sidh (Bangalore) | ~11 min |
| `Sidh 2 Blr.m4a` | Sidh (Bangalore) | ~2.5 min |
| `Nithya gurgaon.m4a` | Nithya (Gurgaon) | ~16 min |

*Contact the repo owner to get the audio files.*

### 3. Run local server
```bash
python3 -m http.server 8080
```

### 4. Open in browser
```
http://localhost:8080/player.html
```

## Features

- **Synced transcripts** - Current segment highlights as audio plays
- **Click to seek** - Click any transcript segment to jump to that point
- **Playback speed** - 0.5x, 0.75x, 1x, 1.25x, 1.5x, 2x
- **Speaker labels** - Interviewer vs interviewee identified
- **Tabbed interface** - Switch between interviews

## Files

```
├── player.html              # Interactive player (open this)
├── transcripts/
│   ├── sidh-1-timestamps.json
│   ├── sidh-2-timestamps.json
│   └── nithya-timestamps.json
├── sidh-interview-transcript.md
├── nithya-interview-transcript.md
├── research-analysis.md
└── supermoney-insights.md
```
