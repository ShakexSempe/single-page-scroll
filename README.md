# scingle-page-scroll
Vanilla Javascript tutorial project #10 presented by John Smilga

## dynamic footer date
-date.innerHTML = new Date().getFullYear();

## dynamic navbar height on link toggle
-height of links container is initially hardcoded to 200px which is the height of the links in total.
### calculate and toggle height of the links:
-getBoundingClientrect();

-links_container is nb as a parent container with an initial height of 0 to wrap around the links giving a reference to the total height.
links height is used for new toggle value as the links will have the height value required;

## media query problems
-height set to auto on bigger screens;
-toggle implements inline styling which needs to be overridden in the css with !IMPORTANT flag.

## Fixed navbar
-navbar fixed to vp when user scrolls past the height of the navbar by setting up a fixed-nav class.
-scroll event listener.

## smooth scrolling: 
-add elements with .scroll-link to variable and use forEach to prevent the default scroll. (e.preventDefault());
-find specific sections using #id and e.target value  