# SurveyMarket website

The public marketing site for SurveyMarket: what we do, how it works, pricing and privacy.

## Handover notes (from Tiago)

Hi Catherine, welcome aboard!

This is the first version of the site. Right now it only lives on my laptop.
To see it, I open a terminal in this folder and run:

    python3 -m http.server 8000

then go to http://localhost:8000.

It's plain HTML and CSS, no build step:

- `index.html`: the whole home page
- `styles.css`: all the styling
- `404.html`: the page people see for a wrong address
- `assets/`: logo and icon

Things I know are missing:

- The contact form. Ifeoma is building that later.
- We haven't checked the site for broken links.
- No idea how to get it online yet. That's why you're here :)

— Tiago
