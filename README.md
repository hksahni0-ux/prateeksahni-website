# Prateek Sahni — Portfolio Website

The source behind **[prateeksahni.pages.dev](https://prateeksahni.pages.dev)**: a project-first portfolio across engineering, software & AI, and sales, with an AI assistant that answers visitors' questions from the site's own content, by text or voice.

## What it does

- Interactive three.js hero with objects drawn as neural networks, recoloured for each area of work
- Area switcher (Engineering · Software & AI · Sales) that changes the projects, stats and accent colours
- 22 project case studies with problem, approach, outcome and skills, filterable by skill
- Skills section built automatically from the projects, so every skill links to the work that used it
- AI assistant on a serverless function that streams answers from NVIDIA's Nemotron model, with origin checks and daily usage limits stored against hashed IPs
- Speech-to-text in the chat through the browser's built-in recognition
- Pages prerendered to static HTML for speed and search, then hydrated in the browser
- Strict security headers (CSP with hashed inline scripts, HSTS), no cookies, plain-English privacy notice and terms
- Lighthouse: 100 for SEO, accessibility and best practices

## Stack

React 19 · Vite · Tailwind CSS v4 · three.js / React Three Fiber · Motion · GSAP · Cloudflare Pages, Functions & KV · NVIDIA API · Web3Forms

---

This is a private project. This repository is a public overview only; no source code is published here.
