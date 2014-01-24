# clin

Create cli-like animations using HTML5.

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


## Customize animations

Use elements datasets to customize animations.

- `data-char-delay`: delay between output of individual characters (in milliseconds)
- `data-cli="fade"`: simply fadeIn element, don't use clin

## TODOs:
- Create stylesheet with terminal styles.
- Implement hierarchical dataset binding.

### License
MIT
