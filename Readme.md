*This repository is a mirror of the [component](http://component.io) module [matthewmueller/fullscreen](http://github.com/matthewmueller/fullscreen). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewmueller-fullscreen`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# fullscreen

  Faux fullscreen implementation. Cross-browser compatible, faster and less restrictive than the actual fullscreen API.

## Example

```js
var Fullscreen = require('fullscreen'),
    textarea = document.getElementById('content');

var fullscreen = Fullscreen(textarea);

fullscreen.open();

setTimeout(function() {
  fullscreen.close();
}, 1000);
```

## Installation

    $ component install matthewmueller/fullscreen

## Events

* `open`: emitted when we open the element in fullscreen mode
* `close`: emitted when we close the element's fullscreen mode

## API

### Fullscreen(el)

Initialize fullscreen

### #open()

open fullscreen mode

### #close()

close fullscreen mode

## License

  MIT
