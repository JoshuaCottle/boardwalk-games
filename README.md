# Boardwalk Games

Boardwalk Games is a multi-page responsive website for a fictional board game cafe.
It is designed as a front-end portfolio project to demonstrate accessible semantic HTML,
responsive layout work with Bootstrap, and custom CSS styling.

## Project Summary

This website showcases a local board game business with:

- A landing page with services, events, and contact information.
- A game library page with featured and popular games.
- Booking and game reservation forms.
- A form success page for user confirmation.

## UX Goals

The project is built around three user goals:

- Discover what the cafe offers.
- Browse games and upcoming events.
- Quickly submit a booking inquiry.

## Features

- Responsive navigation and layouts across mobile, tablet, and desktop.
- Bootstrap carousel sections for visual engagement.
- Service and game cards with clear content hierarchy.
- Event timetable and opening-hours tables.
- Accessible contact and social links.
- Form validation with `required` fields and mobile-friendly phone inputs.

## Tech Stack

- HTML5
- CSS3
- Bootstrap 5.3
- Font Awesome
- Google Fonts

## Quality Checks

Manual checks completed:

- Navigation links verified between pages.
- Form fields and submission flow checked.
- Mobile and desktop layout behavior reviewed.
- Footer consistency checked across pages.

Recent fixes made during review:

- Fixed broken `Services` link on `booking.html`.
- Replaced `type="number"` phone fields with `type="tel"` and validation patterns.
- Removed stray text at the start of `success.html`.
- Fixed footer social icon class mismatch on `success.html`.
- Corrected typo in the Settlers of Catan option value.
- Added a missing closing `div` in `success.html` footer markup.

## File Structure

```
boardwalk-games/
	index.html
	booking.html
	game-library.html
	success.html
	assets/
		css/
			style.css
		images/
```

## Deployment

This is a static front-end project and can be deployed with:

- GitHub Pages
- Netlify
- Vercel (static hosting)

## How To Run Locally

1. Clone or download the repository.
2. Open `boardwalk-games/index.html` in a browser.

## CV / Portfolio Notes

This project demonstrates:

- Semantic, accessible markup practices.
- Responsive design implementation using Bootstrap and custom CSS.
- Practical UI composition for multi-page user journeys.
- Basic QA and bug-fixing workflow on static websites.