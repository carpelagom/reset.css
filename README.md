# base.css

Reset &amp; basic styles

Credits: https://30-seconds.github.io/30-seconds-of-css/

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
--reset-link-color: #4b00da;
--reset-font-family-sans: "IBM Plex Sans";
--reset-font-family-mono: "IBM Plex Mono";
```

To override a variable in your own stylesheet:

```css
:root {
  ...
  --<variable>: <value>;
  ...
}
```

## html element

Applies `box-sizing: border-box` as default for all elements on the page.

if you want an element to use `box-sizing: content-box` instead, apply the
`.content-box` class.


## styled elements

### body

Sets `font-family` to `--reset-font-family-sans`


### pre, code

Sets `font-family` to `--reset-font-family-mono`

### a

Sets default link color to: `--reset-link-color`.

