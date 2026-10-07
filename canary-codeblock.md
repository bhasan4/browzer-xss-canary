# XSS Canary in Code Block

Benign stored-XSS canary for an authorized whitehat security audit of trybrowzer.com.

The canary is inside a fenced code block:

```html
<img src=x onerror=alert(document.domain)>
```
