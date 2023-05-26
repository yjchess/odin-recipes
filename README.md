# The Odin Project: Recipes (Project HTML Version)

This is a mockup of a basic Recipes Website using only HTML.
It is a project from "The Odin Project". Specifically: https://www.theodinproject.com/lessons/foundations-recipes 

## Requirements and Constraints
Alongside the TOP requirements, the developer has placed additional constraints on himself:

### **TOP Requirements**:
1. Working index Page with correct boilerplate html :ballot_box_with_check:
2. index page must have: 
    - A header title :ballot_box_with_check:
    - Links to three different recipe pages :ballot_box_with_check:
3. recipe pages must have: 
    - header for recipe :ballot_box_with_check:
    - Image of dish :ballot_box_with_check:
    - Description Header (Must be "Appropriately Sized") :ballot_box_with_check:
    - Descriptiion paragraph :ballot_box_with_check:
    - An unordered ingredients list :ballot_box_with_check:
    - An ordered steps list (@yjchess changed this to an Instructions List) :question:
4. The top down layout of the recipe pages must follow the order of step 3. :ballot_box_with_check:

### Self-Imposed Hard Rules:
1. No css :negative_squared_cross_mark: (Developed at 200% zoom - not noticed until final push. Added zoom property of 200% to html tag)
2. No js :ballot_box_with_check:

### Self-Imposed Soft Rules:
1. Use html attributes as little as possible :question:
2. The third rule does not apply to: svgs, links and images or backgrounds :question:

## Reflection
Unfortunately, did not meet goal of not using css. However, a valuable lesson is learned to always check zoom level when testing.
The site does work without changing the zoom level, however it is ugly and hard to read.

Some key points to consider:
1. Marquee is a deprecated tag. Used due to restrictions of html only. But use js for future projects.
2. The recipes section on the home page changes height when the details are pressed - pushing everything down. 
    - Can be improved by having an invisible inline-block element in the nav with the height of an opened button.
    - This could be done by a transparent img tag of the same height.
    - Alternatively, add a button with content of the same height as the opened details (dual purpose: show content & adjust height).
    - Note that svg does not work without css intervention as it is not an inline-block and so pushes buttons to the bottom.
    - This would take too much time and is not worth implementing as only useful when css not available.
3. Semantic Tags & Accessibility.
    - Used a lot of semantic tags, but should research when to use code vs pre vs samp vs kbd
    - Due to constraints, did not add alts to svg. This is bad for screen readers.
    - Additionally - used buttons for "styling". Not good practice as buttons indicate functionality.
    - Utilized structure Tags, however could have used more section or div tags to organize categories of code.
4. Missing favicon and proper title.

## Todo
Due to the nature of this project, it may not be worth spending too much additional time as the educational value diminishes.
Additionally, due to constraints: A lot of the problems faced / solved will not come up in normal development due to usage of css and js.

Hence only definite future change: 
1. Add a button to link to yjchess's blog discussing this project. (Need to create blog site and post).

Potential changes may include: 
1. Fixing recipe section in index.html to pre-emptively give space for buttons (with details) to expand.
2. Improving semantic tags used. (Also research more SEO techniques).
3. Editing readme to be shorter and more concise or better styled. (need to read up on github markup)