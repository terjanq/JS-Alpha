# JS-Alpha v3.0
Funny project to create an encoder/obfuscator that converts any javascript code into a code that only consists of `/[a-z().]/` characters

The generated code should work on all platforms. It uses only standardized functions.   

Demo: https://terjanq.github.io/JS-Alpha/encoder.html 

```
with(escape())with(eval.bind)eval(unescape(match().concat(strike().big().link().length).concat(escape(escape.name.length).concat(escape(...call.name))).concat(escape(escape(link())).length).concat(link().blink().link().length).concat(link().link().strike().length).concat(name.link().length).concat(big().big().length).concat(link().length).concat(link().length).concat(strike().big().length).concat(fixed().big().length).join(unescape(...escape(this)))))
```

**Notes**
- *The main version `encoder.html` cannot be used in some cases where `with` statement cannot be inserted (e.g. inside `if` closure). In that case the `encoder_old.html` should work but produces much bigger code.*
- *No UTF8 support*


### Credits
The encoder was created as a collaboration of:
- Me (@terjanq)
- Pepe Vila (@cgvwzq)
- Gareth Heyes (@garethheyes)
