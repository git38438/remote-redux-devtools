A custom monitor for use with [Redux DevTools](https://github.com/gaearon/redux-devtools).

**In early development stage yet.**

### Installation

```
npm install --save-dev redux-remote-monitor
```

### Usage

You can use `LogMonitor` as the only monitor in your app:

##### `containers/DevTools.js`

```js
import React from 'react';
import { createDevTools } from 'redux-devtools';
import RemoteMonitor from 'redux-remote-monitor';

export default createDevTools(
  <RemoteMonitor />
);
```

### License

MIT
