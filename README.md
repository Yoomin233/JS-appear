# jQuery.appear
some code that do something when some element appeared in your view port!

please refer to the source code - the main function is just 28 lines of code! 

##usage
###include the jQuery and circleProgress

(the circleProgress plug-in is just for demostration, you can fire other plug-ins whatever you want!)
```html
<script src="js/jquery-1.12.2.min.js"></script>
<script src="js/circle-progress.js"></script>
```

###select the element
inside the code
```javascript
var $ele=$("selector");
```

And you are all done! Insert the code just before the closing `</body>` tag.

When you scroll down the page and the element is visible in the view port(`flag` is true, detect every 300ms), the plug-in(or other functions)  will be fired.

knowing issues: the plug-in seems not working under FF. 
