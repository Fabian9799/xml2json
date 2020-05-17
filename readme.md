Use with jQuery

1. Load jQuery
2. Load script file
3. input xml url/data
4. ...
5. Profit

Useful Links:
Rss to Json: https://codebeautify.org/xmltojson

Json path finder: https://jsonpathfinder.com/
(if the path starts with x.rss.something remove the rss part)



```js
$.get('data/hello.xml', function(xml){
 var json = $.xml2json(xml);
 alert(json.message);
});
```
