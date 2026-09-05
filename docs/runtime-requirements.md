# Runtime Requirements

## Node.js

- Minimum: Node.js 20 (LTS)
- Recommended: Node.js 20+ (LTS)
- Tested: Node.js 20, 22, 24

Uses native global etch (Node.js 20+).

## Browser

- Chrome 67+, Firefox 69+, Safari 14+, Edge 79+
- Browser-specific build via rowser export condition.

## Deno

- Compatible with Deno 1.28+

## Bun

- Compatible with Bun 1.0+

## Polyfills

For environments without etch:

`	ypescript
import { Polyfill } from 'whatwg-fetch';
globalThis.fetch = Polyfill;
