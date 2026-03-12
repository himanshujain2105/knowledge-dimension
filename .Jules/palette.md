## 2024-05-21 - Accessibility Updates in Blogger Themes
**Learning:** When making accessibility updates to Blogger themes, `ariaLabel` attributes can be passed in the `data` dictionary for `<b:include>` components, and decorative images should receive `alt=''`.
**Action:** Ensure that variables like `data:messages.*` exist before referencing them, and check if images are purely decorative before adding `alt=''`. Use `python3 -c "import xml.etree.ElementTree as ET; ET.parse('theme.xml')"` to quickly validate the XML syntax after changes.
