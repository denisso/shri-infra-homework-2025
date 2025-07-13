---
title: Release {{ env.tag }}
labels: RELEASE
---
## ℹ️ Release Information

- 📅 Date: {{ date | date('YYYY-MM-DD HH:mm') }}
- 👤 Author: {{ env.actor }}
- 🏷️ Version: {{ env.tag }}
- 🐳 Docker image: `cr.yandex/${{ secrets.YC_ID_CONTAINER }}/app:${{ env.tag }}_latest`

---

## 🔄 Changelog

{{ env.log }}
