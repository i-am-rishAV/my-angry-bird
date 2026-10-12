THE BIRTHDAY WEBSITE — ROMANTIC INTERACTIVE EDITION
===================================================

QUICK START
1) Double-click index.html. The website works as a standalone file.
2) Open index.html in VS Code (or any text editor).
3) Search for "const CONFIG =" (about a third of the way down the file).
4) Change herName, nickname, yourName, and any messages you want.
5) Save, and reload the page to see your changes.

PHOTOS
- Three photos are already included next to index.html:
      photo1.jpg   the butterfly selfie   (memory 1, and tucked inside the envelope)
      photo2.jpg   the cake moment        (memory 2, and shown after the candles)
      photo3.jpg   the night fair         (memory 3)
  They were resized for the web and camera metadata was removed.
- To swap one, drop your picture in this folder and point the matching
  photo: '...' entry in CONFIG.memories at it. Use photo: '' for none.
- focus: '50% 30%' chooses which part of a tall photo stays in view
  (first number = left/right, second = up/down).
- coverPhoto is the little round picture inside the envelope.
- cakePhoto is the polaroid that appears once all three candles are out.
- The finale gallery reuses the memory photos automatically.
- Keep the photo files next to index.html when you upload the site.

HOW THE EXPERIENCE WORKS
Invitation -> Three stars -> Three love-note cards -> Memory album
-> Scratch-to-reveal -> Unseal personal letter -> Blow out candles
-> Birthday finale with a photo gallery, a secret promise, falling
   hearts, and replay.
Arrow keys browse the album on a computer; swiping works on a phone.

MUSIC
- A soft music-box "Happy Birthday" melody, synthesized in the browser.
  No music file is required.
- Music only plays when she taps the Music button. This is intentional
  because phones and browsers block autoplay.

SHARE IT AS A WEBSITE LINK (FREE)
OPTION A: Netlify Drop
1) Visit https://app.netlify.com/drop
2) Upload the birthday-surprise-v3 folder (index.html AND the photos).
3) Copy the generated public URL and send it to her.

OPTION B: GitHub Pages
1) Create a public GitHub repository.
2) Upload index.html plus the photo files to the repository root.
3) Repository Settings -> Pages -> Deploy from branch -> main/root.
4) Share the GitHub Pages URL once deployed.

PRIVACY / NOTES
- Anyone with the link can open the site and see the photos, so share
  the link only with her if you don't want others to see them.
- Default birthday is October 13, 2026 (India time).
- Google Fonts are used for nicer typography; the page falls back to
  system fonts offline. All features work without an external library.
