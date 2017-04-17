[![Bower version](https://badge.fury.io/bo/rippler.svg)](http://badge.fury.io/bo/rippler)
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

Rippler
==================
Effect that spreads like a wave in touch or click.  
You can also use the buttons on the bootstrap.  

![demo image](./docs/assets/images/sample.gif)

## Example & Installation
http://blivesta.github.io/rippler

## Sidenote 

Due to click errors on firefox and safari is rippler using 0 for default effectSize!

```
$(document).ready(function() {
  $(".rippler").rippler({
    effectClass      :  'rippler-effect'
    ,effectSize      :  0      // Default size (width & height)
    ,addElement      :  'div'   // e.g. 'svg'(feature)
    ,duration        :  400
  });
});
```

## License
MIT license.
