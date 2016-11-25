# JS-appear
some code that do something when some element appeared in your view port! Function `throttle` and `debounce` tech were used to to achieve better performance. 

see demo [here](http://yueminhu.github.io/JS-appear/index.html)

open the console and see how `callback` were triggered. 

##usage
just call the `detectVisible` function. it takes three parameters: 

| parameter | type | example | explanation |
|-----------|----------|------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| selector | string | 'div.elem' | use `document.querySelectorAll` internally |
| callback | function | function(){this.classList.add('visible') | callback when the element is appeared in the viewport. 'this' refer to the element.  |
| interval | number | 500 | detection interval for the elem's position. the bigger the better performance, but comes with notable delay.   |

enjoy!
