# @onodi-miklos/logger

Simple logger utility for Node.js. You can log messages to console and/or a file.

## Installation

```bash
npm install @onodi-miklos/logger
```
### Usage

const logger = require('@onodi-miklos/logger');
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