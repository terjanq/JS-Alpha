# JS-Alpha
Funny project to create an encoder/obfuscator that converts any javascript code into a code that only consist of `/[a-z().]/` characters

Demo1: https://terjanq.github.io/JS-Alpha/encoder.html (full support)  
Demo2: https://terjanq.github.io/JS-Alpha/encoder2.html (no FireFox support, `with` statement used)  


```javascript
eval(unescape(escape().match().concat(escape(escape.name.length).concat(eval.length)).concat(escape(escape.name.length).concat(escape(...eval.call.name))).concat(escape(escape.name.length).concat(escape(false).length)).concat(escape((typeof(true)).length).concat(eval.apply.length)).concat(escape((typeof(true)).length).concat(eval.name.length)).concat(escape(eval.apply.length).concat(unescape.name.length)).concat(escape(escape().sub.name.length).concat(eval.length)).concat(escape(escape().sub.name.length).concat(escape().sub.name.length)).concat(escape(escape().sub.name.length).concat(escape().sub.name.length)).concat(escape(escape().sub.name.length).concat((typeof(true)).length)).concat(escape(eval.apply.length).concat(escape().length)).join(unescape(...escape(this)))))
```

```
with(escape())with(eval)eval(unescape(match().concat(link(unescape).length).concat(escape(escape.name.length).concat(escape(...call.name))).concat(fontsize(escape).length).concat(escape(eval).strike().length).concat(escape(eval).link(true).length).concat(name.link().length).concat(big().big().length).concat(unescape(eval).length).concat(unescape(eval).length).concat(unescape(unescape).length).concat(apply.name.link().length).join(unescape(...escape(this)))))
```

*No UTF8 support*


### Credits
The encoder was created as a collaboration of:
- Me (@terjanq)
- Pepe Vila (@cgvwzq)
- Gareth Heyes (@garethheyes)
