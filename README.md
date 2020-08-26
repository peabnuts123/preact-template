# Preact Template

Preact project template I use to start all my new projects since I keep doing the same setup over and over. This is the master copy so I can develop changes and improvements in isolation.

TL;DR
  - `preact-cli` 3.0
  - SASS (dart sass)
  - testing-library instead of enzyme
  - prettier removed
  - TypeScript
  - no styled components - regular CSS project
  - eslint set up for 3 different contexts: node.js, react and jest
  - `@app` and `@test` aliases across the codebase for absolute imports
  - A Logger class for nicely formatted logging + configurable log levels
  - `test` directory lifted up out of `src`
  - Some sample jest tests
  - Jest setup scripts to disable logging, ensure that tests don't pass if they assert nothing, and to ensure that tests fail if they make any real network requests
  - Set up for code coverage reporting
