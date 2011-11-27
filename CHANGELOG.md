## Changes

### 1.1.0 - November 27, 2011

* `addRoute()` now returns `routeId` instead of `this` - BREAKING CHANGE
* added `removeRoute(routeId)` 
* updated to `EventEmitter2` current - BREAKING CHANGE

### 1.0.9 - October 25, 2011

* removed regular expression test causing exception in 0.5.10
* ready for node.js v0.6.0, and verified working on windows

### 1.0.8 - October 2, 2011

* added session to request in session plugin
* lower node.js version requirement
* added request plugin
  * POST parameter handling
  * request url parsing