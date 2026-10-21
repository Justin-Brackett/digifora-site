# digifora-site

Front-end effects for digifora.com, loaded by the Webflow site.

- `fx/loader.js` is the only file the page links to. It is under 1 KB.
- The glass nav button over the hero photo (liquid-glass-react) loads once the page is idle.
- The slow brand gradient behind "One system." (shadergradient on react-three-fiber) loads only when a visitor scrolls near that section.

Nothing here changes how the first screen loads.
