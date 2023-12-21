## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport


## HTML

Lines 4-10 Set up the head section with links to stylesheet and basic setting.

Lines 12-28

Set up navigation bar and banner. Style in CSS

Lines 34-55 About Me Section

Set up about me with picture

Lines 57-105

Set up Work example section. I have one completed project and the rest are placeholders.

Lines 107-122

Contact Info setup


## CSS

Lines 6-13 

Set up webpage variables for colors and background

Lines 33-79

Header stylings

Lines 81-92

set up background picture and style

Line 166-169

Make top tile larger
