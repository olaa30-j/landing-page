# landing-page
what is this project about?
This project requires you to build a multi-section landing page, with a dynamically updating navigational menu based on the amount of content that is added to the page.
what languages have you used in this project?
by javascript language . to build dynamically navigational menu.
what resources have you used?
MDN website
atom app download on my device
www.w3schools.com website
**DECRIPTION:
1- to build nav
/*Query the all sections and store the list in variable. Document.querySelectorAll('section').after that made loop to build navbar include all the sections.and uses a DocumentFragment.
select all attribute sections by foreach() element :
1-creat list in ul element. Append list to ul element.
2- add attribute for each section. Append link to li element. create class name for each link in lists. set herf for each section at the link
3-How to name each link on the list to the section it's forward to ?
by select all attribute sections. and put text on the list but the text gonna be there the name of attribute const . the last step append text to the attribute.
4-addEventListener (click)... for scroll the each section.to make the scrolling smooth and add prop for it use scrollIntoView element.
5- append the navlist to fragment. reflow and repaint here on ul element too .

2- to active the classes when near top of viewport👍
1-use foreach() element.
2- to position relative to the viewport use getBoundingClientRect() in const
3-use window.innerHeight() element for returns the interior height of the window in pixels, including the height of the horizontal scroll bar.
4- if statement to get the Active like .Make sure to remove Active class from all links before give the active link class active.
5- for change the background of the list. get query selector of ul in const . and change the the background by style.backgroundColor=""; element.

the elements we use for
1- build navbar
Document.querySelectorAll();

Document.getElementById();

forEach();

Document.createDocumentFragment();

Document.createElement();

Document.createTextNode();

appendChild();

getAttribute();

event.preventDefault()

scrollIntoView({'behavior':'smooth'});
2-
Document.querySelectorAll();

forEach();

getBoundingClientRect();

window.innerHeight;

if sstatement;

classList.remove();

classList.add();

getAttribute();

3- to change the background
document.querySelector();

style.backgroundColor="";

