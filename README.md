# AP-Gym.Vision — AI Personal Trainer

> Real-time pose tracking · Rep counting · Form feedback · Session recording

Built with **MediaPipe** · Runs 100% in the browser · No backend needed · No data leaves your device.

---

## Features
- **Pose Tracking** — MediaPipe Blazepose detects 33 body landmarks in real-time
- **Rep Counter** — Auto-counts reps for Bicep Curl, Squat, and Push-Up
- **Form Feedback** — Live correction cues with voice alerts
- **Form Score** — Percentage ring showing your form quality
- **REC Button** — Records your session with pose overlay + stats bar burned in, saves to Downloads/Gallery
- **Session Log** — Stores your workout history locally

---

## Project Structure

```
apgymvision/
├── index.html                   # Entire app (single file)
├── netlify.toml                 # Netlify deployment config
├── vercel.json                  # Vercel deployment config
├── README.md                    # This file
└── .github/
    └── workflows/
        └── deploy.yml           # GitHub Pages auto-deploy
```

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome 80+ | ✅ Full |
| Edge 80+ | ✅ Full |
| Firefox 90+ | ✅ Full |
| Safari 15+ (iOS) | ✅ Full |
| Samsung Internet | ✅ Full |

---

## Tech Stack

- **MediaPipe Pose** — Body landmark detection (33 points)
- **Canvas API** — Skeleton overlay rendering
- **MediaRecorder API** — Session video recording
- **Web Speech API** — Voice rep counting & form cues
- **Pure HTML/CSS/JS** — Zero frameworks, zero dependencies

---

## License

Built  with ❤️ by Abhay Pandey · AP-Gym.Vision © 2026
