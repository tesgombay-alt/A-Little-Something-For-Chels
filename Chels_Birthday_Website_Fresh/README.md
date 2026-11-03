# Chels Birthday Surprise ♡

A small static birthday website made with HTML, CSS and JavaScript. It includes the passcode screen, eight-photo gallery, Liberia-midnight countdown, and birthday letter.

## Open in VS Code
1. Extract this ZIP.
2. Open the `her-birthday-surprise` folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.

## Personal settings
Open `index.html` and find the `Personal settings` section near the bottom:
- `PASSCODE = '2026'` is the year passcode.
- `BIRTHDAY_AT = new Date('2026-11-04T00:00:00Z')` is midnight in Liberia (UTC).

The birthday letter is already included. The photos are in the `assets` folder. To replace a photo, keep the same filename (`memory-01.jpg` through `memory-08.jpg`) or update its matching image path in `index.html`.

## Publish with GitHub Pages
1. Create a new GitHub repository, `Chels-Birthday-Website` (already created).
2. In VS Code, open Terminal → New Terminal in this project folder.
3. Run these commands in the project folder:

```bash
git init
git add .
git commit -m "Create birthday surprise website"
git branch -M main
git remote add origin https://github.com/jonathangombay-pixel/Chels-Birthday-Website.git
git push -u origin main
```

4. On GitHub, open the repository → **Settings** → **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main**, folder **/(root)**, then click **Save**.
7. Wait for GitHub Pages to publish. Your website address will appear in that Pages section.
8. Open the public address on your phone and test the passcode, photos and countdown before making the QR code.

## Important privacy note
The passcode is a fun entrance screen, not strong security. Because this is a static GitHub Pages website, someone with the site files can inspect the code and image files. Do not put private information on the page that you would not want accessible to someone who has the link.
