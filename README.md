# 

Functional CSS for colors

## Filesize

| File | Size |
|------|------|
| `dist/colors.css` | 3393 bytes |
| `dist/colors.min.css` | 2805 bytes (1241 Gzipped) |

## Install

```sh
npm install 
```

## Usage

### Import

```css
@import "";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com//dist/colors.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to//dist/colors.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|


### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.example-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/colors.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/colors.css` — formatted
- `dist/colors.min.css` — minified

## License

MIT
