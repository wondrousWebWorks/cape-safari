# Cape Safari
The live site can be viewed [here](https://wondrouswebworks.github.io/cape-safari/)

This a website created for a fictional company, Cape Safari, which claims to offer a unique safari eperience in their wildlife reserve in the Cape region of South Africa. The site provides information on Cape Safari itself, reviews, accommodation types, and image gallery, the nearby city of Cape Town and upcoming events. It allows visitors to sign up to the site and make a booking if they want to arrange a visit to Cape Safari.
## UX
A colorful theme is used thoughout the site, as it has to be striking to match the beauty and variety of the natural world. For the most part, the background colors for all sections are transparent to show the *hero shot* animation running in the background virtually everywhere on the page. 

The *hero shot* stretches full screen both horizontally and vertically to deliver maximum visual impact and displays a *Call to Action* jumbotron with information meant to pique the user's interest by displaying offers and gives them an opportunity to *sign up* to the website. 

Navigating to different sections of the page is made possible by the *navigation bar*, which is fixed at the top of the page. It also collapses on smaller screens to take up less space and make for a better user experience. It allows to user to *sign in*, *contact* Cape Safari or make a *booking*.

Users can view some of the most important features of Cape Safari in the **About** section, which features four cards which highlight the relevant information.

In the **Gallery** section, users can view a selection of photos showing some of the animals found at Cape Safari. Once a user clicks/taps on any image in the **Gallery**, a modal launches allowing them to view the entire gallery fullscreen if they so choose.

The **Accommodation** section allows users to view all accommodation types on offer, with images of the accommodation type, a star rating, icons showing which amenities are present, the price and a button to launch the *Booking Modal*.

Another addition is the **Review** section where users can read some feedback from previous Cape Safari customers to entice a possible booking from them.

The next section, **Explore Cape Town**, aims to provide the user with information on the incredibly popular city Cape Town by highlighting some of the cities main features and attractions. Each card has a button which will take the user to an external site, which opens in a new tab, where more information on the relevant feature is available.

Second to last is the **Upcoming Events** section, which provides the user with information on the academic talks and music concerts taking place at Cape Safari. It also shows a timeline with upcoming events and dates allowing the user the plan thir visit accordingly should they be interested.

A **Footer** section at the bottom of the page shows the relevant copyright information, as well as links to Cape Safari's *social media* accounts.
## Technologies
* HTML5
* CSS3
* Bootstrap (4.3.1)
* jQuery (3.3.1)
## Features
This site makes heavy use of *Bootstrap* features, such as:
* Responsive grid
* Navbar (collapsible)
* Jumbotron
* Cards
* Carousels
* Badges
* Tooltips
* Forms
* Modals
* Buttons
### Features Left to Implement
In the future, I would like to add more accommodation options with more than the four basic anemnities listed at present. I would also like to add links to the images in the **Gallery** section to take the user to a *Wikipeadia* entry for the particular animal in question. Photos of the unique flora found only in the Cape region of South Africa would also be a welcome addition. A separate page with some brief introductions to the fauna and flaura found at Cape Safari can also be added down the line.
## Testing
The fictional Cape Safari company set out a list of user stories that had to be satisfied for the site to be considered appropriate for their needs.
### Known Errors
There seems to an error generated by the jQuery code snippet used for smooth scrolling page naivigation, which can be viewed in the console when any link for site navigation is clicked/tapped. The scroll behaviour is as expected, but the error message in the console has yet to be understood by the page author. It is something which will be addressed at once when the author has more knowledge of jQuery and its functionality. A few inexplicable animation issues have been noted on *Safari* mobile browsers and should be addressed and fixed in future.
### Devices and Browsers
The website has been successfully tested on a variety of mobile devices, ranging from the most popular Android devices to Appel devices including tablets. Testing has also been performed on a selection of browsers, including *Chrome, Opera, Firefox, Brave, Safari* and newer versions of *Internet Explorer* (Edge).
### Navbar
On clicking any of the links in the navbar's *SITE NAVIGATION* dropdown, the page will scroll smoothly to the relevant section using the jQuery snippet listed in the **Acknowlegements** section of this document. Clicking the *BOOK NOW*, *CONTACT US* or *SIGN IN* navigation links will open the links' corresponding modal.
### *Book Now*, *Contact Us*, *Sign In* and *Sign Up* Modals
Trying to submit the **BOOKING** form without supplying an *email address*, *check-in* date, *check-out* date, *payment card number*, *card expiry date* or *3 digit security code* will results in failure.

The same restriction holds true for the **CONTACT** form, where an *email adress* and a *query message* in the provided text area are required to submit the form successfully.

Both the **SIGN IN** and **SIGN UP** forms require an *email address* and *password* to be submtted successfully. If the user has not yet signed up to Cape Safari, they are afforded the opportunity to do so from the **SIGN IN** form, where a button click will take them to the **SIGN UP** form directly. The same holds true if the user finds themself at the **SIGN UP** form, but already have an account. A button on this form take the user directly to the **SIGN IN** form.
### About
All four cards in the **About** section have the same animations on hover, which include a 180 degree rotation and horizontal and vertical centering of the card's icon, as well as centering and enlargement of the card's text to be displayed in front of the icon. The text's background color also changes to a transparent black, and the text color itself to yellow to increase legibility. In addition to these animations, there is also a continuous colour-cycling animation running on each card's icon's background. The color-cycling animation stops on hover.
### Gallery
Images in the gallery section are successfully fetched from *Cloudinary* and displayed rotated at three predefined angles. Image shadows display correctly to give the impression of each image not being displayed flush with the gallery's wall background. On hover, each image rotates to a zero degree angle. Once an image is clicked/tapped, an image viewing modal (FancyApp) lauches allowing the user to view and browse the gallery more easily where images are displayed at larger sizes.
### Accommodation
An enlarged box-shadow effect makes it easier for the user to see which **Accomodation** card their mouse is currently positioned over. Each card has an image carousel, and clicking/tapping the left or right chevron icons successfully loads the next image in sequnce. Hovering over the amenity icons launches the expected *tooltip* providing a text description of the relevant amenity. Clicking/tapping the *BOOK NOW* button launches to **BOOKING** modal, also accessible from the **Navbar** at the top of the page.
### Reviews
On hover, each **Review** card displays the expected behaviour: the reviewer's photo rotates 180 degrees, the photo's dark filter increases to full opacity to display the full-colour image and the *div* containing the card's text animates an enlargement of the box-shadow effect to draw the user's attention to the written review. 
### Explore Cape Town
Each of the four cards behave as expected on hover. The card's *heading* translates vertically to the top of the card, while the paragraph's color increases in opacity to make it visible at the centre of the card. A dark filter is also aplied behind the text to increase its legibility, while at the same time making the background image's colours less vibrant.
### Upcoming Events
A carousel successfully displays two slides with their respective background images and a list with an opaque background and differently coloured even and odd list items. Clicking on the left and right chevron navigation icons succesfully launches to next or previous slide. A separate timeline adds a text shadow and changes the text color on hover of any timeline item.
### Footer
The copyright information, wondrousWebWorks logo and famous quote all display as expected.
## Deployment
The site is deployed directly from the master branch on **Github pages** and can be viewed [here](https://wondrouswebworks.github.io/mp1-cape-safari/). As per convention the landing page, and therefore only page, is named *index.html* to allow for correct deployment.
## Credits
All content was written by me, apart from:

 1. the quote by Sir David Attenborough in the footer section, which I found in an article listing his  most famous quotes on *independent.co.uk* [here](https://www.independent.co.uk/arts-entertainment/tv/news/david-attenborough-best-quotes-birthday-a7724216.html)
 2. the information in the Explore Cape Town section cards, which were taken from:
  * [capetown.travel](https://www.capetown.travel) and [getaway.co.za](https://www.getaway.co.za/travel-news/cape-town-voted-worlds-best-city/) for the *The Mother City* card  
  * [waterfront.co.za](https://www.waterfront.co.za) for the *V&A Waterfront* card
  * [en.wikipedia.org/wiki/Greenmarket_Square](https://en.wikipedia.org/wiki/Greenmarket_Square) for the *Greenmarket Square* card
  * [tablemountain.net](https://www.tablemountain.net/) for the *Table Mountain* card
 

## Media
All animal photos were taken from [Pexels](https://www.pexels.com/). The thumb tack vector images used in the **Gallery** section were taken from [Vecteezy](https://www.vecteezy.com) and cropped to give the illusion of being pushed into the wall. I designed the wondrousWebWorks() logo myself. All images are hosted on [Cloudinary](https://www.cloudinary.com/). All icons were taken from [Font Awesome](https://fontawesome.com/).


## Acknowledgements
In order to achieve a smooth scrolling effect to IDs, a qQuery snippet found [here](https://www.taniarascia.com/smooth-scroll-to-id-with-jquery/) was used instead of the smooth scroll-behaviour CSS option to allow for an offset because of the fixed *Navigation Bar* at the top of the screen. **Hover.css** found [here](https://ianlunn.github.io/Hover/) was used for the horizontal shutter efect on hover of *Navigation Bar* items.
