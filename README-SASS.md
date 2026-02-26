This project uses SCSS for styles.

- Source: `styles.scss`
- Output (compiled): `styles.css` (kept as a backup file)

Quick setup using Dart Sass (recommended):

1. Install `sass` globally (or use the npm script below):

```bash
npm install -g sass
```

2. Compile once:

```bash
sass styles.scss styles.css
```

3. Watch for changes during development:

```bash
sass --watch styles.scss:styles.css
```

Optional npm scripts (create `package.json` and add scripts):

```json
{
  "scripts": {
    "sass": "sass styles.scss styles.css",
    "sass:watch": "sass --watch styles.scss:styles.css"
  }
}
```
