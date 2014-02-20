*This repository is a mirror of the [component](http://component.io) module [component/inserted](http://github.com/component/inserted). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-inserted`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# inserted

  Invoke a callback when a DOM element is inserted.

## Installation

    $ component install component/inserted

## Example

```js
var inserted = require('inserted');
inserted(el, function(){
  console.log('element was inserted!');
});
```

## API

### inserted(el, fn)

  Invokes `fn` when `el` is inserted from the DOM.

### .interval

  The `setInterval` fallback uses `inserted.interval`, defaulting to 200ms.

# License

  MIT
