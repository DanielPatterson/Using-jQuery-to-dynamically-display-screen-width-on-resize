# Using-jQuery-to-dynamically-display-screen-width-on-resize

jQuery snippet to display the screen width on browser/device resize.

```js
$(window).resize(function() {
    $("#ratio").html($(window).width());
}).resize();
```

Just add the ratio.js to your page and then the following HTML snippet.

```html
<h1><span id="ratio"></span>px</h1>
```
Dependencies:
- jquery-2.0.2.js
