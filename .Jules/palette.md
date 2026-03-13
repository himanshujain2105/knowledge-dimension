## 2024-05-14 - Redundant Alt Text

**Learning:** When images are purely decorative (like `author-avatar` or `author-image`) or when they are wrapped in an anchor tag that already provides a title (like `comment-delete`), setting `alt=''` on the `<img>` tag is crucial. It prevents screen readers from making redundant, confusing, or noisy announcements, which improves the overall accessibility experience.
**Action:** Always add `alt=''` to decorative images and images wrapped in tags with a title attribute.