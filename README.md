# YTFactory — AI YouTube Shorts Automation

**Portfolio showcase · selected real source code**

A Python + TypeScript/React video automation project for producing YouTube Shorts from a topic: script generation, TTS voiceover, scene assembly, animated captions, rendering, quality checks, and YouTube publishing.

## Pipeline
Topic → LLM script → voiceover → storyboard → Remotion video → validation → YouTube upload.

## Technical work
- Python orchestration and configurable quality presets
- Remotion-based video rendering and animated captions
- TTS word timestamps and synchronization checks
- YouTube Data API integration and publishing workflow
- Automated checks, retry/error handling, and test suite

## Code sample
[Quality presets — actual project code](examples/quality_presets.py). This module controls FPS, encoder CRF, render concurrency and audio bitrate.

## Technologies
Python, TypeScript, React, Remotion, FFmpeg, TTS, LLM APIs, YouTube Data API.

## Scope
This is a **portfolio excerpt**, not a runnable full application. Production configuration, account credentials, and the full private repository are intentionally excluded. No public demo URL is claimed here.

## Notes
The original private project has evolved through multiple iterations. This showcase describes the project and shares a small, representative source module without exposing private configuration.
