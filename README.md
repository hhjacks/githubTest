# Where Should I Eat?

This is a lightweight React app that fetches nearby restaurants using the Google Places API and randomly suggests one to you. It relies on your browser's geolocation feature.

## Setup

1. Open `index.html` in a modern browser.
2. Replace `YOUR_API_KEY` inside the file with a valid Google Places API key.
3. It's best to run a local server so the external scripts load properly:
   ````bash
   python3 -m http.server
   ````
   Then browse to `http://localhost:8000`.

## Usage

- Click **Use My Location** to allow geolocation.
- The app fetches restaurants within 5 km and filters them to a minimum 4.0 rating.
- Click **Spin** to get a random restaurant. Use **Try Again** to reroll.
- Select **Open in Google Maps** to view the restaurant on Google Maps.

The layout is mobile-first thanks to Tailwind CSS loaded from the CDN.
