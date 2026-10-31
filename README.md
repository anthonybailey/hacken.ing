# hacken.ing

Redirects https://hacken.ing (and www.hacken.ing) to https://the.hacken.ing, keeping the path.
The real site is in [anthonybailey/the.hacken.ing](https://github.com/anthonybailey/the.hacken.ing).

`index.html` handles `/`; `404.html` catches every other path. Both redirect with JavaScript, falling back to a meta refresh to the home page.
