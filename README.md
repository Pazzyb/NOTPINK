# !NOTPINK

**!NOTPINK** is a promotional website for a female rock band. The site introduces the band, promotes its latest album, *Echoes in the Static*, showcases photos, displays merchandise, and allows visitors to sign up to a newsletter.

Live site: [https://pazzyb.github.io/NOTPINK/index.html](https://pazzyb.github.io/NOTPINK/index.html)

## Table of Contents

1. [Project Overview](#project-overview)
2. [UX](#1-ux)
   - [Project Goals](#project-goals)
   - [User Goals](#user-goals)
   - [Developer and Business Goals](#developer-and-business-goals)
3. [Features](#features)
4. [Pages](#pages)
   - [Home](#home)
   - [Gallery](#gallery)
   - [Merch](#merch)
   - [Contact](#contact)
5. [User Journey](#user-journey)
6. [Design Choices](#design-choices)
   - [Colour Scheme](#colour-scheme)
   - [Typography](#typography)
   - [Imagery](#imagery)
   - [Layout](#layout)
7. [Accessibility](#accessibility)
8. [Responsive Design](#responsive-design)
9. [Technologies Used](#technologies-used)
10. [Project Structure](#project-structure)
11. [Getting Started](#getting-started)
12. [Deployment](#deployment)
13. [Future Improvements](#future-improvements)
14. [Credits](#credits)
15. [Copyright](#copyright)

## 1. UX

### Project Goals

The goal of this project is to design and build a bold, engaging, and user-friendly website that promotes **!NOTPINK**, a female rock band. The website introduces the band, promotes its latest album, *Echoes in the Static*, showcases photographs, displays merchandise, and allows fans to sign up for updates.

The site aims to create a strong visual identity, encourage visitors to listen to the band’s music, and make it easy for fans to explore content and purchase merchandise.

### User Goals

As a visitor to the website, I want to:

- Quickly understand who !NOTPINK are and what their music sounds like.
- Find and listen to the band’s latest album.
- View photos of the band in the gallery.
- Browse available merchandise and see prices clearly.
- Sign up to receive news and updates from the band.
- Connect with the band through social media.
- Use the website easily on a phone, tablet, or desktop.

### Developer and Business Goals

The goals of the developer and business are to:

- Create a visually striking website that reflects the band’s rebellious and energetic identity.
- Promote the new album and encourage visitors to stream or purchase it.
- Increase interest in the band through the gallery and social media links.
- Display merchandise clearly and direct users to an external store to make a purchase.
- Collect newsletter sign-ups from interested fans.
- Build a clean, responsive, and accessible static website.
- Use semantic HTML, Bootstrap, and custom CSS to create a maintainable front-end project.
- Deploy the completed website using GitHub Pages.
- Create a portfolio-ready project that demonstrates user-centred front-end development skills.

## Features

- Fixed navigation bar with links to Home, Music, Gallery, Merch, About, and Contact
- Responsive Bootstrap navigation that collapses into a mobile menu on smaller screens
- Hero image introducing the band
- About section explaining the band’s identity and musical style
- Album promotion section for *Echoes in the Static*
- External link to Spotify for streaming
- Link to the merch store
- Photo gallery
- Merchandise cards showing product images, names, prices, and purchase links
- Newsletter sign-up form with first name, last name, and email fields
- Social media links
- Responsive layout for desktop, tablet, and mobile devices
- Accessible navigation controls and image alt text

## Pages

### Home

The homepage introduces !NOTPINK, presents the band’s message, promotes the album *Echoes in the Static*, and provides links to stream the music or visit the merch store. It also includes social media links in the lower section of the page.

### Gallery

The gallery displays images of the band. It uses a simple image-based layout to showcase the band’s visual identity.

### Merch

The merchandise page presents products in a card-based layout. Current items include:

| Product | Price |
|---|---:|
| Hoodie Sweater | £35.00 |
| Tee | £15.00 |
| Tote Bag | £10.00 |
| Vinyl Record | £65.00 |

Each product includes an image, price, and a “Buy” button that opens an external Shopify link.

### Contact

The contact page contains a newsletter sign-up form. Users can enter their first name, last name, and email address before submitting the form.

## User Journey

A typical user journey is:

1. The user arrives on the homepage and sees the band’s name, hero image, and introduction.
2. They read about the band’s style and identity.
3. They see the promotion for *Echoes in the Static* and click **Listen Now** to stream the album.
4. They visit the gallery to view images of the band.
5. They visit the merch page to browse products and prices.
6. They sign up to the newsletter through the contact page.
7. They use the social media links to follow the band on other platforms.

This journey supports the main business aims of increasing music streams, merchandise interest, and fan engagement.

## Design Choices

### Colour Scheme

The website uses a dark, high-contrast colour scheme to match the band’s rock identity. Dark backgrounds, light text, and strong borders create a bold and dramatic appearance.

This design choice supports the band’s message of being unconventional and energetic, while also helping important content stand out.

### Typography

The site uses clear headings and readable body text. Large headings such as **“WE’RE !NOTPINK. WE DON’T DO ORDINARY.”** immediately communicate the band’s attitude and make the homepage more engaging.

### Imagery

Photographs are used throughout the site to create an emotional connection with visitors. The homepage includes a black-and-white band image and the album cover, while the gallery displays additional band photographs.

### Layout

The layout is simple and focused, with clear sections for the band introduction, album promotion, social links, gallery, merchandise, and newsletter sign-up. Bootstrap is used to create a responsive grid-based layout that adapts to different screen sizes.

## Accessibility

The website includes several accessibility features:

- A viewport meta tag to support responsive scaling on mobile devices.
- A navigation toggle button with `aria-label="Toggle navigation"` for screen-reader users.
- Descriptive alt text for key images, including the band photo and album cover.
- Visible form labels for first name, last name, and email address.
- External links include `rel="noopener noreferrer"` for safer navigation.
- A visually hidden message tells users that merchandise links open in a new tab.

## Responsive Design

The website is designed to work across desktop, tablet, and mobile devices.

- The navigation menu collapses into a hamburger menu on smaller screens.
- Images use Bootstrap’s responsive image classes to scale appropriately.
- Merchandise cards adjust from one column on mobile to multiple columns on larger screens.
- The newsletter form uses a simple vertical layout that remains easy to complete on mobile devices.

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons
- GitHub Pages for deployment

## Project Structure

```text
NOTPINK/
│
├── index.html
├── gallery.html
├── merch.html
├── contact.html
├── README.md
│
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── images/
│   └── favicon/
│
└── site.webmanifest
```

## Getting Started

To view the project locally:

1. Clone or download the repository.
2. Open `index.html` in a web browser.

No installation, build process, or server is required because this is a static front-end website.

```bash
git clone [https://github.com/pazzyb/NOTPINK.git](https://github.com/pazzyb/NOTPINK.git)
cd NOTPINK
```

Then open `index.html` in your browser.

## Deployment

The website is deployed using GitHub Pages.

To deploy your own version:

1. Push the project files to a GitHub repository.
2. Go to **Settings**.
3. Open the **Pages** section.
4. Select the branch to deploy from, usually `main`.
5. Choose the root folder, `/ (root)`.
6. Save the settings.
7. GitHub Pages will provide a live URL.

## Future Improvements

Potential improvements include:

- Adding real music previews or embedded audio players
- Creating individual product pages for merchandise
- Adding a working contact form with confirmation feedback
- Improving the gallery with a lightbox or carousel
- Adding an events or tour dates page
- Improving SEO through page-specific meta descriptions
- Adding more detailed accessibility testing
- Replacing placeholder or external links with the band’s official platforms

## Credits

- Website design and development: Paz Ai
- Framework: [Bootstrap](https://getbootstrap.com/)
- Icons: [Bootstrap Icons](https://icons.getbootstrap.com/)
- Deployment: [GitHub Pages](https://pages.github.com/)

## Copyright

© 2026 !NOTPINK. All rights reserved.