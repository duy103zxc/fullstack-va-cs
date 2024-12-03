## Lesson 1
### window.addEventListener('keydown', function(e) {})
Scope nhận Input từ bàn phím là `window`

### const key = document.querySelector(`.key[data-key="${e.keyCode}"]`)
Only choose one so it should be querySelector(), querySelectorAll()
To choose all of the elements

## Lesson 3
### Create CSS Variable
-- with name

:root {
    --base: aqua;
    --spacing: 10px;
    --blur: 10px;
}

### this.dataset

### || '' (or nothing, to avoid NaN)

### Array vs NodeList in JS

### document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);

Will update later
## Lesson 4

### Why does an object log `[object Object]` when called with `console.log`?
1. JSON.stringify
const s = 'Hello: ' + JSON.stringify(obj);

2. console.table: In toàn bộ nội dung dưới dạng bảng cho Object Json

### Sử dụng Array.prototype.sort() với một Object, làm cách nào để sort một Object dựa trên một tiêu chí nhất định (Ví dụ như là số năm)?

```javascript
const oldest = inventors.sort(function(a, b) {
    const lastInventor = a.passed - a.year;
    const nextInventor = b.passed - b.year;
    return lastInventor > nextInventor ? -1 : 1;
});

Viết function(a, b) để so sánh giữa hai cái.
```

### How to check if an array contains any values?
if (!obj[name]) {
    obj[name] = 0;
}
obj[name]++;

### How to KeyEventListener "Enter"?

document.querySelector('#txtSearch').addEventListener('keypress', function (e) {
    if (e.key === 'Enter') {
      // code for enter
    }
});
