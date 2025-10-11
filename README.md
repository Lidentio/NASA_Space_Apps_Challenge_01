🌌 NASA Picture of the Day Viewer
🚀 Project Overview

The NASA Picture of the Day Viewer is a simple and interactive web app that displays NASA’s Astronomy Picture of the Day (APOD) using NASA’s public API.
Users can view the image (or video) for any selected date and read its scientific description — all in a clean, minimal interface.

This project was built as part of the NASA Space Apps Challenge to promote public access to space data and inspire curiosity about our universe.

🪐 Features

✅ Displays the Astronomy Picture of the Day (APOD)
✅ Supports custom date selection
✅ Automatically shows today’s picture on load
✅ Handles both images and videos
✅ Built using NASA’s open API
✅ Clean and responsive design using Tailwind CSS

🧰 Tech Stack

Frontend: HTML, CSS (Tailwind), JavaScript

API: NASA APOD API

Hosting (optional): GitHub Pages / Netlify

⚙️ Setup Instructions
1️⃣ Get Your NASA API Key

Visit https://api.nasa.gov

Click “Generate API Key”

Copy your personal API key (looks like Abc123XYZ...)

2️⃣ Add Your API Key

In the index.html file, find this line:

const apiKey = "DEMO_KEY";


Replace it with your actual key:

const apiKey = "YOUR_PERSONAL_API_KEY";

3️⃣ Run the App Locally
Option A — Quickest (Python)

If you have Python installed:

python -m http.server


Then open your browser and visit:
👉 http://localhost:8000

Option B — VS Code

Install the Live Server extension

Right-click index.html → “Open with Live Server”

The app will open automatically

4️⃣ (Optional) Host Online
🔹 GitHub Pages

Create a new repository (e.g., nasa-apod-viewer)

Upload index.html and README.md

Go to Settings → Pages → Source → Deploy from main branch

Your app will be live at:
https://<your-username>.github.io/nasa-apod-viewer

🔹 Netlify (Alternative)

Go to https://www.netlify.com/

Drag and drop your project folder

Your site goes live instantly!

🖼️ Demo Preview

Here’s how the app looks 👇

🌌 NASA Picture of the Day
----------------------------------
[ Select Date: YYYY-MM-DD ] [Get Picture]

[Image or Video Displayed Here]
Title: The Milky Way Above the Mountains
Date: 2025-10-04
Explanation: A breathtaking long-exposure image of our galaxy...

🧑‍💻 Code Structure
📁 nasa-space-apps-challenge-01/
├── index.html     # Main web app
└── README.md      # Documentation

🧠 Learning Outcomes

Using NASA’s open APIs

Handling JSON data in JavaScript

Building responsive UIs with Tailwind

Hosting simple static web apps online

📜 Credits

Data Source: NASA Astronomy Picture of the Day (APOD)

API: NASA Open APIs

Developed by: Abhinav Prasad for the NASA Space Apps Challenge 2025
-------------------------------------------------------------------------------------------------------------------------------

🧾 Changelog
v2.0 – Enhanced NASA APOD Explorer (October 2025)

Major Update: The app has evolved from a simple NASA Picture of the Day viewer into a complete interactive space exploration experience.

New Features

⭐ Favorites System – Save and manage favorite NASA images using browser localStorage.

🎲 Random Picture Button – Explore random APODs from NASA’s archives.

⬇ Image Download Option – Download high-resolution space images directly.

🌓 Dark/Light Mode Toggle – Switch between modes with saved theme preference.

🔊 Voice Narration (TTS) – Listen to APOD explanations via text-to-speech.

⏮⏭ Date Navigation Controls – Easily view previous or next days’ pictures.

Improvements

⚙️ Enhanced responsive design using TailwindCSS.

🧠 Local storage for saving theme and favorites.

🚀 Improved API error handling and smoother data loading.

🎨 Modernized interface with cleaner UI and accessibility tweaks.

Result:
A more immersive, educational, and fun way to explore NASA’s Astronomy Picture of the Day — right from your browser.

🌠 License

This project is open-source under the MIT License
.
Feel free to modify and expand it for your own learning or submissions.
