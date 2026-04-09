# @onodi-miklos/logger

Simple logger utility for Node.js. You can log messages to console and/or a file.

## Installation

```bash
npm install @onodi-miklos/logger

### Usage

const logger = require('@onodi-miklos/logger');

// Log to console only
logger(['console']);

// Log to file only
logger(['file']);

// Log to both
logger(['console', 'file']);