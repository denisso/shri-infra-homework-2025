---
title: Fix for release {{ env.version }}
labels: FIX
---

## Fix Info

- 📅 Date: {{ date | date('YYYY-MM-DD HH:mm') }}
- 👤 Author: {{ env.actor }}
- 🏷️ Version: {{ env.tag }}
- 🐳 Docker image: `cr.yandex/{{ env.container }}/app:{{ env.version }}`

## Commits

{{ env.changelog }}
