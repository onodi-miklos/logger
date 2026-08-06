# @onodi-miklos/logger

Simple logger utility for Express.js. You can log messages to console and/or a file.
ESM!

## Installation

```bash
npm install @onodi-miklos/logger
```
### Usage

import logger from '@onodi-miklos/logger';
app.use(logger([
  // 'console'
  // 'file'
], filePath: string))


// Log to console only
logger(['console'], filePath: string);

// Log to file only
logger(['file'], filePath: string);

// Log to both
logger(['console', 'file'], filePath: string);