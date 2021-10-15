# Hello world browser extension

Useful browser extension that shows a "Hello world!" once "Ctrl + Shift + F" is pressed.

Browser extension introduction from Google: https://developer.chrome.com/docs/extensions/mv3/overview/

## Branch [manifest-v2](https://github.com/viniciuskneves/hello-world-browser-extension/tree/manifest-v2)

This branch modifies the current implementation so it works on manifest version 2. You can check the diff [here](https://github.com/viniciuskneves/hello-world-browser-extension/compare/manifest-v2).

- `manifest_version` changes from `3` to `2`;
- `action` renamed to `browser_action`;
- `_execute_action` renamed to `_execute_browser_action`.
