# typescript-tips-tricks
Tips and tricks about TypeSript


## Understanding target and module in typescript

The module system is independent of the language implementation. ES6 (ES2015) modules use the import/export syntax, and it is up to the module loader to interpret that.

Here you have specified using the ES2015 module system, so that enables the ES6 module syntax.

The Javascript itself may target ES5, and use only ES5 features, but it is theoretically possible to use a module loader with that code that operates with ES2015 module syntax. Although it is possible, it is not necessarily something you would want to do. It is more common to use CommonJS or AMD modules with ES5 Javascript.
