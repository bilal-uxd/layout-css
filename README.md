# Layout CSS Utilities

A lightweight and customizable utility-first CSS framework for spacing — built with SCSS.  
Use intuitive class names like `lp-l5`, `lm-y2`, `lp-a0` to apply layout padding and margin instantly.

---

## 🚀 Installation

```bash
npm install @muhammedbilal/layout-css
```

---

## 📦 Usage

### In HTML

```html
<link
  rel="stylesheet"
  href="node_modules/@muhammedbilal/layout-css/dist/layout.css"
/>
```

### In SCSS

```scss
@import "@muhammedbilal/layout-css/dist/layout.css";
```

---

## 🧱 Class Naming Convention

Each class follows this pattern:

```
l[p/m]-[a/t/b/l/r/x/y][value]
```

| Prefix | Meaning        |
| ------ | -------------- |
| `lp`   | Layout Padding |
| `lm`   | Layout Margin  |

| Suffix | Applies to     |
| ------ | -------------- |
| `a`    | All sides      |
| `t`    | Top            |
| `b`    | Bottom         |
| `l`    | Left           |
| `r`    | Right          |
| `x`    | Left and Right |
| `y`    | Top and Bottom |

**Examples:**

| Class    | Result                                |
| -------- | ------------------------------------- |
| `.lp-a5` | `padding: 5px`                        |
| `.lp-l2` | `padding-left: 2px`                   |
| `.lm-y4` | `margin-top: 4px; margin-bottom: 4px` |
| `.lm-r0` | `margin-right: 0px`                   |

---

## 🔧 Customization

You can customize the `$space-range` in `scss/_spacing.scss` before building:

```scss
$space-range: 0, 2, 4, 8, 16, 32;
```

Then run:

```bash
npm run build
```

---

## 📁 Output

The built CSS is available at:

```
dist/layout.css
```

You can also generate a minified version if needed.

---

## 📃 License

MIT License — free to use and modify.

---

## 🤝 Contribute

Feel free to open issues, suggest new utilities, or submit pull requests!
