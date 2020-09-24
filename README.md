# Site.js Regression Testing List

# Navigation

**Menu Toggle**

function toggleMenu()

* Upon clicking the menu icon in tablet/mobile view the menu should switch between opened and closed.
* Requirements: Click Menu icon on Mobile/Tablet view.

*Testing:*
1. Does it show desktop?


**Search toggle**

function toggleSearch()

* When search button is clicked the search bar either shows or closes depending on it's state
* Requirements:

*Testing*
1. Does the close button function accordingly

**Mobile accordion**

function toggleDropdown()

* In the mobile/tablet menu the accordion dropdown should open accordingly upon clicking with one at a time.
* Requirements: 

*Testing:*
1. 

**Site Header**

``
let lastScrollTop = 0;

window.onscroll = function() {
  const header = document.querySelector(".site_header");
  const headerHeight = header.offsetHeight;
  const st = window.pageYOffset;
  if (st > headerHeight) {
    header.classList.add("site_header--shrink");
    if (st > lastScrollTop) {
      header.classList.remove("site_header--fixed");
    } else {
      header.classList.add("site_header--fixed");
    }
  } else {
    header.classList.remove("site_header--shrink", "site_header--fixed");
  }
  lastScrollTop = st;
};
``

# Paragraphs

**Hero Video Paragraph**

function killVideos()

* Kill video with in the iframe

function playVideo()

* Play youtube video within the iframe

Opens video modal
function js-modal-open()

function js-modal-close()

**Google Maps Paragraph**

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


// Fetches the height of the header
function getHeaderHeight() {

  //Wildlife page anchor scrollto

    $('.js-anchor').on('click', function (e) {
    
        function matchHeightWildlifeExpertPanel () {
