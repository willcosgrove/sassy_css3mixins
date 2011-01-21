# CSS3 Mixins for Sass

_This is taken from [Jeffrey Way's CSS3 mixins for Less](http://net.tutsplus.com/tutorials/html-css-techniques/quick-tip-never-type-a-vendor-prefix-again/), and converted to Sass._

## Usage
To get access to the css3mixins, at the top of your main sass file, add `@import "css3mixins"`.  After that, you can use any of the mixins by calling `+mixin_name` or the more verbose `@include mixin_name`.

## Mixins
Here are the list of mixins, and their arguments, with default values:

*	`border-radius(radius: 3px)`
*	`outline-radius(radius: 3px)`
*	`box-shadow(x-offset: 2px, y-offset: 2px, blur: 5px, spread: 0, color: rgba(0,0,0,.6))`
*	`transition(what: all, length: 1s, easing: ease-in-out)`
*	`transform(params)`
*	`box(orient: horizontal, pack: center, align: center)`
*	`flex(val: 1)`
*	`resize(direction)`
*	`linear-gradient(begin: black, end: white, switch: 100%)`
*	`double-borders(colorOne: green, colorTwo: red, radius: 0)`
*	`triple-borders(colorOne: green, colorTwo: red, colorThree: blue, radius: 0)`
*	`columns(count: 3, gap: 10)`
*	`box-sizing(type: border-box)`