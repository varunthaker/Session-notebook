## Detail about CSS

1. attribute selector
"a href = "http://www.google.com" "

- a[href^="https"] {}: a Tag href starts with https  
- a[href$="com"]: {}: a ends with .com
-  "*" : contains some word

2. Psudo Classes
Target info specific state like a:hover

4. Psudo Element
Targeting specific part of an element a::before { content: "HAHA"}

5. Combinator
- space: (h2 span) : all span in h2
- no-space (h2span): span and h2
- ">" : h2>span : span immediate child
- + : .card+button : button coming directly after an element card


# CSS Flex Box
- display: flex (to the main div/parent)
- flex-direction: row/column -reverse
- gap: 20px (between child)
- justify-content : used for main/first exis (horizontal or Verticle)
  flext-start
  flex-end
  center
  space-between: create space between child and remaining at the start& end
  space-around: create space at the start& end and then between child and remaining
- align-items : same as justify-content but for cross-axis
- flex-wrap: wrap/reverse  for better responsiveness
- align-content: to format/align for overall div/child
- align-self: targeting a specific child in a parent (like image in about section to be in center not all content.
-  flex-flow: flex-direction + flex-wrap :row wrap

  # CSS Grid
  - display Grid
  - gap: 1rem
  - grid-template-column: 300px 300px (twi column nof 300px)
      :repeat(2, 300px) : same as above
      : 1fr 1fr (fraction of parent i.e. 50% 50%)
      : 2fr 1fr (66% 33%)
For Grid item
- grid-column-start: 1 (start from 1st line)
- grid-column-end: 2 (ends on 2nd Ruler)
- grid-column :1/2 (combination of above two command)

  grid-template-areas
   {"1 2 3 " "1 4 5"}
  - https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas
  - first defines which elemts placed where and 
- grid-area: 1 (for element1)
  element 1 will take 1grid and 4th one
