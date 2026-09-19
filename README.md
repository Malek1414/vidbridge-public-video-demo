# vidbridge — public video demo

**vidbridge** is a video-editing pipeline. Claude Code plans and cuts the footage,
Codex CLI renders the effects, and a small Python CLI is the deterministic plumbing
between them. Every deliverable is checked with ffprobe and inspected frame by frame
before it is called done.

This repository holds the demo videos only. The pipeline source is private.

**▶ [Watch both videos in the browser](https://malek1414.github.io/vidbridge-public-video-demo/)**

## How it works, in 48 seconds

[![How vidbridge works: one real run, from a camera roll at IFA Berlin to a 30-second reel](./vidbridge-how-it-works.gif)](./vidbridge-how-it-works.mov)

One real job, start to finish. Fifteen originals from a phone's camera roll at
IFA Berlin 2026 become a 30-second vertical reel of exactly 900 frames. Every number
on screen comes from that run: the twenty prepared clips and the six that perception
dropped for having no subject, the approved `edit_plan.json` drawn as a timeline, the
compile and render transcript, and the QC checklist the finished file was measured against.

| | |
|---|---|
| Full resolution | [`vidbridge-how-it-works.mov`](./vidbridge-how-it-works.mov) · 1920×1080 · 5 MB |
| Web encode | [`vidbridge-how-it-works-web.mp4`](./vidbridge-how-it-works-web.mp4) · 1280×720 · 2 MB |

## The reel it produced

The 30-second vertical output from that same job: cut, graded through a parametric LUT,
and captioned in Montserrat ExtraBold inside the safe area.

| | |
|---|---|
| Web encode | [`vidbridge-demo-ifa-30s-web.mp4`](./vidbridge-demo-ifa-30s-web.mp4) · 1080×1920 · 8 MB |
| Full quality | [download from the release](https://github.com/Malek1414/vidbridge-public-video-demo/releases/tag/demo-v1) · 32 MB · 8.6 Mbps |

## Author

Malek Hassan — [malek1414.github.io](https://malek1414.github.io) · [github.com/Malek1414](https://github.com/Malek1414)
