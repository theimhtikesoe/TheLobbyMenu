

⸻

🥂 The Lobby Bar and Bed — QR Menu Website

📖 Overview

This is a QR-based Digital Menu Web App for The Lobby Bar and Bed, designed to give customers an elegant and immersive experience.
When customers scan the QR code, they’ll be redirected to a full-screen vertical menu, where they can swipe up/down to view drinks and cocktails — one photo per screen.

Built with pure HTML, CSS, and JavaScript, this site loads instantly and runs smoothly on mobile devices without any backend or database.

⸻

✨ Features
	•	📱 Mobile-first vertical layout — optimized for bar menus & restaurant use
	•	🎞️ Smooth scrolling — one image per screen (like Instagram story style)
	•	⚫ Right-side navigation dots — shows which page the user is on
	•	🔁 Up/Down buttons — for easier navigation
	•	🌙 Dark glass design — modern & stylish for nightlife vibes
	•	🖼️ Google Drive image hosting — easy to manage & update your menu photos

⸻

🧩 How It Works
	1.	Customer scans the QR code from the table or counter.
	2.	The site opens in full screen — index.html.
	3.	The bar’s menu photos (hosted on Google Drive) appear one by one.
	4.	Guests swipe vertically or tap arrows to explore.

⸻

🛠️ Tech Stack
	•	HTML5 – Structure
	•	CSS3 (custom dark theme) – Styling & layout
	•	Vanilla JavaScript (ES6) – Smooth scroll, dot navigation, and image loading
	•	Google Drive – Used as the image CDN

⸻

📦 Installation

You can deploy this easily on any static hosting service:

Option 1: Vercel
	1.	Go to https://vercel.com/
	2.	Create a new project and import your GitHub repo.
	3.	Deploy — done!
	4.	You’ll get a live link like:

https://the-lobby-menu.vercel.app



Option 2: GitHub Pages
	1.	Push your project to GitHub.
	2.	Go to Settings → Pages → Branch: main → / (root).
	3.	Wait for a few seconds — your live link will be ready.

⸻

🖼️ Image Setup (Google Drive)

To change or update menu photos:
	1.	Upload new photos to Google Drive.
	2.	Set permission to “Anyone with link → Viewer.”
	3.	Copy your file ID from the Drive URL:

https://drive.google.com/file/d/FILE_ID/view?usp=sharing


	4.	Convert it into a direct link:

https://drive.google.com/uc?id=FILE_ID


	5.	Replace it inside the images array in your index.html:

const images = [
  { src: "https://drive.google.com/uc?id=YOUR_FILE_ID" },
  ...
];



⸻

💡 Tips
	•	Ideal image size: 1080x1920px (9:16 ratio) for mobile clarity
	•	Recommended format: .jpg (smaller file, faster load)
	•	Use Canva or CapCut to export vertical poster-style designs
	•	Keep file size under 1.5MB per image for faster QR load

⸻

🧾 Project Structure

/The-Lobby-Menu/
├── index.html     # main website
├── README.md      # project info
└── /images/       # (optional) if using local images


⸻

🌐 Credits
	•	Design & Concept: Rhyzoe
	•	Brand: The Lobby Bar and Bed
	•	Code & Web Dev: Rhyzoe x ChatGPT (GPT-5)
	•	Image Hosting: Google Drive

⸻

🚀 Future Upgrades
	•	Add “📍 Google Map” and “📞 Call Us” buttons at bottom
	•	Add “🍸 Drink Category” filters (Beer, Cocktails, Spirits)
	•	Add language toggle (EN / TH / MM)

⸻

© 2025 The Lobby Bar and Bed
“Good drinks, good music, and even better vibes.” 🍻

⸻
