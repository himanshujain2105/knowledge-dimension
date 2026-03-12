## 2024-03-12 - Accessibility on anchor-wrapped images
**Learning:** Images wrapped in anchor tags with localized titles (like `expr:title='data:messages.deleteComment'`) can cause redundant or confusing screen reader announcements if they lack an empty `alt` attribute.
**Action:** Always set `alt=''` on decorative images or images inside informative anchors to prevent screen reader noise.
