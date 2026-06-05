# Globetrotter — Decisions Log

## Milestone 0: Setup and Planning
- Destination chosen: Williams College

- Primary audience: Other College Students who have not heard about Williams College

- One design decision that reflects the destination: Implement the College's color scheme

- Wireframe format used (hand-drawn / Figma / other):

hand-drawn

## Milestone 1: HTML Structure
_Add entries after building each page._


One HTML structure choice you made and why (e.g., why you used <article> instead of <div> for gallery items).

* Used a <nav> element with the same link structure across all HTML files and made the navigation bar a list of links.
* Wanted a consistent way to organize the links across all HTML files so that adding CSS styling to the navigation bar would be easier.

One thing Claude generated that you changed, and why.

* For the <section> element containing the attractions-grid class, originally the separate attractions just used <div> elements and did not have an attraction class.
* To make it easier to group similar behavior for the attraction cards, I used <article> elements instead for each attraction and added an attraction class.
* If I want to apply the same styling to the <article> elements, I can do so by using the attraction class that I added to each of the <article> elements nested in the <section> element in question.
 
One place where your wireframe guided a specific decision about structure.

* In terms of knowing what larger parent HTML elements should be present, I used the wireframes to help me structure them.
* I looked at the wireframe I made for each page and determined which child content would go into each parent element.
* Understanding the parent-child relationships from the wireframes will help me when I start applying CSS styling.

## Milestone 2: CSS Styling
_Add entries after applying styles._

## Milestone 3: Flexbox Layout
_Add entries after implementing Flexbox._

## Milestone 4: Responsive Design
_Add entries after implementing media queries._

## Stretch Features
_Add entries if you implement any stretch features._