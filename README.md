# Site.js Regression Testing List

## Navigation

**Menu Toggle**

function toggleMenu()

* Upon clicking the menu icon in tablet/mobile view the menu should switch between opened and closed.
* Requirements: Navigation menu must be visible on webpage.

*Testing:*
1. Does it show desktop?
2. Does is dissapear on Tablet/Mobile View? (Should be yes)

**Search toggle**

function toggleSearch()

* When search button is clicked the search bar either shows or closes depending on it's state
* Requirements: Top header must be visible on webpage.

*Testing*
1. Upon click does the searchbox appear over the navigation menu? 
2. Does the close button function accordingly?
3. Does it function on Tablet/Mobile?
4. Do search queries work?

**Mobile accordion**

function toggleDropdown()

* In the mobile/tablet menu the accordion dropdown should open accordingly upon clicking with one at a time.
* Requirements: Navigation menu must be open on Tablet/Mobile

*Testing:*
1. Does each menu item open when clicked?
2. Is only one item active at a time?
3. Is it hidden on desktop?
4. Do links take you to the right pages?

**Site Header**
* The site header contains the navigation menu and top menu.
* Requirements: Must be at the top of any webpage

*Tests:*
1. Is the site header visible?
2. After scrolling down the page from the inital page's position, does the top menu dissapear? 
3. Scrolling further down the page, is the navigation menu fixed to the top of the page?
4. After scrolling down the page and back to the top, does the top menu reappear ontop of the navigation menu?
5. Are the transitions between the menu positions menu?

## Paragraphs

**Hero Video Paragraph**
* Top banner hero containing a video.

[These functions open the modal and plays the video within the iframe]

function js-modal-open()

function playVideo()

[These functions close the modal and stops the video within the iframe]

function js-modal-close()

function killVideos()

*Tests*
1. In the hero paragraph, when the play button is clicked does the video player modal open?
2. Does the modal close after user clicks outside of the modal?


**Google Maps Paragraph**
* A map of the given coordinators should appear in this container

Main function used in array containing nested functions.
function javascriptMap()

mapMouseUp()

mapMouseDown()

mapMouseLeave()

**Adoption Slice**

function toggleDropdown()

* In the mobile/tablet menu the accordion dropdown should open accordingly upon clicking with one at a time.
* Requirements: 

*Testing:*
1. 

function resetAdoptionPanelErrorMessage()
**Donation - give an hour**

**fundraising**

toggleColor


# Miscellaneous

**Scroll to Link**

function jumpLinkOffset(tar)

* Upon clicking an anchor link the interface should scroll to the specified element on the page
* Requirements: Anchor tag is linked to an existing id tag on the page.

 *Testing:*
1. What happens if element does not exist?
2. Does the link scroll the inputted element?
3. Does the scroll work on mobile?


 * When the page loads, scroll to the ID.
function pageLoad()

 * When the hash changes, scroll to the ID.
function hashScroll() {

**Cookies**

**Tab System**
**Slick Slider**

**matchHeightWildlifeExpertPanel **

**modifierChanger**


**doKonami**
 * Checks to see if we are on same page as the clicked link
 */
function isSamePage(link) {


**Get header Height**
The function fetches the height of the header
function getHeaderHeight()
