# overflow-x-sticky

**NOTE:**

Ideally, browser implementations for `100vw` and `100vh` would account for scrollbars. (Nope.)

Due to the full width element above, `overflow-x` must be set to prevent horizontal scrolling.

Applying `overflow-x: hidden` to either the `html` or `body` tag will hide the browser's scrollbar.

Unless both are set to `hidden`, Safari allows scrolling via touchpad and/or mouse wheel side-to-side tilt.

However, this breaks elements that have `position: sticky` applied.

This page was created to demonstrate that tradeoff.
