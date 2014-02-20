*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/classes](http://github.com/ianstormtaylor/classes). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-classes`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# classes

  Quickly mixin class helper methods to a view.

## Installation

    $ component install ianstormtaylor/classes

## Example

```js
var Classes = require('classes');

/**
 * Mixin classes.
 */

Classes(View.prototype);

View.prototype.addClass    // fn(name)
View.prototype.removeClass // fn(name)
View.prototype.hasClass    // fn(name)
View.prototype.toggleClass // fn(name)
```

Depends on the view's `.el` property being a DOM element reference.

## API

### Classes(obj)
  Mix the classes methods into a given `obj`.

### #addClass(name)
  Adds a class `name` to `this.el`.

### #removeClass(name)
  Removes a class `name` from `this.el`.

### #hasClass(name)
  Checks whether `this.el` has a class `name`.

### #toggleClass(name)
  Toggles a class `name` on `this.el`.

## License

  MIT
