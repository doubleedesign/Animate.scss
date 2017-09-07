# Animate.scss 
*Just-add-water CSS animation by Dan Eden, Sassified.*

`animate.css` is a bunch of cool, fun, and cross-browser animations for you to use in your projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness. This is a basic SASS port so that you can have all animations available in a project, without increasing the size of the final compiled CSS with classes you're not using. 

[Check out all the animations here!](https://daneden.github.io/animate.css/)

## Usage
Because this version uses mixins, not classes, adding classes to your HTML won't work. To add an animation, call the mixin you want on the relevant element in your SCSS. If you want an infinite animation, you must also call the animate-infinite mixin.

Example: 

``` p { 	
	@include bounce;
	@include animate-infinite; 
} ```


## License
Animate.css is licensed under the MIT license. (http://opensource.org/licenses/MIT).