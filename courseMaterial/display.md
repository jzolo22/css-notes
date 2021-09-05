## Display

- `display: none`
  - item is still part of the DOM _but_ its position is not blocked on the page
- `display: hidden`
  - item will not appear but its place will be held on the page
- `display: inline`
  - items will appear in line with other elements
  - takes up only as much width as necessary to fit its content
  - cannot be styled with width/height/margin-top/margin-bottom
  - padding-top/padding-bottom will change distance to border but will not affect neighboring items
- `display: block`
  - starts on a new line and takes up the full width of its parent container
- `display: inline-block`
  - items will behave as inline items (e.g. will not take up the width of the whole parent container, will not start on their own line) but can still be styled with padding, margin, width
  - HTML whitespace (e.g. the new line spacing after an element) is included in the spacing (use one of [these tricks](https://css-tricks.com/fighting-the-space-between-inline-block-elements/) or use another solution like `flexbox`)
