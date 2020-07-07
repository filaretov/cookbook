---
title: Example presentation
author: John Doe
#documentclass: tuberlinbeamer
bibliography: example.bib
theme: metropolis
cite-method: biblatex
# used with xelatex
#mainfont: Montserrat Regular
#mainfontoptions:
#- BoldFont=Montserrat Medium
#- ItalicFont=Montserrat Italic
#- BoldItalicFont=Montserrat Medium Italic
header-includes: |
  \PassOptionsToPackage{%
  autocite=inline,
  style=authoryear,
  bibstyle=authoryear,
  }{biblatex}
  \setbeamertemplate{bibliography item}{}
...


# This is a slide
- Bullet point [@reference]
- You can also use footnotes [^fn1]

[^fn1]: This is an informative footnote


# Slide with a picture
<!-- Comments -->
![](./images/path.jpg)


# Math

$e = mc^2$

# References #
