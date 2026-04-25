# index.html — Nav Patch Instructions

## What to do

In your `index.html`, find the `<nav>` / navigation `<ul>` block that currently looks like this:

```html
* [Free assessment](#assessment)
* [Who we serve](#segments)
* [Features](#features)
* [How it works](#how)
* [Budget tool](https://finwell.co.za/budget.html)
* [Try it](#try)
```

Add the **Learn** link as a new `<li>` item, directly before `[Try it](#try)`:

```html
<li><a href="https://finwell.co.za/learn.html" target="_blank">Learn</a></li>
```

So the full nav list becomes:

```html
<li><a href="#assessment">Free assessment</a></li>
<li><a href="#segments">Who we serve</a></li>
<li><a href="#features">Features</a></li>
<li><a href="#how">How it works</a></li>
<li><a href="https://finwell.co.za/budget.html">Budget tool</a></li>
<li><a href="https://finwell.co.za/learn.html" target="_blank">Learn</a></li>
<li><a href="#try">Try it</a></li>
```

## Key points
- `target="_blank"` — opens learn.html in a new tab (same as how you'd want it)
- No password gate — learn.html is fully public, no auth required
- The exact HTML tag names (`<li>`, `<a>`, `<ul>`) may vary depending on your nav markup — match whatever structure your index.html uses
