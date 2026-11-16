# Lend Manager – Privacy Policy

The public privacy policy for the Lend Manager app by Innodhara (`com.innodhara.lendmanager`), published with GitHub Pages.

- **Page:** `index.html`, a single self-contained page (no build step, no scripts).
- **Public link:** https://hsjagadeesh.github.io/lend-manager-privacy/

That link is used in three places, so keep it stable:
1. Google Play Console → **App content → Privacy policy**, and the store listing.
2. App Store Connect → **App Privacy → Privacy Policy URL** (when the iPhone app is published).
3. Inside the app: `PRIVACY_POLICY_URL` in `LendManager-CrossPlatform/src/app/subscription.tsx`.

## Publish (first time)

1. On GitHub, create a **public** repository named `lend-manager-privacy` (no README, no .gitignore).
2. In this folder:
   ```bash
   git remote add origin https://github.com/hsjagadeesh/lend-manager-privacy.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the page is live at the link above. Open it in a private browser window to check it loads without signing in.

## Update the policy

1. Edit `index.html`, and change the **Effective** date at the top.
2. Commit and push. GitHub Pages republishes within a minute or two.
3. If the app's data handling changed, update the policy **before** releasing that app version, and mention it in the release notes.

## Before publishing

- Replace `[CONTACT EMAIL]` in section 11 with the email users can write to. It is shown publicly.
- `.nojekyll` tells GitHub Pages to serve the files as they are.
