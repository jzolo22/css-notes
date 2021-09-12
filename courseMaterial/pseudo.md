## Pseudo Classes

- allow us to define a style for a special state of an element
  - e.g. hover or active
  - syntax: `div:hover`
- `:not`
  - `a:not(.active)` --> select any anchor tags without the classname active

## Pseudo Elements

- allow us to define a style on a specific part of an element
  - e.g. first letter
  - syntax: `p::first-line`
  - `::after` & `::before` -> allows us to use `content` CSS property on an element and add some content (e.g. an icon to a link )

### Random note:

- can use comma to separate 2 selectors using the same CSS properties like so:

```css
nav a:hover,
nav a:active {
  color: white;
}
```
