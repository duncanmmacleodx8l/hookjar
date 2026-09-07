# hookjar

Small typed hooks: debounce, localStorage, media query, toggle

Side project, maintained when I have time.

## Install

```bash
npm install
npm test
```

## What it does

- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- Tiny: no dependencies besides React

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
```

## License

MIT - see [LICENSE](LICENSE).
