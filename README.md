# Editkaro.in-Portfolio-Website
A complete multi-page portfolio website designed for Editkaro.in, a Social Media Marketing & Video Editing Agency.
The site highlights their services, video portfolio, brand identity, and ways for clients to connect and collaborate.

This project demonstrates strong skills in responsive design, UI/UX development, form handling, animations, and dynamic content integration.

🌐 Live Pages Included
Page	Key Elements
Home	Hero banner, scroll animations, services showcase, email subscriber form (Google Sheets integration), CTA buttons
Portfolio	Category-based filtering, 18 editable portfolio items, thumbnails, hover animations, lightbox video player
About Us	Mission, vision, core values, team showcase with 6 members (placeholders), “Why Choose Us” section
Contact	Contact form with database integration, office details, business hours, form validation & live success/error feedback
✨ Website Features
🏠 Home Page

Hero section with gradient animation + CTA buttons

Services highlights with hover effects

Email Subscription Form ✅ Integrated with Google Sheets

Content structured for lead generation

🎞️ Portfolio Page

Advanced filtering: Short / Long Form, Gaming, Football, Ads, Documentary, Anime, Color Grading, etc.

18 project items with stock placeholders (changeable to real client assets)

Smooth interactions + video lightbox for immersive viewing

👥 About Us Page

Mission & Vision storytelling

Core company values section

Team showcase with professional placeholder images

Highlights why clients should choose Editkaro.in

📩 Contact Page

Fully functional contact form

Auto-store submissions in Google Sheets using Google Apps Script / API

Real-time validation

Business hours & contact details

🛠️ Tech Stack
Technology	Usage
HTML5	Website structure
CSS3	Styling, animations, responsiveness
JavaScript	Filtering, lightbox, form handling, interactions
Google Sheets + Apps Script	Database for contact & email submissions
📁 Project Structure
Editkaro-Website/
│
├─ index.html           # Home Page
├─ portfolio.html       # Portfolio Page
├─ about.html           # About Page
├─ contact.html         # Contact Page
│
├─ assets/
│   ├─ images/          # Images & thumbnails
│   └─ videos/          # Video assets (optional, external links supported)
│
├─ css/
│   └─ style.css        # Main stylesheet
│
└─ js/
    └─ script.js        # Filtering, lightbox, form handling, animations

✅ Setup Instructions

1️⃣ Download or clone this repository
2️⃣ Open any .html file in a browser — works without a server
3️⃣ Update video links & images in the Portfolio section
4️⃣ Connect forms to your own Google Sheet using provided Apps Script template

🔌 Google Sheets Integration

Both Email Subscriber Form and Contact Form send data to Google Sheets.

📌 Setup Guide:

Create a Google Sheet

Go to Apps Script → Paste the provided script

Deploy as Web App → Copy the endpoint URL

Paste the URL inside script.js form submission function

Test and verify live database updates! ✅

📈 Performance & SEO Optimizations

Metadata & Open Graph tags for social visibility

Mobile-first responsive layout

Optimized media loading & caching

Semantic HTML for accessibility
