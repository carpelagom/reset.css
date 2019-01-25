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

## Utility classes


### .unselectable

Apply this class to any element to make it's content unselectable by the user.


### .donut-spinner

Transform element into a donut spinner


### etched-text

Make the text look like it's been etched into the page.

Note: The text color should be dark for the effect to work.


### .object-fit-contain, .object-fit-cover

Apply to an image to make the image be contained to fitted into the element
respectively.


### .flex-centering

Centers the contents of the element using flexbox.


### .hover-underline-animation

Applies an animation of the links underline on hover. Override the color of the
underline with the variable `--reset-link-hover-underline-animation-color`.


### .offscreen

Hides the element offscreen so that screen readers and javascript can still
access it.


### .overflow-scroll-gradient

Applies a gradient when the element overflows to indicate there is more
content.


### .pretty-text-underline

Adds a underline to the text that doesn't clip descenders. (except on selection)


### .reset-all-styles

Resets all styles on the element to their defaults.


### .siblings-fade

Makes a hover'ed elements siblings fade out. Each sibling needs the `.sibling`
class though.


### .switch

Make the element look like a iOS switch.


### .truncate-text

Truncate the text and add ellipsis if the text exceeds one line's width.

Note: the element needs to have a width applied for this to work?


## Credits

Code mostly taken from [30 seconds of
CSS](https://30-seconds.github.io/30-seconds-of-css/), with a few small
modifications.
