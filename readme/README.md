# horiseonRefactor
Refactor challenge of Horiseon's website for accessibility

Changes made:

index.html


Changed website title from "website" to "Horiseon | Home"

Changed elements with class=hero to class=bannerimage

Changed elements with class=contents to class=services

Added id=search-engine-optimization to line 29 to fix the internal link in line 16

Changed line 76's h2 to an h4 in order to make the heading attributes sequential

Removed unnecessary class elements from lines 29, 36, and 43

Changed elements within the aside to be selected by id instead of class to differentiate the child fields of the section 
from the parent fields

Added appropriate alternate ID's for all included picture links

style.css


Changed many . (class) selectors to # (id) selectors in order to maintain consistency with index.html

Changed .hero to .bannerimage for consistency with index.html

Changed .contents to .services for consistency with index.html

Link to webapp: https://myersdg.github.io/horiseonRefactor