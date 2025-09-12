# Server Side Template Injection 1

Basically, a template injection is whenever there is no input sanitization in template based languages such as jinja2 and then the user can simply test native syntax until the correct language is found. For example, in jinja2, the syntax for printing a variable is `{{ variable }}`. If the user can input this into a web application and it is rendered, then the user has found a template injection vulnerability.

!(SSTI1_home_screen.png);
