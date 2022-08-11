# simple-file-logger

An easy approach to file logging!

## Design

I designed this library with ease of use in mind.

## Usage

The time logged is automatically written to a file.

```
'''
// Import the library
const FileLogger = require('file-logger');

// Init the logger
const log = new FileLogger('log.txt');

// Simply use the logger
log.add('Hello world!');
```

## Output Format

Timestamp - Message