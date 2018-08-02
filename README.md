+ `npm run build` works
+ `npm run test` works

The following works,

1. Open `./project-c/src/index.ts`
1. Hover cursor over `b.bar()`
1. The correct type declaration appears in a tooltip

The following does not work,

1. Open `./project-c/src/index.ts`
1. Right-click on `bar`
1. Click "Go to Definition"
1. An error of "No definition found for 'bar'" pops up instead

```
TS 3.0.1

== VS Code ==
Version: 1.25.1
Commit: 1dfc5e557209371715f655691b1235b6b26a06be
Date: 2018-07-11T15:40:20.190Z
Electron: 1.7.12
Chrome: 58.0.3029.110
Node.js: 7.9.0
V8: 5.8.283.38
Architecture: x64
```