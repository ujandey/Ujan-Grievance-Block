Ujan Grievance Block
A retro-styled, mobile-friendly grievance submission form inspired by Minecraft vibes — powered by Google Forms. Perfect for collecting anonymous feedback or complaints with a cool pixel-art aesthetic.

Features
Pixel art Minecraft grass block background for nostalgic vibes

Fully responsive design that looks great on desktops and mobiles

Uses a hidden iframe to submit the form silently without page reload

Displays a thank you message after submission, hiding the form

Anonymous submission option with optional name field

Easy to customize Google Forms integration

How It Works
User fills out their grievance and optional suggestions or name.

On submit, form posts data to Google Forms using a hidden iframe (no page reload).

After submission, the form disappears, and a thank you message shows up.

Setup
Replace the form action URL with your own Google Forms POST URL if you want to use your form.

Make sure the input name attributes match the Google Form field names (like entry.1780480500).

Host the HTML file anywhere (GitHub Pages, your server, local machine).

Open in any modern browser, mobile or desktop, and start collecting grievances!

Customization
Change background image by editing the CSS body background URL

Adjust colors, fonts, and spacing in the CSS to match your style

Add or remove form fields to suit your data needs (remember to update Google Form accordingly)

Add more client-side validation or animations as desired

Tech Stack
HTML5 + CSS3

Vanilla JavaScript

Google Forms backend for data collection

No dependencies or frameworks

Troubleshooting
If the thank you message doesn't show, ensure your Google Form URL and field names are correct.

If the form reloads the page, check the iframe name matches the form’s target attribute.

Make sure JavaScript is enabled in your browser.

License
Free to use and customize for any project. If you improve it, share the love!

