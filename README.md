# css-border-radius

Functional CSS for border-radius

## Filesize

| File | Size |
|------|------|
| `dist/border-radius.css` | 3137 bytes |
| `dist/border-radius.min.css` | 2427 bytes (318 Gzipped) |

## Install

```sh
npm install css-border-radius
```

## Usage

### Import

```css
@import "css-border-radius";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-border-radius/dist/border-radius.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-border-radius/dist/border-radius.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.br0` | `border-radius: var(--border-radius-0, 0);` |
| `.br1` | `border-radius: var(--border-radius-1, 4px);` |
| `.br2` | `border-radius: var(--border-radius-2, 6px);` |
| `.br3` | `border-radius: var(--border-radius-3, 8px);` |
| `.br4` | `border-radius: var(--border-radius-4, 12px);` |
| `.br5` | `border-radius: var(--border-radius-5, 16px);` |
| `.br6` | `border-radius: var(--border-radius-6, 20px);` |
| `.br7` | `border-radius: var(--border-radius-7, 24px);` |
| `.br8` | `border-radius: var(--border-radius-8, 32px);` |
| `.br9` | `border-radius: var(--border-radius-9, 48px);` |
| `.br10` | `border-radius: var(--border-radius-10, 64px);` |
| `.br11` | `border-radius: var(--border-radius-11, 9999px);` |
| `.br0-s` | `border-radius: var(--border-radius-0, 0);` |
| `.br1-s` | `border-radius: var(--border-radius-1, 4px);` |
| `.br2-s` | `border-radius: var(--border-radius-2, 6px);` |
| `.br3-s` | `border-radius: var(--border-radius-3, 8px);` |
| `.br4-s` | `border-radius: var(--border-radius-4, 12px);` |
| `.br5-s` | `border-radius: var(--border-radius-5, 16px);` |
| `.br6-s` | `border-radius: var(--border-radius-6, 20px);` |
| `.br7-s` | `border-radius: var(--border-radius-7, 24px);` |
| `.br8-s` | `border-radius: var(--border-radius-8, 32px);` |
| `.br9-s` | `border-radius: var(--border-radius-9, 48px);` |
| `.br10-s` | `border-radius: var(--border-radius-10, 64px);` |
| `.br11-s` | `border-radius: var(--border-radius-11, 9999px);` |
| `.br0-m` | `border-radius: var(--border-radius-0, 0);` |
| `.br1-m` | `border-radius: var(--border-radius-1, 4px);` |
| `.br2-m` | `border-radius: var(--border-radius-2, 6px);` |
| `.br3-m` | `border-radius: var(--border-radius-3, 8px);` |
| `.br4-m` | `border-radius: var(--border-radius-4, 12px);` |
| `.br5-m` | `border-radius: var(--border-radius-5, 16px);` |
| `.br6-m` | `border-radius: var(--border-radius-6, 20px);` |
| `.br7-m` | `border-radius: var(--border-radius-7, 24px);` |
| `.br8-m` | `border-radius: var(--border-radius-8, 32px);` |
| `.br9-m` | `border-radius: var(--border-radius-9, 48px);` |
| `.br10-m` | `border-radius: var(--border-radius-10, 64px);` |
| `.br11-m` | `border-radius: var(--border-radius-11, 9999px);` |
| `.br0-l` | `border-radius: var(--border-radius-0, 0);` |
| `.br1-l` | `border-radius: var(--border-radius-1, 4px);` |
| `.br2-l` | `border-radius: var(--border-radius-2, 6px);` |
| `.br3-l` | `border-radius: var(--border-radius-3, 8px);` |
| `.br4-l` | `border-radius: var(--border-radius-4, 12px);` |
| `.br5-l` | `border-radius: var(--border-radius-5, 16px);` |
| `.br6-l` | `border-radius: var(--border-radius-6, 20px);` |
| `.br7-l` | `border-radius: var(--border-radius-7, 24px);` |
| `.br8-l` | `border-radius: var(--border-radius-8, 32px);` |
| `.br9-l` | `border-radius: var(--border-radius-9, 48px);` |
| `.br10-l` | `border-radius: var(--border-radius-10, 64px);` |
| `.br11-l` | `border-radius: var(--border-radius-11, 9999px);` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.br0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/border-radius.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/border-radius.css` — formatted
- `dist/border-radius.min.css` — minified

## License

MIT
