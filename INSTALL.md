# Scan Log: put it on your phone

You need two things: the app (this zip) and a free Gemini key.

## 1. Get your free Gemini key (2 minutes, on your phone)
1. Open aistudio.google.com and sign in with a Google account.
2. Tap **Get API key**, create a key, copy it.
3. Keep it private. Don't send it to anyone or put it in any file.

Free keys have usage limits, and as far as I know Google may use free-tier content to improve its products. Your face photos are sent to Google for every scan. If that bothers you, use a paid key with a spending cap instead.

## 2. Put the app online once (free), then add it to your home screen
The app is plain files. It must be opened from a web address (https) to install and save data reliably. Pick one:

**Netlify Drop (no code)**: unzip the file on any computer, open app.netlify.com/drop, drag the whole folder onto the page. You get a link. Sign in free to keep the site permanently.

**GitHub Pages**: make a free GitHub account, create a new public repository, upload all the unzipped files, then Settings, Pages, deploy from the main branch. Your link is shown there.

The files contain no secrets. Anyone who finds the link sees an empty app, never your key, photos or scores, because those live only in your phone's browser.

On your phone, open the link in Chrome, tap the three-dot menu, then **Install app** or **Add to Home screen**.

## 3. First run
1. Open the app, tap the settings icon, paste your key, tap **Save and check key**. It should say "Key works" and pick a model.
2. Go to Scan, take a selfie facing a window, tap **Analyse photo**. It takes 10 to 20 seconds.

## Good to know
- **Everything is stored on your phone only.** Clearing Chrome's site data or removing the app can erase it. Use Settings, **Export my data**, now and then.
- **Quick trial without hosting:** you can open `index.html` from your phone's Files app in Chrome. Then open Settings. If it says "Saved on this phone", it works. If it says the browser is not letting the app save, use a hosted link instead.
- If a scan says you hit the free limit, wait a minute or try tomorrow.
- Cosmetic scores are an opinion about one photo, not medical advice.
