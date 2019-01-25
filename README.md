# base.css

Reset &amp; basic styles


## :root variables

Variables defined in `:root`:

```css
--ease-in-quad
--ease-in-cubic
--ease-in-quart
--ease-in-quint
--ease-in-expo
--ease-in-circ
--ease-out-quad
--ease-out-cubic
--ease-out-quart
--ease-out-quint
--ease-out-expo
--ease-out-circ
--ease-in-out-quad
--ease-in-out-cubic
--ease-in-out-quart
--ease-in-out-quint
--ease-in-out-expo
--ease-in-out-circ
```

## html element

Applies `box-sizing: border-box` as default for all elements on the page.

if you want an element to use `box-sizing: content-box` instead, apply the
`.content-box` class.


## styled elements

### body

Applies `font-family: var(--reset-font-family-sans);` ("IBM Plex Sans")


### pre, code

Applies `font-family: var(--reset-font-family-mono);` ("IBM Plex Mono")

### a

Applies a nicer link color instead of the default blue.

To override:

```css
:root {
  ...
  --reset-link-color: <color>;
  ...
}
```
