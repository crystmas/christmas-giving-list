# The Christmas Giving List

A one-page website that lists programs where you can give a gift at Christmas, to a child, a teen, an adult, or an older adult. Each listing shows the cost, the deadline, and how to give.

**Visit the site:** https://thechristmasgivinglist.org/

## About

- Some programs on the list help people anywhere in the United States. Others help people in New York City.
- It is not a complete list of every program.
- The site is independent. It is not part of any organization on the list.
- Each listing links to the page its information came from. Dates and openings change, so confirm with the organization before you buy a gift.

## See a mistake, or know a program that belongs here?

Tell us with this short form. You do not need to give your name.

https://docs.google.com/forms/d/e/1FAIpQLSfdwLZCQvjUqEZg6rhdhUFrDyp4WQBQvWkwpQ0rKYL52Z11yQ/viewform

## How it is built

- `index.html` holds the list and its script.
- `about.html` is the About page.
- `styles.css` is shared by both pages.
- `fonts/` holds the self-hosted fonts.
- There are still no libraries and no build step.
- GitHub Pages publishes the site from the `main` branch.

## How to edit

- Whenever `styles.css` changes, change the `v=` value in both pages (for example, to today's date plus a number), so visitors' browsers download the new file instead of reusing an old one.
- The 'Updated' date at the top of index.html shows when the list's information last changed. When a change adds or removes a program, or changes a program's details (deadline, cost, steps, about text, status or links), set that date to the day of the change in New York time. Change both the datetime value and the text. Don't change it for changes that only affect the look or the code.
- Change a program's 'checked' date only when its details have been confirmed against the organization's own page.
- Whenever og-image.png changes, change the v= value on og:image and twitter:image in both pages, so link previews use the new picture.

Made by Crystal Marte.
