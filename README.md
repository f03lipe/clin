# cli

This undocumented script allows for a cli-like interface using HTML5.

## Basic usage

html:
```html
<div class="cli-wrapper">
  <h1 class="b-cursor" data-char-delay="200">This website looks so clin!</h1>
</div>
```

and the javascript:
```js
$(document).ready(function(){
  $(".cli-wrapper").cli();
});
```

Oh, don't forget to add the CSS file, in order to get the blinking cursor functionality.

## TODOs:
- Create stylesheet with terminal styles.
