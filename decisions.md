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

One color or font choice you made, and why it serves your destination.

* I made the color pallet (royal purple, yellow and white) and font choice (inspired by fonts font on williams college website) to create 
* a consistent easily identifiable webpage that is unique to Williams College and the college town.

One Claude suggestion you rejected, and why.

* Claude had made all of the page titles in the nav bars highlight yellow. I decided to change the "active" class attribute in such a way that only 1 of the 
* page titles will be highlighted at a time, and the title highlighted is dependent on what page the user is on. I felt like this would make it easier for the user to
* immediately know which of the sub pages they were on.

One style that didn't look right at first, and what you changed.

* I noticed that claude did not add the images to the webpage with a consistent sizing. I decided to go through all images on the webpages and manually convert the dimensions 
* so that the images would all be the same size (except for the header image meant to take up as much horizontal space as it needs.). There is likely a better way that involves using flexbox to
* arrange the figure elements and adjust the image proportions.

## Milestone 3: Flexbox Layout
_Add entries after implementing Flexbox._

## Milestone 4: Responsive Design
_Add entries after implementing media queries._

## Stretch Features
_Add entries if you implement any stretch features._