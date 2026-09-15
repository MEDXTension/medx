# MED-X Privacy Policy

Last updated: 15 September 2026

MED-X is a browser extension that filters and highlights posts on X. It runs
entirely inside your own browser.

## What MED-X does not do

MED-X has no servers, no accounts and no analytics. It does not transmit
anything about you, your browsing, or the posts you see to the developer or to
any third party. There is nothing to opt out of, because nothing is collected.

The only network requests MED-X makes are to x.com, on your behalf and with
your own session, to ask X for information the page already has access to. No
request is made to any other domain.

## What is stored, and where

Everything below is stored locally in your browser through the standard
extension storage API. None of it leaves your device except where your browser
syncs your own Chrome profile between your own devices.

**Your settings** — which filters are on, their thresholds, your whitelists,
your highlighted terms and your muted accounts. Synced by Chrome across your
own devices if you have extension sync enabled.

**A working cache**, held locally only: profile locations and bios for the
accounts on screen, so the same account doesn't have to be re-read while you
scroll; your muted words as reported by X, used to apply them to quoted posts,
which X does not do itself; and the quoted posts and accounts you have muted,
with their expiry.

Caches are pruned automatically and can be cleared at any time by removing the
extension.

## How MED-X reads posts

To decide whether to hide a post, MED-X reads the responses X already sends to
your browser when it loads your timeline, along with the text on the page. That
is how it knows a post's language, how long a video is, or when an account was
created. This inspection happens in your browser as the page loads. Nothing
read this way is sent anywhere, and nothing is retained beyond the working
cache described above.

MED-X does not read pages on any site other than x.com and twitter.com.

## Permissions

**storage** — to save your settings and the caches described above.

**x.com and twitter.com** — MED-X only works on X, and needs access to those
pages to hide, collapse and highlight posts.

## Changes

If this policy changes, the updated version will be published at this address
and the date above will change.

## Contact

Questions about this policy can be sent to: medxtension@gmail.com
