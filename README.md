# iarmailt-docs

The privacy policy and support page for **Iarmailt**, published as web pages
because App Store Connect requires both as *URLs*.

Same arrangement as `bardachd-docs`, `fonn-docs` and `Orain`.

## Why this is a separate repo

The app's own source is not published. A second public repository costs nothing,
and means the only thing ever public is two documents written to be read by
strangers.

## One copy, not two

This folder is the only copy. Edit here, commit here. There is nothing to keep in
step.

## Publishing it

1. Create a **public** repo called `iarmailt-docs` on GitHub.
2. Push this folder to it.
3. Settings > Pages > Source: *Deploy from a branch*, branch `main`, folder
   `/ (root)`. Save.
4. Wait a minute or two, then check both pages load in a private browsing window:

   - `https://glenachulish.github.io/iarmailt-docs/privacy`
   - `https://glenachulish.github.io/iarmailt-docs/support`

5. Put them into App Store Connect: *Privacy Policy URL* on the App Information
   page, *Support URL* (and optionally Marketing URL
   `https://glenachulish.github.io/iarmailt-docs/`) on each version page.
   Then complete the App Privacy questionnaire to match `privacy.md`.

## When the app changes

If Iarmailt starts collecting anything, sending anything new, or asking for a
new permission, `privacy.md` is updated **before** that version ships, and the
date at the top changes.
