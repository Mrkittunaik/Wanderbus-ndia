Placify Trip demo (vanilla HTML/CSS/JS, no build step).
Open index.html in a browser, or run: npx serve .
Demo tour data: top of app.js (const T). Simulated bookings/auth only, stored in localStorage.
Images are generated SVG artwork; swap in licensed photos via the art() helper.

Google login: in images.js set GOOGLE_CLIENT_ID (Google Cloud Console > OAuth Web client, add your site origin).
Real Google sign-in needs http(s) hosting (not file://). Without a client ID, a demo account chooser is used.
