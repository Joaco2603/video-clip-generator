---
workflow: general-video
flow: companion
storyboard: yes
message: "This course takes Transformers apart slowly, from first principles, and you need Python plus basic programming to start."
destination: youtube
aspect: 1920x1080
language: en
audience: "Developers moving into AI, and engineers who want mechanistic clarity"
length: 98s
angle: course-intro
---

## Intent

Edit the recorded course introduction. Keep the speaker's voice for the whole take. Cut the picture away from the camera to hand-drawn teaching cards, then return to camera. Add one requirement the spoken take does not have to say: Python installed, and basic programming (functions, loops, and reading a short script).

Tone from the script: slow, plain, no skipped steps, no black-box math.

## Assets

- ../sin-editar/video1.mov — the same OBS take, renamed (75,500,140 bytes, 98.03s, 1280x720, 30fps, stereo AAC). Picture source and the only audio. Camera stays at native size inside the 1920x1080 frame.

## Customizations

- Cutaways, not cards stuck on the face: full-screen graphics, then back to camera.
- Hand-drawn teaching look. Registry blocks named in the plan: `hw-title`, `hw-pipeline`, `marker-checklist-card`. Catalog had no transformer-specific block; the diagram is authored from `hw-pipeline`.
- No music bed. The voice stays dry. A music bed would need a carve and is out of this cut.
- Hard cuts between camera and cards. Shader wipes are the optional upgrade, not the plan.

## Notes

- HyperFrames usage status was `unknown` (`unsupported_harness`). No allowance was assumed.
- Canvas is 1920x1080 because the destination is YouTube. The face is not scaled up: the 1280x720 plate sits on the paper field.
- Personal name stays off the graphics until a name is given. The script's `[Your Name]` is not invented.
- The Python card is on-screen copy. It does not replace or dub the recorded voice.
- Word-level in/out points are still approximate. They follow the script's beat order across the 98s take, not a transcript.
