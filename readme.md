Use with jQuery

```js
$.get('data/hello.xml', function(xml){
 var json = $.xml2json(xml);
 alert(json.message);
});
```
