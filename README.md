# Ceylora Journeys

A polished, responsive homepage for a fictional Sri Lankan travel agency, created for a web developer practical assessment.

## Features

- Responsive navigation and mobile menu
- Tour filtering and accessible itinerary dialogs
- Interactive four-step custom trip planner
- Active navigation, scroll reveals, and back-to-top control
- Testimonial slider and accessible FAQ accordion
- Validated trip finder and inquiry delivery through WhatsApp
- SEO metadata, TravelAgency structured data, sitemap, and robots file
- Real Sri Lankan destination photography from free-use travel photo libraries, with a dedicated credits page
- Tour durations, routes, and indicative starting prices researched from Sri Lankan Private Tours; all descriptions and presentation are original to this project

## Technologies

Semantic HTML5, modern CSS3, and vanilla JavaScript. No framework or build tool is required.

## Run locally

Open `index.html` directly, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Forms

The inquiry form validates the customer's details, prepares a formatted message, and opens a WhatsApp chat with the travel administrator. The customer must tap **Send** in WhatsApp to deliver the inquiry. No data is stored by the website. An email link is included as a fallback.

## Deployment

Upload the folder to Netlify, GitHub Pages, Vercel, or any static web host. Replace the fictional canonical URL and contact details before launch.

## Photography

All website photography shows real Sri Lankan destinations and wildlife. Source and licence information is listed in `photo-credits.html`. Images were resized and compressed for web delivery.
