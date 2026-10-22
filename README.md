# Vicky's Birthday Celebration

A single-file, mobile-responsive birthday microsite built with plain HTML, CSS and JavaScript. No build step, backend, login or paid API is required.

## Run locally

- Open `index.html` in a modern browser, or
- From this folder, run `python -m http.server 8000` and visit `http://localhost:8000`.

## Personalise it

Open `index.html` in a text editor and find `PERSONALISATION CONFIG` near the top of the JavaScript. Update the name, birthday date, displayed age, text, wishes, photo captions, image paths, music path, palette, and share text there.

To add photos, put the files in this folder (or in a `photos` subfolder) and change the matching `src` values, e.g. `src: "photos/friends.jpg"`. Leave a `src` empty to keep an illustrated placeholder. To add optional music, put a supported audio file here and set `backgroundMusicFile: "birthday-song.mp3"`. Music never autoplays.

## Publish for free with a shareable public link

1. Open <https://app.netlify.com/drop>.
2. Drag the **entire project folder** (the folder containing `index.html`) or its ZIP onto the page.
3. Copy the generated `*.netlify.app` URL and send it to Vicky and friends.

The site is static, so no build step is needed. If you add photos or music, include those files in the folder/ZIP before publishing. Avoid adding private photos unless everyone pictured is comfortable with them being public.
