## Detail about CSS

1. attribute selector
<a href = "http://www.google.com" />

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



