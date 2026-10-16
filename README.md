# Anjappar Restaurant Website

A responsive one-page website for Anjappar Chettinad Restaurant in Nungambakkam, Chennai. I built it as a practice project to work on HTML and CSS layout, and later cleaned it up and rebuilt the styling so it works properly on phones as well as desktops.

> This is a personal practice project. It is not affiliated with or endorsed by Anjappar. The restaurant name, logo and photo belong to their owners and are used here for learning only.

## What's on the page

- A full-screen hero section with the restaurant's logo, a short welcome message and a "Make a reservation" button that opens an email to book a table
- A navigation bar with working links to each section (Home, About, Find us, Contact) and smooth scrolling
- An embedded Google Map showing the restaurant's location
- A footer with the address and a tap-to-call phone link

## Built with

- HTML5
- CSS3 (flexbox, `clamp()` for fluid headline sizing, a media query for small screens)
- No JavaScript, frameworks or build tools

## Project structure

```
index.html      the page
style.css       all styling
images/
  logo.jpg
  background.webp
```

## Running it locally

There is nothing to install. Download or clone the repo and open `index.html` in any browser.

```
git clone https://github.com/monishvijaybharat/HOTEL-WEBSITE-.git
```

The map needs an internet connection to load.

## What I changed from the first version

- Rewrote the headline and fixed grammar mistakes in the copy
- Replaced the fixed 1024px layout with a responsive one that works on phones
- Added a dark overlay on the background photo so the text is easy to read
- Made every navigation link work and added accessible labels (page title, map title, image alt text)
- Fixed the reservation email address
- Removed leftover files from an earlier saved copy of the page and from CSS practice exercises

## Author

Monish Vijay Bharat
