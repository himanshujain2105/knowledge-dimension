## 2024-05-16 - Blogger Theme Accessibility Findings
**Learning:** Author avatars and comment deletion icons in Blogger themes often lack `alt` attributes, making them confusing for screen readers. Back navigation icons may also miss `aria-label` attributes.
**Action:** Added empty `alt=''` attributes for decorative images and explicit `aria-label` attributes for icon-only links.
