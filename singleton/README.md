# Hello World

Sample that shows how to use the [windowing API](http://developer.chrome.com/trunk/apps/appWindow.html) in an app to have a "singleton" window app.

The app keeps track of its window in the background page. If none exists, or if it's closed, it creates a new one. Otherwise it re-focuses the existing one via `chrome.app.window.focus()`.

## APIs

* [Windowing](http://developer.chrome.com/trunk/apps/app.window.html)
---
Last updated: 2012-08-14 by miu
