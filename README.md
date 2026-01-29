# ai-cron-gen

[![npm version](https://img.shields.io/npm/v/ai-cron-gen.svg)](https://www.npmjs.com/package/ai-cron-gen)
[![npm downloads](https://img.shields.io/npm/dm/ai-cron-gen.svg)](https://www.npmjs.com/package/ai-cron-gen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Convert natural language to cron expressions. Never look up cron syntax again.

## Install

```bash
npm install -g ai-cron-gen
```

## Usage

```bash
npx ai-cron-gen "every weekday at 9am"
# → 0 9 * * 1-5

npx ai-cron-gen "first monday of every month at noon"
# → 0 12 1-7 * 1

npx ai-cron-gen "every 15 minutes during business hours"
# → */15 9-17 * * 1-5
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
