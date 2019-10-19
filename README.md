# useful-script

## JavaScript
1. Get all elements by class name and click to expand
```
var el = document.getElementsByClassName('see_more_link');
for (var i=0;i<el.length; i++) {
    el[i].click();
}
```
2. Autoscroll after certain interval (1.5 sec)
```
var scroll = setInterval(function(){ window.scrollBy(0,1200); }, 1500);
```
To stop
```
clearInterval(scroll);
```
