# HTML & CSS Layout

## Position Property

Sets the position of an element on the screen.

- Properties...
  - relative
    - positioned relative to its normal position on page.
    - Other content will not be adjusted to fit into any gap left by the element.
  - absolute
    - positioned relative to the nearest positioned ancestor
    - If no positioned ancestor, positions relative to body
    - Removed from flow of page, does not affect other elements positioning
  - fixed
    - is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
  - sticky
    - newer
    - behaves like position: relative within its parent, until a given offset threshold is met in the viewport
  - static
    - Default position
    - not considered a positioned element
    - positioned according to normal flow of page

## Display

Used to alter how an element will display on the screen.

- Properties...
  - block
  - inline
  - inline-block
  - flex
  - grid
  - none

## Flexbox

Used to layout elements. Remember, the parent container needs `display: flex;`

- Flex Properties
  - flex-direction
  - flex-wrap
  - justify-content
  - align-items
  - align-content
  - flex (grow, shrink, basis)

* Additional Resources.
  - Flexbox Froggy - https://flexboxfroggy.com/
  - Flexbox Zombie - https://mastery.games/p/flexbox-zombies
  - CSS flexmex - https://cssflexmex.netlify.com/
