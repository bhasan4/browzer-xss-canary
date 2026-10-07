# XSS Canary Test File

Benign stored-XSS canary for an authorized whitehat security audit of trybrowzer.com.

Canary HTML below:

<img src=x onerror=alert(document.domain)>
