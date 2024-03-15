# Band website for 'Hot Gin Swing'

## Table of Contents
1. [UX](#1-ux)
    - [Strategy](#strategy)
    - [Scope](#scope)
    - [Structure](#structure)
    - [Skeleton](#skeleton)
    - [Surface](#surface)
2. [Features](#2-features)
3. [Technology used](#3-technology-used)
4. [Testing](#4-testing)
	- [Bugs](#bugs)
5. [Credits](#5-credits)

## 1. UX

### Strategy

#### Project goals

This website is a place for prospective clients to find out about the South Wales-based, swing/jazz band Hot Gin Swing. It will introduce users to the band and provide information about the type of musical services they offer, examples and images of their performances, reviews, and contact information.

#### Band goals

The band's main aim is to get more bookings. They therefore want to increase and improve their online presence, providing information about their music and availability in a professional-looking format. They have a presence on Facebook and Youtube where they post upcoming gigs, videos and photos of performances and booking details, but often potential clients ask to see a website. They would like to direct potential clients to the website as the main source of information about the band.
The website will also be an opportunity to establish a 'house style' for the band in terms of font, colour, logo and image format, which can then be used on promotional material and on the band's social media. This 'house style' could also be made available to clients (particularly festival and dance organisers) as a promotional pack.

#### User goals

Users may access the website for a number of reasons:
- an event organiser already considering booking the band, looking for confirmation as to the quality of the band's music and suitability fo their event
- an event organiser browsing/searching for musical acts in their region
- a casual visitor, or someone who has heard the band at a performance and wants to find out more about the band, including future performances

All of these users will need to easily navigate through the information on the site. Contact information will need to be readily available. Images and media will need to be of the highest quality available. Information about what the band offer will need to be displayed clearly and in a friendly and professional manner.

#### User stories

- As a potential client, I want:
	1. To hear/watch examples of the band's performances
	2. To find out about the range of musical services they offer
	3. To read reviews about the band's performances from other clients
	4. To be able to get in touch easily to make an enquiry
	5. To see images of the band's appearance
	6. To know that the band will be friendly and easy to deal with
	7. To find out about the band's repertoire and the styles of music they perform
- As a festival organiser, in addition to the potential client desires, I want:
	1. To know about any of the band's other festival appearances
	2. To find out about the band's reputation
	3. To see images/video content of previous appearances
- As a dance event organiser, in addition to the potential client desires, I want:
	1. To know the repertoire, to judge whether it will be suitable for my event
	2. To read reviews of the band's performances at other dance events
- As someone who recently heard the band at a performance, I want:
	1. To learn more about the band

---
### Scope

#### Required features

In order to meet the requirements identified at strategy level, the following features and information will need to be included in the website:

- General information about the band
- Information about the band's previous performances
- A range of reviews from the band's previous performances
- A range of images of the band
- A selection of video and audio content
- Information about the band's repertoire
- Information about what a potential client could expect from the band from arrival to departure
- Contact information in a range of formats
- links to the band's social media

---
### Structure

The required information will be laid out in the following pages:

*Home page*
- A hero image
    - This will need to be high quality and one that communicates a sense of the band's style and energy
- A brief description of the style of the music and events the band can cater for
- A brief summary of contact information and/or link to contact form

*About page*
- General information about the band
- Information about band's previous festival appearances and brief testimonial
- FAQs including information about what a client can expect from the band

*Gallery page*
- A range of images of the band

*Music page*
- A selection of video and audio clips of the band's performances
- Information about the band's repertoire
- Links to social media websites

*Testimonials page*
- A range of reviews from the band's previous performances

*Contact page*
- Phone and email contacts
- A contact form

Notes:
- The band's name and logo will appear fixed in the top left of the navbar.
- Social media links will appear in the navbar and in the footer.
- Contact information and/or a contact form will also appear above the footer on every page to make this information easily accessible.


Here is a proposed [site map](./assets/site_map.png "Opens site map as png") for the above pages.

---
### Skeleton

#### Wireframes

The following wireframes were created in Balsamiq and include responsive design ideas for Laptop, Tablet and Mobile devices.

[Home](assets/wireframes/home.png "Opens Home page wireframe as png")  
[About](assets/wireframes/about.png "Opens About page wireframe as png")  
[Gallery](assets/wireframes/gallery.png "Opens Gallery page wireframe as png")  
[Music](assets/wireframes/music.png "Opens Our Music page wireframe as png")  
[Testimonials](assets/wireframes/testimonials.png "Opens Testimonials page wireframe as png")  
[Contact](assets/wireframes/contact.png "Opens Contact page wireframe as png")  

---
### Surface

#### Design choices

**Layout**

- The navbar will be fixed at the top of the screen so that at any point, a user can navigate to any of the main pages. (On mobile, the nav menu will appear as a list icon).
- The logo and name of the band will be fixed in the left of the navbar.

**Fonts**

- Font for band name:
- Font for headings
- Sans-serif font selected for the main body

**Icons**

The following icons from FontAwesome will be used in the site:
- Martini as main logo (placeholder for a more unique logo design)
- Phone
- Email

**Colours**

Palette will be derived from the main images used on the site.
- The band wears formal wear for their performances (DJs, white shirts, sparkly ball gowns), and so the background palette will build on this:
    - A high contrast between black and off-white with some splashes of colour, taken from the colours in the background and gallery images.

**Styling**

- The aim is to minimise the written content and major on the visual impact of images, audio/video and clear layout.
- The highest volume of text will be on the About page:
    - This will be broken up into sections with different visual cues for the About us and FAQ section.

**Images and backgrounds**

- A range of images from the band's performances have been used as background images and in the Gallery section
- To give these a consistent sense of style, saturation has been reduced and a warm filter has been applied.
- Background images will have an opacity applied (using rgba) to ensure that the text is clear, but such that the image can still 'speak'.
- Size and resolution of images will be adjusted to ensure that they load as quickly as possible. 

**Audio/video files**

- Video files will either be embedded Youtube clips or saved with the project files. If the latter, then these will be edited down to minimise load time.
- Audio files will be edited clips (not full tracks) and compressed to minimise load time.

---
## 2. Features

### Future features

- Link contact form to backend server
- Arrange professional photo and video shoot to replace images and video with higher-quality content

---
## 3. Technology used

- The code was written in Gitpod using a Github template from Code Institute

- Images were resized and edited using [TinyJPG](https://tinyjpg.com/) and [RedKetchup](https://redketchup.io/image-resizer)

---
## 4. Testing

### User stories



### Bugs

- About page - containers not adjusting height dynamically when resizing viewport
- - found thread on Stackoverflow explaining that body tag needed to be at 100%

---
## 5. Credits

### Code

- Navbar code copied from [Boostrap](https://getbootstrap.com/docs/4.2/components/navbar/#placement) and edited and styled

### Images

- Contact page background image by Ardian Lumi, downloaded from [Unsplash](https://unsplash.com/photos/group-of-people-dancing-6Woj_wozqmA)

- FAQ background image by Miti, downloaded for free from [Unsplash](https://unsplash.com/photos/person-playing-cielo-black-and-white-photography-vSws0g1KjxI)

- About page background image by Jens Thekkeveettil, downloaded for free from [Unsplash](https://unsplash.com/photos/person-playing-saxophone-dBWvUqBoOU8)

- Media background image by Daniel Lazar, downloaded for free from [Unsplash](https://unsplash.com/photos/brown-and-white-piano-keys-KWUuFjXWzcI)

- All other images taken by the band

### Video

- Embed code copied from [Youtube](https://www.youtube.com/watch?v=-6qFbtDSqgM)
