# Daymark — Personalized News Digest Demo

A responsive, dependency-free browser prototype of a personalized daily news digest. Open `index.html` directly in a modern browser.

## What it demonstrates

- Topic selection across six interest areas, persisted in browser local storage.
- A daily briefing view with a featured story and concise summaries.
- Keyword-overlap suppression to reduce repeated topics within one edition.
- Reading list, read-state, story search, and relevance / recency sorting.
- Responsive layout for desktop and mobile.

## Content and production integration

This demo uses clearly labeled, fictional sample stories and local browser logic. It does not fetch current news or call an AI service. To make it production-ready, replace `STORIES` in `app.js` with normalized items from licensed news feeds, add server-side summarization and semantic clustering, and persist user preferences and seen-story fingerprints in an account-backed store. Keep source links and publication timestamps in the normalized story records.
