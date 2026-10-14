# On the Edge

A Hawkstone bonus game prototype by Baobab. Someone keeps poking your pint: drag the slider to get under the lean and keep it on the bar. Three saves wins.

**Test build, for a small group of testers.**

Everything is in `index.html`. There's no build step, no dependencies and no backend. Settings, best score and the "seen the tutorial" flag are stored in each tester's own browser only. Nothing is collected or sent anywhere.

---

## Walkthrough: putting it online with GitHub Pages

No command line needed. Allow about 10 minutes.

### 1. Sign in
Go to github.com and sign in. If you've forgotten the password, use "Forgot password?" on the sign-in page.

### 2. Create the repository
1. Click **+** (top right) → **New repository**.
2. Repository name: `on-the-edge`.
3. Visibility: **Public**. On a free GitHub plan, Pages only works with public repositories. If you have GitHub Pro or a company plan, Private works too.
4. Leave "Add a README" unticked (this folder already has one).
5. Click **Create repository**.

### 3. Upload the files
1. On the new, empty repository page, click the link **uploading an existing file**.
2. Drag in `index.html` and `README.md` from this folder.
3. Optional: `.nojekyll`. It's a hidden file. On a Mac, press **Cmd + Shift + .** in Finder to show hidden files, then drag it in too. The site works without it.
4. Scroll down and click **Commit changes**.

### 4. Switch on GitHub Pages
1. In the repository, open **Settings** (top bar) → **Pages** (left sidebar).
2. Under "Build and deployment", Source: **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. Wait 1 to 2 minutes, then refresh the page. A box appears saying "Your site is live at…". The address will be `https://YOUR-USERNAME.github.io/on-the-edge/`.
5. If it's not there yet, open the **Actions** tab to watch it build. A green tick means it's live.

### 5. Test it yourself first
- Open the link on your phone in **Safari** (iPhone) or **Chrome** (Android), held upright.
- Tap through the tutorial, then play a round.
- Sound: tap **Pick it up** to start. On iPhone, check the side switch isn't on silent.

### 6. Send it to testers
Send them the link plus a short note, for example:

> Quick game test, takes 2 minutes. Play on your phone, held upright, sound on. Afterwards tell me: did the controls make sense without help, which round you lost on, your best score, and whether anything felt unfair or broken. Also which phone you used.

### 7. Updating the game later
1. In the repository, click **Add file** → **Upload files**.
2. Drag in the new `index.html` (same name, so it replaces the old one) → **Commit changes**.
3. Pages republishes in about a minute. Testers may need to refresh, or close and reopen the tab.

### 8. Taking it down
- **Settings** → **Pages** → **Unpublish site**, or
- **Settings** → **General** → scroll to "Danger Zone" → **Delete this repository**.

---

## For testers: Tuning
The **Tuning** button under the game adjusts start distance, thumb grip, fall speed and wobble strength. Changes apply from the next attempt. **Reset to defaults** puts it back.

## Before going public
- **Font licence:** Gellix is a commercial typeface embedded in `index.html`. A public repository makes it downloadable. Confirm Hawkstone's licence covers web embedding before sharing widely.
- **No 18+ gate** in this test build. The full platform has one.
