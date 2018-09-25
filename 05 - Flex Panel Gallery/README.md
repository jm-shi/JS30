# Extra Notes

### flex-basis

- Default: auto
- Controls default size of an element, before it's manipulated by other flexbox properties
- Affects element size's across main axis (i.e. horizontal axis)
- Determines width when `flex-direction` is set to row, and height when `flex-direction` is set to column

### flex-grow

- Default: 0 (meaning the flex items can't grow to take up space in the container)
- Determines how much a flex item is allowed to grow
- Applies across main axis, so flex items only grow in width unless `flex-direction` is set to column
- Proportions matter: If all items have `flex-grow` set to 1, then all items grow to fill up equal space in container

### flex-shrink

- Default: 1
- Determines how much a flex item is allowed to shrink
- Proportions also matter

### flex

- Default: 0 1 auto
- Shorthand for `flex-grow`, `flex-shrink`, `flex-basis` combined

[Source](https://medium.freecodecamp.org/even-more-about-how-flexbox-works-explained-in-big-colorful-animated-gifs-a5a74812b053)
