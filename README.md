# Love Like Cora Website

This repository contains the Love Like Cora landing page.

The site highlights Cora's story, a featured news video, donation options, and social links for community support.

## Current Stack

- HTML5
- Tailwind CSS via CDN
- Font Awesome via CDN

## Project Structure

- index.html: Main one-page website
- images/1000014772.png: Hero background image

## Main Sections On The Page

- Hero section with call-to-action buttons
- As Seen On WTVM News video section
- Direct Support donation methods section
- Join the Movement section with shirt and social links
- Footer

## Run Locally

Option 1: Open directly

1. Open index.html in your browser.

Option 2: Run a local web server (recommended)

1. From the project folder, run:

	python3 -m http.server 8000

2. Open:

	http://localhost:8000

Using a local server is better for consistent behavior with embeds and browser security rules.

## Editing Guide

- Update hero background image in the style block inside index.html by changing the hero-gradient background URL.
- Replace the donation widget placeholder in the Direct Support section.
- Update Facebook and TikTok links in the Join the Movement section.
- Update donation handles in the Direct Support cards.

## Notes

- The YouTube embed may not always render inside some editor preview panes due to sandbox restrictions.
- If that happens, open the site in a regular browser using localhost.