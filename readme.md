Use with jQuery

1. Load jQuery
2. Load script file
3. input xml url/data
4. ...
5. Profit


```js
$.get('data/hello.xml', function(xml){
 var json = $.xml2json(xml);
 alert(json.message);
});
```
