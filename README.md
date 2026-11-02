# Video Clip Generator

A collection of video editing projects and source footage for creating YouTube videos. The current project, `course-intro`, is a 98-second introduction to a course on Transformers, built with [HyperFrames](https://hyperframes.dev/).

## Project structure

- `course-intro/` — HyperFrames composition, storyboard, brief, and project assets.
- `sin-editar/` — original, unedited footage (kept locally; not tracked by Git).
- `editado/` — rendered/exported footage (kept locally; not tracked by Git).

## Preview and validate

From the `course-intro` directory:

```sh
npm run dev
npm run check
```

Render the composition with:

```sh
npm run render
```

See `course-intro/BRIEF.md` for the creative brief and `course-intro/STORYBOARD.md` for the scene plan.

## Media files

Large video files are intentionally excluded from version control. Keep source and rendered videos in the local folders above; use a separate storage or delivery service to share them.
