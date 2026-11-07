# Top & Tail privacy policy

_Last updated: 3 November 2026_

Top & Tail is a browser extension for YouTube. It keeps your per-channel rules in your own browser and sends nothing anywhere. This page says what it reads, what it keeps, and where.

## What it reads

On `www.youtube.com` and `m.youtube.com`, and nowhere else, the extension reads the video that's playing from YouTube's player:

- the video's ID, length and channel (ID and name)
- whether it's a live stream, a Short or an ad
- where its end cards start
- the player's speed, volume and loop setting

On a channel's page, when you open the extension's popup there, it reads from the page which channel that is (its ID, name and handle), so you can add that channel.

It uses these in the moment to apply your rules. It doesn't record which videos you watch.

## What it keeps

- **Your rules.** For each channel you add, it keeps the channel's ID and name and the settings you chose: how much to skip, when the outro starts, what happens at the outro, the intro, speed and volume. It also keeps whether the extension is switched on. These live in the browser's synced extension storage.
- **Your own volume.** While a channel's volume is applied, it keeps the volume it replaced, so it can put yours back afterwards. This stays in local extension storage on this device.
- **What it did on the current video**, such as "skipped the last 20 s", so the popup can say so. This stays in the open tab's memory and is gone when the tab moves on or closes.

## Where it goes

Nowhere. The extension makes no network requests, has no analytics, ads or tracking, and doesn't sell, share or transfer anything. The developer never receives your rules or anything about your viewing.

Your browser may sync your rules to your other computers if you've turned sync on (Chrome, Edge) or chosen to sync add-ons in Firefox Sync. That's your browser's own sync, under its own privacy policy. The extension can't see or reach it.

**Backup and restore** writes a file only when you click **Export**, and saves it where you choose. Importing reads only the file you pick.

**Report a problem** in the popup shows a few lines of details for a problem report: the extension's version, the browser and its version, whether skipping is on, and what the extension did or held back on the current video, with your rule's settings for its channel. They never include which video or channel it is. They're put together in the popup when you open it, and go only where you paste them. Its **Open the support page** link opens [github.com/abhinavpm-dev/top-and-tail](https://github.com/abhinavpm-dev/top-and-tail) in a new tab, with nothing added to the address. Whatever you post there is public and falls under GitHub's privacy policy.

## Permissions

- **Storage:** to keep your rules and your own volume, as above.
- **Access to `www.youtube.com` and `m.youtube.com`:** to read the playing video and apply your rules there. The extension doesn't run on any other site.

## Removing your data

Remove a channel with **×** in the popup to delete its rule. Uninstalling removes the extension's data from this browser. To clear synced rules from your other computers too, remove the channels in the popup before you uninstall.

## Changes

If the extension ever starts keeping something new, this page will say so before that version is released, with a new date at the top.

## Contact

abhinavpm.dev+topandtail@gmail.com
