The following changes we're made by Kevin Jerome to the original html and css code

1. the [Search Engine Optimization] Text in the Horiseon navigation was linked properly to its header in the lower section, by using it's designated id: "search-engine-optimization"

2. All excessive < div > elements we're changed to properly contain and mark each porttion of the webpage
  - lines 31/53 < div > elements were changed to < section > elements to create a section for the informational links of the navigation bar and to clearly define the main informational section
  - lines 55/77 changed from < div > elements to < aside > elements to place all < h3 > level text in side a proper side container to follow proper structure and to clearly define the side portion of the webpage
  - lines 79/84 placed from < div > elements into proper < footer > elements to define proper bottom container for the bottom of the webpage
  - line 80 labeled with 'Made with [heart symbol] by Horiseon' changed from < h2 > to < h4 > header elements as it's content doesnt contain any information of higher importance than the < nav > < section > or < aside > portions

3. All images and icons we're given < alt > tags for images that can't be displayed due to any technical issues. images and icons we're also given titles for very short descriptions when hovering.

4. Within the CSS file all selectors for HTML attributes we're reorganized so that all the CSS selectors are grouped together based on what CSS selector corresponds with each specific portion of the webpage . CSS selectors for < section > portions are grouped together. CSS selectors for < aside > portion are grouped together. CSS selectors for < nav > are grouped together.

* The < h1 > child element labeled "seo" within the < span > under the parent < nav > element has a CSS selector for color. Please notify me if this is an intentional design choice.

Screenshot of the webpage: ![Alt text](image.png)