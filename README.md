# JS-appear
some code that do something when some element appeared in your view port!

see demo [here](http://yueminhu.github.io/jQuery.appear/index.html)

##usage
just call the `detectVisible` function. it takes three parameters: 

| parameter | type | example | explanation |
|-----------|----------|------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| selector | string | 'div.elem' | use `document.querySelectorAll` internally |
| callback | function | function(){this.classList.add('visible') | callback when the element is appeared in the viewport. 'this' refer to the element.  |
| interval | number | 500 | detection interval for the elem's position. the bigger the better performance, but comes with notable delay.   |

enjoy!
