# faeriefloss

A darker variant of [sailorhg](http://twitter.com/sailorhg)'s [fairyfloss](http://sailorhg.github.io/fairyfloss/)
theme ([repo](https://github.com/sailorhg/fairyfloss)), based on [nopjmp](https://github.com/nopjmp)'s [Visual Studio
Code conversion](https://marketplace.visualstudio.com/items?itemName=nopjmp.fairyfloss)
([repo](https://github.com/nopjmp/vscode-fairyfloss)).

## Why?

I love the original fairyfloss theme, but the editor background colour is just a little too bright for my aging
eyeballs to stare at for long periods of time. This variation just shades it a bit towards black a bit.

## Alternatives

If you would like the darker background but prefer to stick with the main theme, you can instead override the
background colour in your per-user `settings.json`:
``` jsonc
{
    // …
    "workbench.colorCustomizations": {
        "[fairyfloss]": {
            "editor.background": "#322A3A"
        }
    },
    // …
}
```

## Screenshot

![screenshot](https://github.com/kbriggs/vscode-faeriefloss/blob/main/assets/faeriefloss.png?raw=true)
