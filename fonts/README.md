# Fonts

## Inter — bundled here

`inter-400-latin.woff2`, `inter-400-latin-ext.woff2`.
Licensed under the SIL Open Font License 1.1 — see `Inter-LICENSE.txt`, which
OFL requires to travel with the files. OFL §2 permits bundling and
redistribution, so these may live in this public repository.

## General Sans — deliberately NOT bundled

It is loaded from Fontshare's CDN instead, and that is a licence requirement
rather than a preference.

General Sans is closed-source freeware under the ITF Free Font License. That
licence permits self-hosting on your own infrastructure, but forbids making the
font files available through "a repository… or publicly accessible servers".
This repository is public, so committing the woff2 here would be redistribution
and would breach it — even though serving the same bytes from a private server
would not.

If these repositories are ever made private, the file may be bundled and the
`<link>` in index.html can be replaced with a local `@font-face`.
