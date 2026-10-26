SOLEHAAA — BIRTHDAY SURPRISE WEBSITE
From Ali Hasan | Luxury black-and-gold theme | No database

FILES
- index.html: all wishes, memory dialogue and final message
- style.css: design and animations
- script.js: slide navigation and optional music picker
- assets/: optional music file goes here

PREVIEW
1. Extract this ZIP.
2. Open the folder in VS Code.
3. Double-click index.html to open it in your browser, or use VS Code Live Server.
4. Tap the music button to choose an audio file for local preview.

IMPORTANT: The music picker plays a file only in your own browser session. It does not upload or share the audio. To include music for Solehaaa:
1. Put a permitted audio file in assets/, e.g. assets/soft-piano.mp3.
2. In index.html change <audio id="audio" loop></audio> to <audio id="audio" loop src="assets/soft-piano.mp3"></audio>.
3. In script.js find `let hasTrack=false` and change it to `let hasTrack=true`.
4. The button still opens the picker first by design; for a simple shared music button, change the music click handler to toggle audio playback instead of calling file.click() when no track is selected. Browsers normally require a tap before music starts.

EDIT TEXT
Open index.html and search for:
- Solehaaa — name/title
- Pata hai, aaj ka din — main birthday wishes
- Nahhhhh — auditorium memory
- Once again Happy Birthday — final personal message
Edit text between the HTML tags, but keep the tags intact. The supplied wording has been lightly cleaned in a few places for readability; you can restore any original phrase you prefer.

PUBLISH FREE USING GITHUB PAGES
1. Create a public GitHub repository (example: solehaaa-birthday).
2. Upload index.html, style.css, script.js, and assets/ if you added music.
3. Go to repository Settings → Pages.
4. Select Deploy from a branch, branch main, folder /(root), then Save.
5. Wait for the published URL to appear and test it on your phone.
6. Send that public URL to Solehaaa.

No database or backend is used. The personal message is in the static HTML, so it appears for everyone who opens the published website. Upload changed files again if you edit after publishing. Use only music you own or have permission to share.


BACKGROUND MUSIC — ALREADY INCLUDED
The uploaded Kalam Eineh track is included as assets/kalam-eineh-slow.mp3.
It has been slowed to about 88% speed, reduced in volume, and given a soft fade-in/out.
The site tries to start the song when the visitor presses the first "Open your surprise" button.
Browsers can block audio until a user taps; the top-right music button always lets them play/pause it.
Keep the assets folder when publishing. The MP3 is part of the ZIP and will be hosted with the website.
