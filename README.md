Campus Events Guide

A five-page, responsive website that helps students find a campus event, read the details, check the schedule and save their place. Built with plain HTML and CSS only for SW302 User Interface Development, Zewail City, Fall 2026.

The featured event is Campus Care Day, Saturday 14 November 2026, 9:00 AM to 5:00 PM, at Sunset Lawn and Main Hall.

Pages
Page	File	What it does
Home	index.html	Introduces the guide and the featured event
Events	events.html	Lists upcoming and past events as cards
Details	event-details.html	Everything about Campus Care Day, with a teaser video, agenda and a review form
Schedule	schedule.html	A table of upcoming events
Register	registration.html	A registration form with validation
Features
Semantic HTML5: header, nav, main, section, article, aside, footer, figure, table with caption and headings.
One external stylesheet, style.css, built on CSS variables for colour, type and spacing.
Flexbox for the header and navigation, CSS Grid for the card layouts and the details page.
Mobile-first responsive layout, tested at 375, 768 and 1280 px. The schedule table turns into cards on phones.
A CSS-only dark mode, using a hidden checkbox and the :has() selector. No JavaScript.
Hover and focus transitions on links, buttons and cards, switched off for people who prefer reduced motion.
Forms with visible labels and required, pattern, maxlength, min and max validation. The registration form uses all 13 control types the brief asks for.
Accessibility: skip link, visible focus rings, text contrast checked against WCAG, images with alt text, and a figure caption that describes the silent teaser video.
Folder structure
campus_events_omar/
  index.html
  events.html
  event-details.html
  schedule.html
  registration.html
  style.css
  assets/
    fonts/
    images/
    media/
Run it

There is nothing to install or build. Download or clone the repository and open index.html in Chrome or Edge.

bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
Notes
The forms check input in the browser but do not send it anywhere, because the site has no server or JavaScript.
Dark mode is CSS-only, so it resets when you move to another page.
Credits
Fonts: Fraunces and Atkinson Hyperlegible Next, both under the SIL Open Font License 1.1, self-hosted in assets/fonts/.
Images and the logo are original SVG illustrations made for this project. The teaser video is a short silent clip made for the project, with no people shown.
Author

Omar Amgad, Software Development (HCI), Zewail City.
