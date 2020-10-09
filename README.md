# TN-HW1-Code-Refactor
## Homework Assignment week 1
# TASK
    Refator the codebase that follows accessibility standards 
    SO THAT our own site is optimized for search engines
# LINK
    
# Changes Made
## In HTML:
* Update directory link to CSS with updated name.
* Rename the <Head> title from "website" to "Heriseon Website"
* Change element <div> with class="header" to element <header>
* change <div> in header to <nav> = navigation
* Replace "Div" for Class="content" to "main" to represent for Main contents of website
* Each "div" of paragraph, replace "div" with "section" in contents
* Replace "Div" for Class="benefits" to "aside" to represent for the right side contents
* Each "div" of paragraph, replace "div" with "section" in Benefits
* Add "alt" to img on Benefit section
* Remove </img> on the "Benefit-cost" section.
* add id to search-engine-optimization to active the search when click on the header and it bring to that section.
* rename 3 class in content (main element) to get same class name to be able to combine same code in css
* Change h2 to h4 in footer.

### Example screenshot image of the changes
    Original HTML: ![](TN-HW1-Code-Refactor/Original/assets/images/HTML-Original.png)
    Update HTML: ![](TN-HW1-Code-Refactor/Original/assets/images/CSS-Original.png)

## In CSS:
* Remove the "." in front of header to change it to elements instead of class.
* change all "div" to "nav" that relate to "header"
* Remove unnecessary codes:
    code( header nav ul {
        list-style-type: none;)
* combine float-left and float-right which have the same margin
* combine benefit-lead, -brand and -cost together since they are same mergin and color
* combine benefit-lead, -brand, -cost h3 together
* combine the setting of 3 sections in content
* combine the setting image of 3 sections in content
* combine the h2 setting for sections-content
* Move the content-section up to improve sematic logic.
* add some note comments to each segment of codes
* Change h2 to h4 in footer.

### Example screenshot image of the changes
    Original CSS:
    Update CSS: