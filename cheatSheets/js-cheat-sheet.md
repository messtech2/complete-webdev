# JavaScript Cheat Sheet

## DOM Manipulation
| Method/Property          | Example                                |
|--------------------------|----------------------------------------|
| Select Element           | `document.querySelector("#id");`       |
| Update Content           | `element.innerHTML = "New Text";`      |

## Event Listeners
```javascript
button.addEventListener("click", () => {
  alert("Clicked!");
});
```

## Form Validation

```js
form.addEventListener("submit", (e) => {
  if (input.value === "") e.preventDefault();
});



```
# Local Storage

| Method        | Example                                |
|---------------|----------------------------------------|
| Save Data     | `localStorage.setItem("key", "value");`|
| Retrieve Data | `const data = localStorage.getItem("key");`|
