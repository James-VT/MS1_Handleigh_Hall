# Handleigh Hall README

https://james-vt.github.io/MS1_Handleigh_Hall/

## Table of contents

* Project overview
* UX
* User stories
* Site owner stories
* Features
* Template
* Colours
* Wireframes
* Technologies used
* Validations
* Testing
* Bugs
* Features credits

## Project overview

This project imagines the creation of a website for a fictional visitor attraction in Oxfordshire. It imagines this property - an old English country house - has recently opened to the public and the charitable trust thast runs the site wants a website for a number of purposes. They want to generate revenue by securing ticket bookings, they want to relay information to visitors about what's on offer, how to get there, and when visitors can come, and they want to generate interaction with the public. This latter will happen both directly, via a contact form, and by directing people to social media.

## UX

The main goals of the Handleigh Hall website are twofold: for its users, information; for its owners, revenue. Visitors to the site will want to know how to visit and what to expect. The owners of the site - Handleigh Hall Trust - will want to increase the revenue and publicity of the site.

### The goals of a user:

1. Learn whether the site is worth visiting.
2. Learn when they can visit the site.
3. Learn how to get to the site.
4. Learn how to visit the site.
5. Learn how to arrange a visit to the site.

### The goals of the site owners:

5. Generate revenue through ticket sales.
6. Relay information to visitors on how to get there.
7. Relay information to visitors regarding what's available at the site.
8. Generate revenue by relaying information about the food and beverage outlet on site.
9. Drive up engagement with the public via social media and direct feedback
10. Relay just enough history of the site itself to tickle the interest of prospective visitors and turn this interest into bookings.

As part of the planning for this project, I have run through the stages of User Experience Design, as proposed by [Jesse James Garrett.](https://en.wikipedia.org/wiki/Jesse_James_Garrett)

Addressing the strategy plane for this project, I asked myself who would need this website, and what they might hope to achieve by using it. I have asked these questions from the point of view of the owner and a visitor to the website. The site owner wants to generate revenue and visits by selling tickets, and making visitors aware of what's available. Visitors want to know if this place is worth visiting, and how to do so.

The Scope Plane: This plane helped to prevent the project growing beyond its immediate scope. The main strategy is to generate ticket sales by promoting the property. As such, the pages in the navigation bar are chosen to address the main questions of a visitor to these places: what is it, what food and drink is available, are there public lavatories, etc.

The Structure Plane: my wireframes can be found below. These have been constructed with the idea that mobile design should come first, and that the main aim from the point of the view of the site owner is to generate income via bookings to visit the historic house. This is why the BOOK button is visible for as much of the time as possible, and each page presents its information in a way that encourages the selling of tickets.

The Skeleton Plane:

The Surface Plane: Colours for the website were chosen based on those colours associated with the visual look of Handleigh Hall itself. Green for the grass around it, blue for the (optimistically) blue sky above, and the beige colour of the navigation bar to resemble the colour of the local stone from which the property was constructed.

* This is the visitor website of the organisation looking after a historic building opened to the public as a visitor attraction.
* This website exists to provide information to visitors, and to convey information from the site owners to said visitors.
* As a visitor to the website, I want to know what's on offer, the location, and how to book tickets to visit.
* As the owner or manager of the organisation, I want to relay to customers the info that will generate revenue.


## User stories

Table | Second column | Third column
--- | --- | ---
1 | 2 | 3 

## Site owner stories

## Features

Features to build for the site

## Template

Aspiring to simplicity, the website has been designed with a simple template that can be used across all pages. The background images have been chosen carefully (credit for these can be found below) to provide a visual indication of what's on offer at the property, and space has been left so that these remain visible on all screen sizes.

### Colours

For the site's colours, I have chosen gentle pastel colours of beige and blue. The beige is to match the colour of Cotswold stone from which the fictional building is constructed, and the blue is supposed to match the blue sky. I did not choose a directly analogous sky blue as this didn't match the beige so well, so instead a pastel blue was chosen. The background colour of the main image is a gentle green to be similar to the grass. I chose a slightly sharper shade of green than pastel green in order to contrast a little better with the pastel colours between which it would be sandwiched should the background image fail to load.

A similar beige colour to the header was chosen for the text boxes as these will scroll up over the building or sit alongside them at wider screen sizes.

### Wireframes

The layout of the pages for this project were planned using Balsamiq's wireframes. The wireframes for mobile devices can be found [here.](docs/wireframes/wireframems1mobile.pdf) The wireframes for tablets can be found [here.](docs/wireframes/wireframems1tablet.pdf) The wireframes for desktops can be found [here.](docs/wireframes/wireframems1desktop.pdf)

## Technologies Used

* [Balsamiq](https://balsamiq.com/)
    * Balsamiq was used to develop the wireframes for this project.

* [HTML5](https://html5.org) 
    * The HTML pages for this site were written using HTML5. TODO: CHECK IF THIS SITE IS CORRECT

* [CSS3](http://www.css3.info/)
    * The CSS styling for this site was written using CSS3. TODO: CHECK IF THIS SITE IS CORRECT

* [Bootstrap](https://getbootstrap.com/)
    * Bootstrap was used in this project to provide styling frameworks and for the automatic elements of responsive design it comes with. The version I have used is Bootstrap 4.

## Validations
* HTML + CSS validations, no errors, links to evidence pictures
* Accessibility - wave
* Performance - lighthouse

## Testing
Testing against stories - how was this goal achieved? Evidence - screenshot

## Bugs

* An issue was discovered on very large screen widths with the footer bunching up to the left if the text boxes don't have enough content in them. I suspect this is something to do with the blank space I left for the background image, but I'm uncertain why it only happens at screen widths approaching 1800 pixels. As yet, this is unfixed as the amount of content I have on each page is enough to keep everything where it should be even at these larger widths and in the hypothetical situation in which this was a genuine website for a genuine property, the amount of information in those text sections would become more over time, not less.

# Credits

## Navigation bar
* The original code for the site's navigation bar in the header is taken from Bootstrap 4's [Nav code.](https://getbootstrap.com/docs/4.0/components/navbar/#nav) I have edited it with some styling.

## Footer spacing
* The column spacing in the footer was acheived using Bootstrap 4's [Grid system.](https://getbootstrap.com/docs/4.0/layout/grid/#auto-layout-columns)

## List Unstyled
* The .list-unstyled class is a Bootstrap 4 class used for [list styling.](https://getbootstrap.com/docs/4.6/components/list-group/)

## Font
* The font used throughout is Roboto, a google fonts font, and sans-serif is used as the backup for if Roboto cannot load. [Roboto.](https://fonts.google.com/specimen/Roboto#standard-styles)

## Index/home page
* Background image is an open-source image. [Photo by Yaosheng Zheng on Unsplash](https://unsplash.com/photos/mpGz-JBOnZU)

* First carousel image is of Lodge Park, taken from Wikipedia. [Link and licence.](https://commons.wikimedia.org/wiki/File:Lodge_Park,_Gloucestershire,_May_2016_side_view.jpg)

* Second carousel image is open-source, photo taken by Birmingham Museums Trust. [Photo by Birmingham Museums Trust on Unsplash](https://unsplash.com/photos/P2pGX2-zWNs)

* Third carousel image is open-source, photo taken from unsplash. [Photo by Content Pixie on Unsplash](https://unsplash.com/photos/m-gqDRzbJLQ)

## Find Us page
* The directions and text used on the Find Us page were taken from the website for [Lodge Park and the Sherborne Park Estate](https://www.nationaltrust.org.uk/lodge-park-and-sherborne-park-estate#How%20to%20get%20here) and edited to suit.

* The contact form on the Find Us page was adapted from Bootstrap 4's contact page template, found [here.](https://getbootstrap.com/docs/4.0/components/forms/#form-controls)

* Background image on the Find Us page is an open-source image. [Photo by Randy Fath on Unsplash.](https://unsplash.com/photos/TUXrJZCNHbU)

## Facilities page
* Background image on the Facilities page is an open-source image. [Photo by Suhyeon Choi on Unsplash.](https://unsplash.com/photos/4Ia348kvX7A)

## Carousel
* Carousel used is one of Bootstrap's components, found [here.](https://getbootstrap.com/docs/4.0/components/carousel/#with-controls)

## Booking page
* Background image is an open-source image. [Photo by Eric Muhr on Unsplash.](https://unsplash.com/photos/6HdfrD20rTk)