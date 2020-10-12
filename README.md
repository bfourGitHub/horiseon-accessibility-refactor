# Horiseon Accessibility Refactor

## The purpose of this project is to incorporate semantic html elements to make an existing website more accessible and easier to navigate with accessibility aides.


### What are semantic elements and why are they important?
A semantic element clearly describes its meaning to both the browser and the developer. 

Examples of non-semantic elements: *div* and *span*

Examples of semantic elements: *form*, *aside*, and *article*

Not only does this type of html organization allow for code to be easily followed by developers, it also allows users to more easily utilize assistive technologies.


### How was this implemented in this application?
The existing application functioned as it should but some html and css could be streamlined.

Html: DIV's and other non-descriptive elements are replaced with semantic elements like NAV, ARTICLE, and ASIDE. Redundant class selectors were also removed.

CSS: Elements and selectors in css are updated to reflect semantic html elements. Class selectors in html that were removed allowed for a simplified css style sheet. Rather than using multiple class selectors to target similar elements, a single css selector was utilized.


### How are these changes reflected in the application?
Visually, the new application will appear identical to the existing application.
However, this application will now function more responsively when used with assistive technologies. For instance, images that are displayed have alternative attributes that give a description of the image to a user who may be impaired.

