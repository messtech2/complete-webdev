# CSS Cheat Sheet

## Selectors
| Selector | Example                       |
|----------|-------------------------------|
| Class    | `.class { color: red; }`      |
| ID       | `#id { font-size: 20px; }`    |
| Tag      | `tag { margin: 0; }`          |

## Box Model
| Property         | Example                          |
|------------------|----------------------------------|
| Margin           | `margin: 10px;`                 |
| Padding          | `padding: 15px;`                |
| Border           | `border: 1px solid black;`      |

## Flexbox
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

---
## Grid

```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
}


```
## Media Queries

```css
@media (max-width: 600px) {
  body { background: lightblue; }
}


```