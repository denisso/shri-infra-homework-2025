---
title: Fix for release {{ env.version }}
labels: FIX
---

## Fix Info

- 📅 Date: {{ date | date('YYYY-MM-DD HH:mm') }}
- 👤 Author: {{ env.actor }}
- 🏷️ Version: {{ env.tag }}
- 🐳 Docker image: `cr.yandex/<registry_id>/app:{{ env.version }}`

## Commits

{{ env.changelog }}
