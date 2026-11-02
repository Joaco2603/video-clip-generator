---
version: 1
name: Paper notebook — course intro
description: >
  Warm paper, ink, and one burnt-orange mark. Handwritten display for the
  teaching cards. The camera plate stays native 1280×720, centered, never scaled up.
unit: the frame — 1920×1080
principle: one paper sheet threads every card · the face is a plate, not a fill

colors:
  paper: "#FFFCF2"
  ink: "#252422"
  stone: "#403D39"
  muted: "#CCC5B9"
  accent: "#EB5E28"

borders: { wobble: "2px solid ink", hairline: "1px solid ink" }
shadows: { none: "none" }

typography:
  display: { fontFamily: "Marker Felt, Segoe Print, cursive", cqw: 7.2, weight: 400, lineHeight: 1.05 }
  headline: { fontFamily: "Marker Felt, Segoe Print, cursive", cqw: 4.6, weight: 400, lineHeight: 1.1 }
  body: { fontFamily: "Iowan Old Style, Palatino, Georgia, serif", cqw: 2.2, weight: 400, lineHeight: 1.35 }
  kicker: { fontFamily: "IBM Plex Mono, ui-monospace, Menlo, monospace", cqw: 1.3, weight: 500, tracking: "0.14em" }

spacing:
  slide-pad: "4.2cqw"
  gap-md: "1.6cqw"
  radius-sm: "2px"
  camera-w: "66.7cqw"
  camera-h: "37.5cqw"

components:
  paper-stage:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    description: "Every graphic frame is this sheet. No second background."
  camera-plate:
    backgroundColor: "{colors.stone}"
    width: "{spacing.camera-w}"
    height: "{spacing.camera-h}"
    description: "Stand-in for the 1280×720 take. Centered on the paper. Never scaled above native size."
  marker-card:
    backgroundColor: "{colors.paper}"
    border: "{borders.wobble}"
    textColor: "{colors.ink}"
    description: "The checklist. One accent underline on the headline. Rows are the only list."
  node:
    backgroundColor: "{colors.paper}"
    border: "{borders.wobble}"
    textColor: "{colors.ink}"
    description: "A hand-drawn box. Accent is the arrow or the underline, not a fill."
---

## Overview

A slow course intro drawn like a notebook. The orange mark is scarce: one underline, or one arrow, per frame.

## The Frame

Graphic frames fill 1920×1080 with paper. When the speaker returns, the same paper stays and the footage sits in the centered plate.

## Do

- Use the words locked on the storyboard, verbatim.
- Draw boxes and arrows as outlines.
- Keep the camera plate the same size and place every time it returns.

## Don't

- No cyan, glow, gradient text, or neon.
- No upscaled face.
- No invented name.
- No music under the voice.
- No fake code editor.
