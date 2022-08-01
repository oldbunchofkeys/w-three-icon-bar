# icon bars

## horizontal

use divs

- div for each icon (they're not clickable, just change on hover, so no need to use button for semantic html?)

- `display: flex;` on wrapping div

- `:hover` on each icon
    -  example: 
    `.search:hover {
        background-color: blue;
    }`

## vertical

same as above, but without `display: flex;` on wrapping div

in fact, we probably don't even need a wrapping div. it can just be a series of divs??