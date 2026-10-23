# NoteSmart — free Android-ready starter

## What is included
- Create, edit and delete notes
- Search notes by title, content or category
- Categories, pinning, sorting and dark mode
- Copy a note
- Export/import a JSON backup
- Progressive Web App (PWA) files for installation on Android
- Offline app shell after first visit when served over HTTPS

## Important limitations
This is a first working prototype, not a published Play Store app. Notes are stored locally in the browser on the device. They do not automatically sync between phones, and clearing browser/site data can remove them. Use Export regularly. There is no account system, cloud backup, payments, or income guarantee.

## Test it on a computer
Open `index.html` in a browser. Note-taking features should work; PWA installation/offline caching requires serving the folder over HTTPS (or localhost).

## Put it online for free so Android can install it
1. Create/sign in to a GitHub account.
2. Create a public repository named `notesmart`.
3. Upload the files in this folder to the repository root.
4. In repository Settings → Pages, deploy from the `main` branch and `/ (root)`.
5. Wait for GitHub Pages to provide the HTTPS website address.
6. Open that address in Chrome on your Android phone, then use Chrome's menu → **Install app** or **Add to Home screen**.
7. Test create/edit/search/export and test offline after opening it once online.

GitHub's interface can change; follow its current Pages prompts. Hosting is free under its published limits, but it requires setup and a public repository.

## Next steps before charging users
- Ask 10–20 people to test it and report problems.
- Add privacy information and reliable backup/sync before handling important notes.
- Consider a paid upgrade only after users ask for valuable extras (for example, cross-device sync or secure cloud backup).
- At UGX 5,000/month, 17 paying users for 12 months would generate UGX 1,020,000 gross annual revenue, before fees, taxes, hosting, support, and churn. This is a target, not a forecast.
