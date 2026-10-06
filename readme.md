Task 4: Make a Website Mobile-Friendly Using CSS Media Queries
Objective
Convert a desktop-only web page into a mobile-friendly, responsive layout using CSS media queries.

Tools Used
HTML5 and CSS3
VS Code
Chrome DevTools (device toolbar)
Project Structure
project-folder/
├── index.html
├── style.css
└── README.md
How to Run
Download or clone the project folder.
Open index.html in Chrome.
Press F12, then Ctrl+Shift+M to open the device toolbar.
Choose a device (e.g., iPhone) or resize the screen below 768px.
Responsive Techniques Used
Viewport meta tag so phones render the page at device width.
Media queries at max-width: 768px (tablet/mobile) and max-width: 480px (small phones).
Fixed width to fluid: the 1100px container becomes width: 100%.
Stacked columns: the flexbox row changes to a column on mobile.
Stacked navigation: menu links display vertically.
Reduced font sizes for headings and hero text on small screens.
Flexible images using max-width: 100%; height: auto;.
box-sizing: border-box to prevent horizontal overflow.
Testing
Tested in Chrome DevTools at desktop width, 768px, and 375px (iPhone). No horizontal scrolling; the layout stacks correctly.

Outcome
Learned media queries, mobile-first design thinking, and flexible layouts.

