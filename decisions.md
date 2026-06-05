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

One Flexbox property choice you made deliberately, and why.

* For webpages with gallery cards (consisting of a small header, image, and paragraph element), I wanted the gallery cards to be shown one at a time on mobile views and in a grid format on desktop views. For someone using a laptop, it makes less sense to have to scroll so much to see the available attractions, so I decided to display the gallery cards in a grid format, allowing desktop users to view all the attractions at once. For someone using a phone, it makes more sense to let the user scroll through one gallery card at a time rather than having to swipe sideways to view the other gallery cards.

One place where Claude generated a layout that didn't match your plan, and what you changed.

* For the header image shown across all webpages, Claude made the scaling look weird when changing the screen size. The full image would be shown on smaller screen sizes, but a cropped or zoomed-in version of the image would be shown on desktop screen sizes, which did not look appealing. I had Claude revise the sizing of the header so that the image scaled properly on larger screen sizes.

One layout challenge that required adjusting your HTML structure, and why.

* Most of the HTML structure was kept in tact when applying CSS. I tried to leverage using semantic HTML and good parent-child container organization so that I could better use selectors to apply styling. 

## Milestone 4: Responsive Design
_Add entries after implementing media queries._

What breakpoints did you end up using, and why those values?
* I went with the suggested break point sizes for the desktop, tablet, and mobile phone sizes. Those seem to be the most standard sizes to have compatability for. 

One section where the mobile layout needed to feel genuinely different, and what you did.
* Claude happened to already do this correctly, but it made sure that on mobile, any of the gallery cards are stacked vertically on top of each other so that the full cards could be shown instead of any one of them being trimmed off.

One Claude suggestion about breakpoints you accepted or rejected, and why.
* Claude did not do this but it did suggest adding larger break points for 1280px and 1440px screen sizes, but I decided not to go with them because the website was only really meant to be optimized for standard laptop screens and any sizes below.

## Stretch Features
_Add entries if you implement any stretch features._

* I added an embeded map to the homepage. I asked claude to add the map to the content section of the below the paragraph text introducing the website, so that the user could start exploring things that are nearby. When I asked claude to do this, it also suggested edits to the media querying so that the map could scale well to mobile. I did not consider this when I was prompting so I am glad Claude suggested for me to do this.

* Deployed via github pages (note to self, commit and push changes and the github will automatically redeploy the page)

* Implemented flashing alert symbol that appears on bottom right corner of the screen for all ages.
