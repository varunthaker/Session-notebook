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


#CSS Flex Box
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
