# Swara's Cat-Themed Birthday Website 🐱💗

## Preview
Unzip this folder and open `index.html` in your browser. Tap the cat three times. The first pet starts a synthesized instrumental birthday melody and a cute synthesized meow plays on every pet. Cut the cake to unlock the gift menu.

Browsers generally require a click/tap before sound can start. The melody is synthesized in the browser, so no music file is needed. It is an instrumental melody, not a recorded vocal song.

## Add more photos
Put images in `assets/photos/`. The sample gallery uses `photo1.jpg` through `photo6.jpg`. Then open `script.js` and add entries to the `PHOTOS` array, e.g.
`{file:"assets/photos/photo7.jpg",caption:"our silly day ♡"},`
Use the actual file extension if you use PNG.

## Add more letters
In `script.js`, add another object inside `LETTERS`:
`{title:"Open when you miss me",subtitle:"a little reminder",body:\`Hey Swara,\n\nWrite your letter here. ♡\n\n— your bestie\`},`
Separate objects with commas.

## Publish for free
1. Sign in at https://github.com and create a public repository such as `swara-birthday`.
2. Upload `index.html`, `style.css`, `script.js`, and the `assets` folder (not only the ZIP).
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
5. Wait for the published URL shown on the Pages settings screen. It typically looks like `https://YOUR-USERNAME.github.io/swara-birthday/`.

GitHub Pages hosting is free for public repositories; no custom domain is required. Public websites can be seen by anyone with the link, so only upload photos you are comfortable sharing.
