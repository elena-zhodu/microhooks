# microhooks

A handful of React hooks I keep copy-pasting between projects

Small but I use it weekly.

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## What it does

- useDebounce with leading/trailing options
- Tiny: no dependencies besides React
- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization

## Install

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## License

MIT - see [LICENSE](LICENSE).
