# Payloads

## XSS

### [Ultimate XSS Polyglot](https://github.com/0xsobky/HackVault/wiki/Unleashing-an-Ultimate-XSS-Polyglot)
Nice xss polyglot with examples of context in which it can run

### Tricks:
```javascript
[]['constructor']['constructor']('alert(1)') // all strings can be replaced with OCT notation: "\143\157...." etc.
```

[jsfuck](http://www.jsfuck.com/) Generate arbitrary JS code using only [,] and !
