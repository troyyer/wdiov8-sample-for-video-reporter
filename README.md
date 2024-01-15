# wdiov8-sample-for-video-reporter
getting a failure with Wdio v8 and the video reporter
```
C:\code\sample\node_modules\wdiov8-video-reporter>npm run wdio

> sample@1.0.0 wdio
> wdio run ./wdio.conf.js

2024-01-15T02:46:22.993Z ERROR @wdio/config:ConfigParser: Failed loading configuration file: file:///C:/code/sample/node_modules/wdiov8-video-reporter/wdio.conf.js: Cannot find module 'wdio-video-reporter'
Require stack:
- C:\code\sample\node_modules\wdiov8-video-reporter\wdio.conf.js
Error: Cannot find module 'wdio-video-reporter'
Require stack:
- C:\code\sample\node_modules\wdiov8-video-reporter\wdio.conf.js
    at Module._resolveFilename (node:internal/modules/cjs/loader:1048:15)
    at Module._load (node:internal/modules/cjs/loader:901:27)
    at Module.require (node:internal/modules/cjs/loader:1115:19)
    at require (node:internal/modules/helpers:130:18)
    at Object.<anonymous> (C:\code\sample\node_modules\wdiov8-video-reporter\wdio.conf.js:1:15)
    at Module._compile (node:internal/modules/cjs/loader:1241:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1295:10)
    at Module.load (node:internal/modules/cjs/loader:1091:32)
    at Module._load (node:internal/modules/cjs/loader:938:12)
    at cjsLoader (node:internal/modules/esm/translators:284:17)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/translators:234:7)
    at ModuleJob.run (node:internal/modules/esm/module_job:217:25)
    at async ModuleLoader.import (node:internal/modules/esm/loader:316:24)
    at async ConfigParser.addConfigFile (file:///C:/code/sample/node_modules/wdiov8-video-reporter/node_modules/@wdio/config/build/node/ConfigParser.js:86:36)
    at async ConfigParser.initialize (file:///C:/code/sample/node_modules/wdiov8-video-reporter/node_modules/@wdio/config/build/node/ConfigParser.js:48:13)
    at async Launcher.run (file:///C:/code/sample/node_modules/wdiov8-video-reporter/node_modules/@wdio/cli/build/launcher.js:41:9) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    'C:\\code\\sample\\node_modules\\wdiov8-video-reporter\\wdio.conf.js'
  ]
}

C:\code\sample\node_modules\wdiov8-video-reporter>
```
