# FreeCodeCamp_Responsive_Web_Design_Certification_Project

This Folder Contain all the Certification Project Performed during the COmmpletion of the COurse

###
## Project 1 : Playing_Cards

Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

You should build a webpage that displays at least three playing cards.
You should have a main element with an ID of playing-cards.
Within your #playing-cards element, you should have at least three div elements, each with a class of card.
Within each .card element, you should have three div elements, the first with a class of left, the second with a class of middle, and the third with a class of right.
Your #playing-cards element should use flexbox to horizontally center its children, allow them to wrap, and put a 20px space between them.
Each of your .card elements should use flexbox to justify its children using space-between.
Each of your .left elements should use flexbox item properties to align itself at the start of its' parent container.
Each of your .middle elements should use flexbox item properties to align itself in the center of its' parent container.
Each of your .right elements should use flexbox item properties to align itself at the end of its parent container.
Each of your .middle elements should use flexbox to display its children in a column.
Here are some characters you can copy and paste to use in your cards if you want: ♠, ♣, ♥, and ♦.

###
## Project 2 : Book_Inventory_App

Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

You should have an h1 element with the text Book Inventory.
You should have a table element with columns named Title, Author, Category, Status, and Rate.
Your table should have at least four rows, the first for the column headings and the rest filled with book information.
Each table row inside the table body should have either the class read, to-read, or in-progress.
td elements of the Status column should contain a span element with the class of status surrounding the text Read, To Read, or In Progress, depending on the class of that row.
td elements of the Rate column should contain a span element with the class of rate wrapping three empty span elements.
.rate elements placed inside .read rows should have an additional class with the value of either one, two, or three, depending on the personal rate. This value should come after rate.
You should create three attribute selectors to target the elements with the class of read, to-read, and in-progress, and set their background-image property to use a linear-gradient of your choice.
You should set the display property of each span element to inline-block.
You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read and set their border and background-image properties.
You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read and set their border and background-image properties.
You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress and set their border and background-image properties.
You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their height, width, and padding properties.
You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their border, border-radius, margin, height, width, and background-color properties.
You should use an attribute selector to target the first descendant of span elements that have the word one as a part of their class value and set its background-image property to use a linear-gradient.
You should use an attribute selector to target the first two descendants of span elements that have the word two as a part of their class value and set their background-image property to use a linear-gradient.
You should use an attribute selector to target the three span elements that are descendants of span elements that have the word three as a part of their class value and set their background-image property to use a linear-gradient.
Run the Tests (Ctrl + Enter)

###
## Project_3 : Technical_Documentation_Page

Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

You can see a main element with a corresponding id="main-doc", which contains the page's main content (technical documentation).
Within the #main-doc element, you can see several section elements, each with a class of main-section. There should be a minimum of five.
The first element within each .main-section should be a header element, which contains text that describes the topic of that section.
Each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding id="JavaScript_and_Java").
The .main-section elements should contain at least ten p elements total (not each).
The .main-section elements should contain at least five code elements total (not each).
The .main-section elements should contain at least five li items total (not each).
You can see a nav element with a corresponding id="navbar".
The navbar element should contain one header element which contains text that describes the topic of the technical documentation.
Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section.
The header element in the #navbar must come before any link (a) elements in the navbar.
Each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
When you click on a navbar element, the page should navigate to the corresponding section of the #main-doc element (e.g. If you click on a .nav-link element that contains the text "Hello world", the page navigates to a section element with that id, and contains the corresponding header).
On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user.
Your technical documentation should use at least one media query.
Note: Be sure to link your stylesheet in your HTML and apply your CSS.

###
## Project_4 : Product_Landing_Page

Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

Your product landing page should have a header element with a corresponding id="header".
You should have an image within the header element with a corresponding id="header-img" (A logo would make a good image here).
Within the #header element, you should have a nav element with a corresponding id="nav-bar".
You should have at least three clickable elements inside the nav element, each with the class nav-link.
When you click a .nav-link button in the nav element, you should be taken to the corresponding section of the landing page.
You should have an embedded product video with id="video".
Your landing page should have a form element with a corresponding id="form".
Within the form, there should be an input field with id="email" where you can enter an email address.
The #email input field should have placeholder text to let users know what the field is for.
The #email input field should use HTML5 validation to confirm that the entered text is an email address.
Within the form, there should be a submit input with a corresponding id="submit".
When you click the #submit element, the email should be submitted to a static page (use this mock URL: https://www.freecodecamp.org/email-submit).
The navbar should always be at the top of the viewport.
Your product landing page should have at least one media query.
Your product landing page should utilize CSS flexbox at least once.
Note: Be sure to link your stylesheet in your HTML and apply your CSS.

