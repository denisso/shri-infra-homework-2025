---
title: Fix for release {{ env.version }}
labels: FIX
---

## Fix Info

- Author: @{{ github.actor }}
- Date: {{ date | date('YYYY-MM-DD') }}
- Docker image: `cr.yandex/<registry_id>/app:{{ env.version }}`

## Commits

{{ env.changelog }}
