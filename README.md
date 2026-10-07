# MED-X Privacy Policy

Last updated: 7 October 2026

MED-X is a browser extension that filters and highlights posts on X, and
changes how X looks and plays media. It runs entirely inside your own browser.

## What MED-X does not do

MED-X has no servers, no accounts and no analytics. It does not transmit
anything about you, your browsing, or the posts you see to the developer or to
any third party. There is nothing to opt out of, because nothing is collected.

## The network requests MED-X makes

MED-X makes requests of its own in two cases only. Both go to X, and neither
carries anything MED-X has added about you.

**To x.com** — with "Show 'Account based in' on profiles" switched on, MED-X
asks X for an account's country when you hover over or open its profile. It is
the same request X's own "About this account" panel makes, sent with your own
session, and the answer is kept in the working cache described below.

**To X's media servers (twimg.com)** — when you fullscreen a picture or a
video with MED-X's button, it loads the full-size version of that picture, or
of the video's cover image, from the same server X loaded the small one from.

No request is made to any other domain.

With full quality video switched on, MED-X changes which of the video
qualities X offers its player will use. The video is still fetched by X's own
player from X's own servers, as it would be anyway.

## What is stored, and where

Everything MED-X stores stays on your device. The one exception is your
settings, which Chrome copies between your own devices if you have sync on.

### In the extension's own storage

**Your settings** — which filters are on, their thresholds, your whitelists,
your highlighted terms, how you have set X to look, and which changelog
entries you have seen. Synced by Chrome across your own devices if you have
extension sync enabled.

**Kept on this device only, never synced:**

- the accounts and quoted posts you have muted, with their expiry;
- your muted words as reported by X, used to apply them to quoted posts, which
  X does not do itself;
- any picture or video you choose as a background;
- a working cache of profile locations, bios and "Account based in" countries
  for accounts that have been on your screen, so the same account doesn't have
  to be re-read while you scroll.

The working cache is pruned automatically, and can be emptied from the
settings page. All of the above is deleted when you remove the extension.

### In x.com's own page storage

Part of MED-X has to run inside the page itself, where it cannot reach the
extension's storage. Two small things are therefore kept in the page's storage
for x.com instead:

- whether full quality video is switched on;
- the address of X's own "About this account" request, with the account's name
  removed, so that the country lookup described above can be repeated.

Neither says anything about you or about the accounts you look at. Because
this storage belongs to x.com, X's own code is able to read both, and both
stay behind when the extension is removed, until you clear x.com's site data
in your browser.

### Never stored

Your X login is never stored. To make the country lookup, MED-X reuses the
authorisation headers the page has already sent. They are held in memory only
and are gone when the tab closes.

### Files you choose to save

"Save settings to a file" writes a file to your own computer holding your
settings, your muted accounts, muted quoted posts and muted words, and your
background pictures if you ask for them to be included. MED-X sends that file
nowhere. It is yours to keep, move or delete.

## How MED-X reads posts

To decide whether to hide a post, MED-X reads the responses X already sends to
your browser when it loads your timeline, along with the text, pictures and
videos on the page. That is how it knows a post's language, how long a video
is, or when an account was created. This inspection happens in your browser as
the page loads. Nothing read this way is sent anywhere, and nothing is
retained beyond the working cache described above.

To check the language of a short post, MED-X hands its text to the language
detector built into Chrome, which runs on your device. Chrome may download
that detector's language model itself the first time it is used. That is the
browser's own download, and MED-X sends no post text with it.

MED-X does not read pages on any site other than x.com and twitter.com.

## Permissions

**storage** — to save your settings and the other items listed under "In the
extension's own storage" above.

**x.com and twitter.com** — MED-X only works on X, and needs access to those
pages to hide, collapse and highlight posts, and to change how the site looks.

## The userscript version

MED-X is also available as a userscript, for browsers other than Chrome. It
behaves the same way and makes the same requests. Its settings and the other
stored items are kept in your userscript manager's storage instead of
Chrome's, so Chrome does not sync them.

## Changes

If this policy changes, the updated version will be published at this address
and the date above will change.

## Contact

Questions about this policy can be sent to: medxtension@gmail.com
