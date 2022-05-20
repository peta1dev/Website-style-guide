# Website-style-guide
A repository for my Codecademy Build A Website Style Guide project in Module 7 of the Full Stack Dev course. 

The aim of this project was to build a basic design system for a website including sections for:

- colors to be used on the site
- fonts to be used
- font style specifications for different textual elements of the site

The project challenge spec did not require colors and fonts to be set via UI - instead they are coded into the HTML/CSS.

In the initial build, I added a section at the end to demonstrate how a section of the site might look in the fonts and colors chosen, and navigation buttons at the top to jump to different sections.

The color cards have been set up in CSS so that colors can be chosen by changing a group of 3 variables that control:

-the hex code for the color, 
-the displayed hex code 
-and the displayed color name. 

In a later build (when I have done Javascript modules - only CSS and HTML have been covered at this point) this setup should facilitate allowing the user to select colors from a color-picker on the site.

In the first build I have not yet made the page fully accessibity-compliant, checked cross- and legacy browser compatibility issues or implemented on-page UI-controlled color and font selections, so that I can move on to the next module. I will make these checks and add features after covering Javascript.

Personal challenges that arose in this project included:

*     making the nav bar static
*     how to jump to a page anchor and have it display below the nav bar instead of behind it
*     creating visual indicators and interaction for "flat design" buttons for the nav bar
*     using flex and grid layouts to solve different layout issues
*     wrapping my head around inline, block and position rules
*     working out how to make text automatically change to a contrasting color on a background that can change to any color (used mix-blend-mode property although result is not always accessibility compliant)

To do:

*     rename classes and variables to be more concise, consistent and appropriate to their use
*     accessiblity compliance
*     add ability to change colors and fonts through UI
*     check browser compatibility
*     implement a responsive design
*     implement a better solution for not allowing the test-diary class block overflow the div with class font-color-test-page bounds
