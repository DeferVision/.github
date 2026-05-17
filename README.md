# 👁 Defer Vision

> **AI-powered video monitoring. Describe what matters — get alerted when it happens.**
>
> **Система мониторинга видео на базе ИИ. Опишите что важно — получайте уведомления когда это происходит.**

---

## What is Defer Vision?

Defer Vision is an intelligent camera monitoring system that watches your video feeds so you don't have to.

Instead of recording everything and reviewing footage manually, you simply describe the events you care about — in plain language. The system continuously analyzes the video stream and sends an alert the moment something matching your description appears in frame.

**Example triggers:** `sleeping at desk` · `smoking` · `using phone` · `animal appeared` · `person fell`

---

## Что такое Defer Vision?

Defer Vision — система интеллектуального видеомониторинга, которая анализирует потоки с камер вместо вас.

Вместо того чтобы записывать всё подряд и вручную просматривать видео — просто опишите события, о которых хотите знать. Система непрерывно анализирует видеопоток и отправляет аларм в тот момент, когда описанное событие появляется в кадре.

**Примеры триггеров:** `спит за столом` · `курит` · `использует телефон` · `появилось животное` · `человек упал`

---

## How it works / Как это работает

```
Camera feed  →  Scene change detection  →  VLM description  →  Relevance check  →  Alert
Видеопоток   →  Детекция изменения сцены →  Описание VLM    →  Проверка триггера →  Аларм
```

1. **Video capture** — connects to IP cameras or local webcams
2. **Scene change detection** — fast lightweight check before invoking AI (no GPU wasted on static frames)
3. **VLM inference** — vision-language model generates a detailed description of what's happening
4. **Relevance matching** — description is compared against user-defined alert triggers
5. **Alert** — if matched, an alert appears in the feed with a snapshot of the frame

---

## Features / Возможности

| | EN | RU |
|---|---|---|
| 🎯 | Natural language triggers — no ML expertise needed | Триггеры на естественном языке — без знания ML |
| 📷 | Multiple cameras per account | Несколько камер на один аккаунт |
| ⚡ | Real-time alerts, no page reload | Алармы в реальном времени |
| 🖼 | Frame snapshot saved for every alert | Кадр события сохраняется для каждого аларма |

---

## Status / Статус

🚧 **MVP in development / MVP в разработке**

---

## Team / Команда

Built by a small team as part of a university project.

Проект разрабатывается небольшой командой в рамках учебного проекта.

---

<p align="center">
  <sub>Defer Vision · MIT License</sub>
</p>
