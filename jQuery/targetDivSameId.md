- Sample snippet for how to color just Div 2 on button click

```html
<div id="a1">Div 1</div>
<div id="a1">Div 2</div>
<div id="a1">Div 3</div>
<button>Click Me!</button>
```

```javascript
$(document).ready(function() {
  $("button").click(function() {
    $("[id=a1]:eq(1)").css("background-color", "red");
  });
});
```
