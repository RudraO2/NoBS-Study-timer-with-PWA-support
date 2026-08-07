# NoBS Timer

> A no-frills study timer for your phone. One screen, one job: track the hours you actually put in. No account, no ads, no install from a store.

**[▶ Open it](https://rudrao2.github.io/nobs-timer/)** — then add it to your home screen and it runs like a real app.

<!-- DEMO: drop a short screen recording or GIF of the timer running here later. -->

![PWA](https://img.shields.io/badge/PWA-installable-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-single_file-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![offline](https://img.shields.io/badge/works-offline-3FCF8E?style=for-the-badge)

## The idea

Every study-timer app wants an account, a subscription, or a 40MB download to do something a stopwatch does. I wanted the opposite: open a link, start the timer, done. It is one HTML file. It works offline. You never install anything from a store.

## Install it (no store)

1. Open **[rudrao2.github.io/nobs-timer](https://rudrao2.github.io/nobs-timer/)** on your phone.
2. Browser menu, "Add to Home screen".
3. It now opens full-screen like a native app, and keeps working with no signal.

## How it is built

The whole thing is a single `index.html`. The PWA manifest and the service worker are generated at runtime in the page itself, so there are no extra files to host and no build step. The service worker caches the page, which is why it opens offline after the first visit.

## Why

Minimalism as a feature. The less an app asks of you, the more you actually use it.
