# Portfolio Website

## Overview:

This is a portfolio website for a developer or a small agency that builds websites. It is a multi-page website consisting of the home, about, projects, and contact pages. In this website you are able to view the developer's background information, skill levels, and past completed projects. On the contact page, you are able to leave your contact information and message to the agency or developer so that you are contacted at a later stage.

## Issues found in the starter code and fixes implemented:

### Home page:

1. Regularly fixed indentation by using ctrl + alt + F.
2. Added a meta tag, so that the website displays characters correctly.
3. Added “./” to the pathway of the href attribute to correctly reference the stylesheet.
4. Added lang = “en” on the html opening tag so that the website reads in English.
5. Added a navigation bar on the header. The navigation bar was missing completely.
6. Properly aligned the title to center. Alignment was missing.
7. Added images folder to directory.
8. Renamed the welcome/profile photo to welcome.png. 
9. Added the alternate attribute to the img tag. This was missing completely, and it posed an accessibility issue.
10. Added an email link to the footer. It was just plain unclickable text at first.
11. Changed the welcoming text on the hero section.
12. Changed the text on the about me section, it was lorem ipsum at first. Then added links to the contact and projects page.
13. Changed generic <div> tags with semantic HTML5 elements across the html pages to header, main, section, article and footer tags

### About page:

1. Regularly fixed indentation by using ctrl + alt + F.
2. Similarly added a meta tag.
3. Similarly added “./” to the href attribute. It was missing.
4. Similarly added lang = “en”. It was missing.
5. Similarly added a navigation bar. It was completely missing.
6. Edited the paragraph on developer background section to be more informative.
7. Used h2 heading for the photo section and h3 for background and skills for better visual appearance.
8. Added a table to list developer skills. It was completely missing.
9. Removed my photo section to be right below the header for better flow/hierarchy. And I renamed the section to “Meet JuneDevs”.
10. Fixed footer to resemble the one in the home page

### Projects page:

1. Similarly fixed indentation, added a meta tag, added “./” to the href attribute, and added a navigation bar.
2. Added a main tag to add a list of projects.
3. Added images for projects 1 and 2, and added their respective alternate attributes. Sections for the images were present but the photos and the alt text were missing.
4. Added project 3. It was not there completely. I added the title, photo and alt text.
5. Fixed footer to resemble the one in the home page.

### Contact page:

1. Similarly fixed indentation, added a meta tag, added “./” to the href attribute, and added a navigation bar.
2. Added more input types to the form. I added the tel input type for the user’s phone number and a dropdown list for the user’s contact preference.
3. Added corresponding labels to the input types. Labels were completely missing.
4. Added validation to the inputs.
5. Added form ID, action and method attributes. These were completely missing.
6. Fixed footer to resemble the one on the home page.

### Style sheet:

1. Added navigation styling. It was completely missing.
2. Managed to use hover and focus pseudo-classes in the navigation bar.
3. Used selector combinations in the navigation bar..
4. Removed 36px font size for h2 heading, as it made the h2 heading appear like an h1 heading.
5. Changed the background color of the body tag to #ddd. This was just my style choice.
6. Changed the background color of the hero section to match the body, to fix the poor color contrast that initially existed.
7. Changed the hero and footer padding to 30px, to left-align the main content of the home page.
8. Fixed the width and height of the img tags to 325px respectively. I used the element tag so that any image added would have the same dimensions. This improves uniformity and visual appearance. 
9. Combined selectors to left-align the rest of the html pages’content.
10. Added styling for the table on the about me page. It was completely missing.
11. Added styling for the forms. It was completely missing.
12. Added styling for the submission button. Styling was completely missing.
13. Added basic CSS animation for the footers on all of the website’s pages. (for bonus appeal)
14. Added comments for better readability.
15. Fixed indentation by using ctrl + alt + F.

## Description of final HTML structure:

All four pages of the website are constructed following the HTML boilerplate and layout.
The website is built with the consideration of the Document Object Model.
This is so that the structure can be modified and styled by programs or technologies such as JavaScript.
HTML5 semantics are used for better code readability and search engine optimization.

## CSS approach and selectors used:

The styling approach was to improve overall appearance of the website. This included fixing bad color contrasts, enhancing text styling with appropriate fonts, sizes and hierarchy. Then to provide styling were styling was missing in the starter code. Selectors used include: element, class, id, attribute and pseudo-selectors. Selector combination was also used to improve code quality.

## Main accessibility improvements:

1. Used alternate attributes to describe images.
2. Wrote CSS that makes website responsive for different devices.
3. Included a meta tag in the html so that browser reads characters correctly.

## Instructions on how to view website locally:

1. You can download the portfolio-website folder from github onto your local device.
2. Open the folder with a code editor like Visual Studio Code.
3. Open preview of the index html file.
4. Copy the url on the preview browser.
5. Paste url on your device's browser. You will reach the home page of the website.

## Screenshots:

### Home page
![home page](./screenshots/homepage.png)

### About page
![about page](./screenshots/about_page.png)

### Projects page
![projects page](./screenshots/projects_page.png)

### Contact page
![contact page](./screenshots/contact_page.png)

### Navigation menu
![navigation menu](./screenshots/navigation_menu.png)

### Styled table
![styled table](./screenshots/styled_table.png)

### Projects before styling
![project list before styling](./screenshots/project_list(before).png)

### Projects after styling
![project list after styling](./screenshots/project_list(after).png)

### Form before modification and styling
![form before addition of more inputs and styling](./screenshots/form(before).png)

### Form after modification and styling
![form after addition of more inputs and styling](./screenshots/form(after).png)

## Reflection:

1. I did not know where to start with the debugging task. I was not organized.
2. There were many things to fix at different places. I had to do my own checklist and to solve the problem bit by bit.
3. I had to make a wireframe of how I want the site to look.
4. I then started with the home page. Found the errors, fixed them and styled. I continued with that procedure until I got to the contact page.

---
---
---

## <mark>**Portfolio Improvements:**</mark>



## 1. HTML Structure & Semantics

Added `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
to All pages.

Added `<meta name="description" content="…">`
to All pages.

Added `lang="en"` attribute to `<html>` tag
to `projects.html` and `contact.html`.

Removed unnecessary `<div class="header">` wrapper inside `<header>`
from All pages.

Replaced invalid `</br>` tag from `projects.html`.

Wrapped images in `<figure>` / `<figcaption>` for
`about.html`, `projects.html` and `index.html`

Added a skip-to-content link `<a href="#main-content" class="skip-link">` to
All pages.

---

## 2. Navigation & Linking

Added `aria-current="page"` to the active navigation link on each page
for All the pages.

Added visible focus styles (`outline: 3px solid #007BFF`) for all interactive elements to
`styles.css`.

Added `nav li a[aria-current="page"]` style (bottom border + bold) as a visual active-page indicator to
`styles.css`

---

## 3. Images & Tables

Replaced fixed dimensions with `max-width: 100%; height: auto` in the
`styles.css` file.

Moved skill-bar widths from inline `style="width: X%"` initially in the `about.html` file, to CSS custom property `--gauge-width` in the `styles.css` file.

Added `<caption>` to the skills table in the `about.html` file.

Added `scope="col"` to all `<th>` elements in the `about.html` file.

Activated `.table-wrapper` div around the skills table in the `about.html` file.

Added `role="img"` and `aria-label` to each gauge container in the `about.html` file.

Updated project image alt text to be more descriptive in the `projects.html` file.

---

## 4. Forms & Accessibility

Wrapped related form fields in `<fieldset>` / `<legend>` groups ("Your Details" and "Your Message")
in the `contact.html` file.

Added `autocomplete` attributes (`name`, `tel`, `email`) to relevant inputs
in the `contact.html` file.

Added `title` attributes to inputs with format requirements
in the `contact.html` file.

Added an `aria-live="polite"` status div (`#form-status`)
in the `contact.html` file.

Added `novalidate` to the `<form>` element
in the `contact.html` file.

Changed submit button text from "Send" to "Send Message"
in the `contact.html` file.

---

## 5. CSS Styling & Selectors

Added CSS custom properties (variables) for all repeated colour, spacing, and font values
in the `styles.css` file.

Removed duplicate `.footer` rule block
from the `styles.css` file.

Added explicit `:focus` styles for links, inputs, textarea, select, and button
in the `styles.css` file.

Added `button:hover` and `.btn:hover` colour change
in the `styles.css` file.

Added `@media (prefers-reduced-motion: reduce)` block to disable animations when requested by user, in the
`styles.css` file.

---

## 6. Box Model & Layout

Added `*, *::before, *::after { box-sizing: border-box; }` reset
in the `styles.css` file.

Added `max-width: 960px; margin: 0 auto` container to `<main>`
in the `styles.css` file.

Converted project sections for the projects page to a CSS Grid layout (`auto-fit`, `minmax(260px, 1fr)`)
in the `styles.css` file.

Added flex layout with `flex-wrap: wrap` to the hero section
in the `styles.css` file.

Added `@media (max-width: 600px)` breakpoint with mobile adjustments
in the `styles.css` file.

Added `line-height: 1.6` to the `body` rule
in the `styles.css` file.

---

## 7. Text & Colour Design

Added `--color-accent` and `--color-accent-hover` variables to be applied consistently to links and buttons
in the `styles.css` file.

Added hover and focus colour changes to `.contactLink` in the footer, in the
`styles.css` file.

Added `justify-content: center` to `nav ul` in the
`styles.css` file.

Styled `<th>` elements with a light background colour
in the`styles.css` file.

---

## 8. Code Quality & Organisation

Organised CSS into clearly labelled sections using meaningful comments throughout the
`styles.css` file.

Added `font-family` and `font-size: 1rem` explicitly to form input elements in the
`styles.css` file.

Added `background-size: 400% 400%` to `.footer`, in the `styles.css` file, so the gradient animation actually runs.


Added a `.btn` call-to-action link to the home page hero pointing to the projects page, in the 
`index.html` file.

---