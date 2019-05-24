# JS-Alpha
Funny project to create an encoder/obfuscator that converts any javascript code into a code that only consist of `/[a-z().]/` characters

Demo: https://terjanq.github.io/JS-Alpha/encoder.html

```javascript
eval(unescape(escape().match().concat(escape(escape.name.length).concat(eval.length)).concat(escape(escape.name.length).concat(escape(...eval.call.name))).concat(escape(escape.name.length).concat(escape(false).length)).concat(escape((typeof(true)).length).concat(eval.apply.length)).concat(escape((typeof(true)).length).concat(eval.name.length)).concat(escape(eval.apply.length).concat(unescape.name.length)).concat(escape(escape().sub.name.length).concat(eval.length)).concat(escape(escape().sub.name.length).concat(escape().sub.name.length)).concat(escape(escape().sub.name.length).concat(escape().sub.name.length)).concat(escape(escape().sub.name.length).concat((typeof(true)).length)).concat(escape(eval.apply.length).concat(escape().length)).join(unescape(...escape(this)))))
```

*No UTF8 support*


### Credits
The encoder was created as a collaboration of:
- Me (@terjanq)
- Pepe Vila (@cgvwzq)
- Gareth Heyes (@garethheyes)
