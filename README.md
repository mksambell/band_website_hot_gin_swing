# **Hot Gin Swing**

Hot Gin Swing is a 6-piece jazz/swing band based in South Wales. With a growing reputation and increasing number of regular performances, the band is looking to improve the quality of their online presence. The site is targeted at prospective clients who might be interested in booking the band for a private function or public event. It introduces users to the band and provides information about the type of musical services they offer, examples and images of their performances, testimonials, and contact details.

Welcome to the site! [**Hot Gin Swing**](https://mksambell.github.io/band_website_hot_gin_swing/)

![Responsive Screenshot](./assets/readme-images/responsive-screenshot.jpg)

## Contents
1. [**User Experience UX**](#1-user-experience-ux)
    - [Strategy](#strategy)
	- [User Stories](#user-stories)
    - [Site Structure](#site-structure)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
2. [Features](#2-features)
3. [Technology used](#3-technology-used)
4. [Testing](#4-testing)
	- [Bugs](#bugs)
5. [Deployment]
6. [Credits](#5-credits)
7. [Acknowledgements]

# 1. User Experience UX

## Strategy

### Band goals

The band's main aim is to get more bookings. They therefore want to increase and improve their online presence, providing information about their music and availability in a professional-looking format. 

They have a presence on Facebook and Youtube where they post upcoming gigs, videos and photos of performances and booking details, but often potential clients ask to see a website. They would like to direct potential clients to the website as the main source of information about the band.

The website will also be an opportunity to establish a 'house style' for the band in terms of font, colour, logo and image format, which can then be used on promotional material and on the band's social media. This 'house style' could also be made available to clients (particularly festival and dance organisers) as a promotional pack.

Users may access the website for a number of reasons. They could be:
- an event organiser already considering booking the band, looking for confirmation as to the quality of the band's music and suitability for their event
- an event organiser browsing/searching for musical acts in their region
- a casual visitor, or someone who has heard the band at a performance and wants to find out more

[Back to top](#contents)

## User stories

As a potential client, I want:
1. To find out basic information about the band
2. To hear/watch examples of the band's performances
3. To find out about the range of musical services they offer
4. To read testimonials about the band's performances from other clients
5. To be able to get in touch easily to make an enquiry
6. To see images of the band's appearance
7. To know that the band will be friendly and easy to deal with
8. To find out about the band's repertoire and the styles of music they perform
9. To find my way easily around the site
10. To know how to connect with the band on social media


[Back to top](#contents)

---

## Site Structure

The site is structured with six pages:

[*Home*](index.html)
- The landing page contains a hero image, a brief description of the band and contact information

[*About*](about.html)
- General information about the band
- A brief testimonial
- Link to band's facebook page
- FAQs to answer some general questions users may have

[*Gallery*](gallery.html)
- A range of images of the band

[*Music*](music.html)
- A selection of video clips of the band's performances
- Information about the band's repertoire
- Link to band's Youtube channel

[*Testimonials*](testimonials.html)
- A range of testimonials
- Logos of festivals at which the band has performed

[*Contact*](contact.html)
- Contact information
- A contact form. When submitted a [enquiry receipt](contact-received.html) page displays
- There is a link to a [privacy policy](privacy.html) in the footer

Notes:
- The band's name and logo will appear fixed in the top left of the navbar.
- Social media links will appear in the navbar and in the footer.
- Contact information and/or a contact form will also appear above the footer on every page to make this information easily accessible.

[Back to top](#contents)

---
## Wireframes

The following wireframes were created in [Balsamiq](https://balsamiq.com/) and include responsive design ideas for Laptop, Tablet and Mobile devices. The final design differs from the wireframes due to changes made in the design process. For example, the contact form does not appear at the bottom of every page. It was felt that there was sufficient access to it through the home page, navbar and footer and that it would be unnecessary and annoying to the user.

### Home
![Home](assets/wireframes/home.png "Opens Home page wireframe as png")  
### About
![About](assets/wireframes/about.png "Opens About page wireframe as png")
[Back to top](#contents)
### Gallery
![Gallery](assets/wireframes/gallery.png "Opens Gallery page wireframe as png")
### Music
![Music](assets/wireframes/music.png "Opens Our Music page wireframe as png")
[Back to top](#contents)
### Testimonials
![Testimonials](assets/wireframes/testimonials.png "Opens Testimonials page wireframe as png")  
### Contact
![Contact](assets/wireframes/contact.png "Opens Contact page wireframe as png")
[Back to top](#contents)

---
## Design choices

**Typography**

The fonts chosen were:

- Josefin Sans
	- Used in uppercase for the main logo. This has a vintage 1930s/1940s feel which suits the style of the band. In uppercase and with sufficient weight, it is bold and eyecatching.
- Raleway
	- Used for navbar links, page headings, highlighted taglines and in italics for testimonials. Complements the main logo font well.
- Source Sans
	- Used for the main body of the text. Very easy to read.

All fonts default to sans serif.

**Icons**

A handful of [FontAwesome](https://fontawesome.com/) icons are used to draw attention to contact information throughout the site:
- Phone
- Envelope (for email)
- Checkist (for contact form)
- List (to replace default navbar toggler)

[Back to top](#contents)

**Colours**

The colour scheme was chosen to reflect the formal wear the band plays in (DJs, white shirts, sparkly ball gowns) and also a sense of the muted colours of vintage style; a high contrast between two types of black and an off-white with two splashes of red, both taken from the colour of the tie in the hero image on the landing page. The lighter colour is used against black backgrounds to provide a higher contrast; the darker red is used against the off white in the navbar and footer.

![Colour palette](/assets/readme-images/colour-palette.png)

**Styling**

- The aim is to minimise the written content and major on the visual impact of images, audio/video and clear layout.
- The highest volume of text will be on the About page:
    - This will be broken up into sections with different visual cues for the About us and FAQ section.

**Images and backgrounds**

- A range of images from the band's performances have been used as background images and in the Gallery section
- To give a consistent sense of style, saturation has been reduced and a warm filter has been applied.
- Background images that are too bright are overlayed with an opaque layer to ensure the text is clear.
- Size and resolution of images have been adjusted to ensure that they load as quickly as possible to maximise the user experience. 

[Back to top](#contents)
---
## 2. Features

The site is intended to be easy to navigate around and intuitive to use. Common pages, terminology and icons are used to help the user find their way around easily, and high contrast between font and background has been used to make the text immediately clear.

## Existing Features

- Navigation Bar
	- The navbar is fixed at the top of the screen so that at any point, a user can navigate to any of the main pages. 
	- The name/logo of the band is fixed in the left of the navbar and is a link to the home page
	- The dropdown menus for the About and Music pages provide links to the FAQ and Repertoire sections respectively
	- Active links are shown in bold to show the user where they are in the site.
	- Links turn red when hovered over as shown in the pictures below.
	- On mobile and tablet devices, the nav menu appears as a list icon. The default Bootstrap has been replaced with a more elegant icon from FontAwesome.
	- The social media links only appear in the navbar at laptop size; they are hidden in mobile and tablet version to avoid cluttering the interface. The same links are permanently in the footer.

![Navbar Laptop](/assets/readme-images/navbar.jpg)


![Navbar Collapsed](/assets/readme-images/navbar-small.jpg)


[Back to top](#contents)

- Footer

[Back to top](#contents)

- About us

[Back to top](#contents)

- FAQ

[Back to top](#contents)

- Gallery

[Back to top](#contents)

- Media

[Back to top](#contents)

- Repertoire

[Back to top](#contents)

- Testimonials

[Back to top](#contents)

- Contact

[Back to top](#contents)

- Contact receipt

[Back to top](#contents)

- Privacy policy

[Back to top](#contents)

**Layout**

- The navbar will be fixed at the top of the screen so that at any point, a user can navigate to any of the main pages. (On mobile, the nav menu will appear as a list icon).
- The logo and name of the band will be fixed in the left of the navbar.

### Future features

- Link contact form to backend server
- Link to a wider range of media, including audio clips
- An upcoming gigs section
- A link to download a promotional pack, including logo, photos, etc that clients could use to promote their event.

---
## 3. Technology used

- The wireframes were created using [Balsamiq](https://balsamiq.com/)
- The structure of the site was written in [HTML5](https://html.spec.whatwg.org/)
- The site was styled using [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
- [Bootstrap 4.2](https://getbootstrap.com/docs/4.2/layout/grid/) was used to create the grid system and provide some styling
- The site was developed in [Gitpod](https://www.gitpod.io/) using a Github template from [Code Institute](https://github.com/Code-Institute-Org/ci-full-template)
- [Github](https://github.com/) was used for version control and for hosting
- Images were resized and edited using [TinyJPG](https://tinyjpg.com/) and [RedKetchup](https://redketchup.io/image-resizer)

---
## 4. Testing

### User stories



### Bugs

- About page - containers not adjusting height dynamically when resizing viewport
- - found thread on Stackoverflow explaining that body tag needed to be at 100%

---
## 5. Deployment

---
## 6. Credits

### Code

- Navbar code copied from [Boostrap](https://getbootstrap.com/docs/4.2/components/navbar/#placement) and edited and styled

- Embed code copied from [Youtube](https://www.youtube.com/watch?v=-6qFbtDSqgM)

### Content

- Fonts from [Google Fonts](https://fonts.google.com/)
- Icons from [FontAwesome](https://fontawesome.com/)
- Colour palette created with [Coolors](https://coolors.co/)

### Media

- Contact page background image by Ardian Lumi, downloaded from [Unsplash](https://unsplash.com/photos/group-of-people-dancing-6Woj_wozqmA)

- FAQ background image by Miti, downloaded for free from [Unsplash](https://unsplash.com/photos/person-playing-cielo-black-and-white-photography-vSws0g1KjxI)

- About page background image by Jens Thekkeveettil, downloaded for free from [Unsplash](https://unsplash.com/photos/person-playing-saxophone-dBWvUqBoOU8)

- Media background image by Daniel Lazar, downloaded for free from [Unsplash](https://unsplash.com/photos/brown-and-white-piano-keys-KWUuFjXWzcI)

- All other images taken by the developer, Mark Sambell, and other members of the band.

## 7. Acknowledgements


