**Html Tricks**

[Htmlcheatsheet](https://www.codewithharry.com/blogpost/html-cheatsheet)

[w3Schools](https://www.w3schools.com/)

[Bootstrap](https://getbootstrap.com/)

**Subdomain Finder**

[Nmmapper](https://www.nmmapper.com/sys/tools/subdomainfinder/)

**Disable ways to open Inspect Element in JavaScript and HTML**

I wrote a script that disables practically all the ways to access Inspect Element in JavaScript. Here's what it blocks:

- Right Click
- F12
- Ctrl + Shift + I
- Ctrl + Shift + J
- Ctrl + U
**Right Click**
Copy the HTML below!
```
<body oncontextmenu="return false;">
```

**Keys**

Copy the JavaScript below!
```
document.onkeydown = function(e) {
if(event.keyCode == 123) {
return false;
}
if(e.ctrlKey && e.shiftKey && e.keyCode == 'I'.charCodeAt(0)){
return false;
}
if(e.ctrlKey && e.shiftKey && e.keyCode == 'J'.charCodeAt(0)){
return false;
}
if(e.ctrlKey && e.keyCode == 'U'.charCodeAt(0)){
return false;
}
}
```



