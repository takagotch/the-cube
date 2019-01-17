### the-cube
---
https://github.com/pstadler/the-cube

```js
var _config = {
  enableKeys: false,
  transform Property: null,
}
var dummy = document.createElement('div');
$.each('transform MozTransform WebkitTransform OTransform msTransform'.split(' '), function(i, prop){
  if(typeof dummy.style[prop] !== "undefined"){
    _config.transformProperty = prop;
    return false;
  }
});
$(document).ready(function(){
  var rotate = (function(){
    var x = y = 0;
      cube = $('#cube')[0];
    return function(direction){
      switch(direction){
        case '':
          y -= 90;
          break;
        case '':
          y += 90;
          break;
        case 'up':
          x += 90;
          
      }
    }
  });
});
```

```
```

```
```

