## Pre-release 1.1.0 (Apr. 29)

- [Directory] override the default session management by using the `directory.setSessionManager` API
- [Services] `applicationWillStop` called before Workers are closed ([SO discussion](http://stackoverflow.com/a/35726567))
- [HTTP Server] add/remove HTTP Request Handlers via the global `httpServer` object using `addRequestHandler` and `removeRequestHandler`
- [Directory] `currentUser` and `currentSession` available from `directory` global object
- Fix: WebSockets high CPU & memory consumption
- Fix: `__STAMP` not updated on `entity.$_entity.serverRefresh()` [#43](https://github.com/Wakanda/wakanda-issues/issues/43)
- Fix: CORS does not work if port 80 is specified in the domain list [#42](https://github.com/Wakanda/wakanda-issues/issues/42)
- Fix: `XMLHttpRequest` uses charset utf-8 when sending Blob
- Fix: Debugger does not break on uncaught exceptions

## 1.0.3 (Feb. 25)

- Fix : `Compute()` API with bool attribute on MySQL Pro Connector

## 1.0.2 (Feb. 19)

- Fix : Windows x64 Installation Controller - Only shortcut is installed [#17](https://github.com/Wakanda/wakanda-issues/issues/17)

## 1.0.1 (Dec. 17)

- Fix : CORS credentials bug [#21](https://github.com/Wakanda/wakanda-issues/issues/21)
- Fix : MySQL Pro Connector REST API crash
