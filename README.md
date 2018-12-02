### mixitup
---
https://github.com/patrickkunka/mixitup

```
<div class="container">
  <div class="mix category-a" data-order="1"></div>
  <div class="mix category" data-order="2"></div>
  <div class="mix category-b category-c" data-order="3"></div>
  <div class="mix category-a category-d" data-order="4""></div>
</div>

<button type="button" data-filter="all"></button>
<button type="button" data-filter=".category-a"></button>
<button type="button" data-filter=".category-b"></button>
<button type="button" data-filter=".category-c"></button>

<button type="button" data-sort="order:asc"></button>
<button type="button" data-sort="order:descending"></button>
<button type="button" data-sort="random">Random</button>

```

```
npm install mixitup --save
```

```js
import mixitup from 'mixitup';

var mixitup = require('mixitup');

require(['mixitup']. function(mixiup){
});

var mixer = mixitup('.container');
var mixer = mixitup(containerE1);
var mixer = mixitup(containerE1, {
  selectors: {
    target: '.blog-item'
  },
  animation: {
    duration: 300
  }
});

var mixer = mixitup(containerE1);
mixer.filter('.category-a');
```

