# NASA Astronomy Explorer

A web application that lets users select a date and explore
NASA’s Astronomy Picture of the Day.

## Features

- Select a date using a date picker.
- Request astronomy content from NASA’s APOD API.
- Display the title, picture, and description.

## Built With

- HTML
- CSS
- JavaScript
- Fetch API
- NASA Astronomy Picture of the Day API

## How to Run

1. Download or clone this repository.
2. Configure your NASA API key in js/config.js using the variable
   expected by js/main.js.
3. Open index.html in your browser.
4. Select a date and click Get Picture.

An internet connection and a valid NASA API key are required.
No Node.js server is needed.

## Project Files

- index.html — date picker and astronomy content
- css/style.css — page styling and responsive layout
- css/normalize.css — browser style normalization
- js/config.js — local API configuration
- js/main.js — API requests and page updates
- README.md — project documentation

## Current Limitations

NASA sometimes returns an embedded video instead of a picture.
Embedded video URLs require an iframe; the current HTML uses
a video element, so those videos may not play.

## What I Practiced

- Requesting data from an API.
- Working with dates and JSON responses.
- Updating page content with JavaScript.
- Styling a responsive web page.

## Author

Sushana Thomas