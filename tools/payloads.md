# Payloads

## XSS

### [Ultimate XSS Polyglot](https://github.com/0xsobky/HackVault/wiki/Unleashing-an-Ultimate-XSS-Polyglot)
Nice xss polyglot with examples of context in which it can run

### Tricks:
```javascript
[]['constructor']['constructor']('alert(1)') // all strings can be replaced with OCT notation: "\143\157...." etc.
```

### using [html entities](https://www.w3schools.com/html/html_entities.asp)
to bypass sanitization

### [jsfuck](http://www.jsfuck.com/)
Generate arbitrary JS code using only [,] and !

### [codepoints](https://codepoints.net/)
Find a lot of info about specific unicode symbols, to craft nice payloads (f.e. `.toLowerCase()` on non-ascii symbols that gives ascii symbols)

### [script gadgets](https://github.com/google/security-research-pocs/tree/master/script-gadgets)
Don’t trust the DOM: Bypassing XSS mitigations via Script gadgets.
