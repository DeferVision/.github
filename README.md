# Defer Vision

> **AI-powered video monitoring. Describe what matters — get alerted when it happens.**

---

## What is Defer Vision?

Defer Vision is an intelligent camera monitoring system that watches your video feeds so you don't have to.

Instead of recording everything and reviewing footage manually, you simply describe the events you care about — in plain language. The system continuously analyzes the video stream and sends an alert the moment something matching your description appears in frame.

**Example triggers:** `sleeping at desk` · `smoking` · `using phone` · `animal appeared` · `person fell`

---

## How it works

```
Camera feed  →  Scene change detection  →  VLM description  →  Relevance check  →  Alert
```

1. **Video capture** — connects to IP cameras or local webcams
2. **Scene change detection** — fast lightweight check before invoking AI (no GPU wasted on static frames)
3. **VLM inference** — vision-language model generates a detailed description of what's happening
4. **Relevance matching** — description is compared against user-defined alert triggers
5. **Alert** — if matched, an alert appears in the feed with a snapshot of the frame

---

## Features

- Natural language triggers — no ML expertise needed
- Multiple cameras per account
- Real-time alerts, no page reload
- Frame snapshot saved for every alert

---

## Status

**MVP in development**

---

## Team

Built by a small team as part of a university project.

---

<p align="center">
  <sub>Defer Vision · MIT License</sub>
</p>
