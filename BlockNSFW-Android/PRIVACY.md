# BlockNSFW — Privacy Policy

**Last updated: July 11, 2026**

## The short version

BlockNSFW is built to protect you, not to profit from you. There are no ads, no
accounts, and no analytics or tracking. Almost everything the app does happens
privately on your device. Information only leaves your phone for the specific
features described below — and even then, nothing that identifies you is collected.

This policy applies to the BlockNSFW Android app.

## What we never do

- No ads and no in-app purchases.
- No account, sign-in, or email required to use the app.
- No analytics, advertising, or tracking SDKs.
- We never sell or share your information.

## What stays on your device

This information is kept only in the app's private storage. It is never sent to us:

- Your blocklist, allow list, and the built-in filter.
- Your streak, check-ins, and the counters shown on the Activity screen.
- Your PIN and recovery code, stored in encrypted form — we cannot see or recover them.
- Your preferences, schedules, and your private "why" note.

It is removed when you clear the app's data in Android settings or uninstall the app.

## What leaves your device (and only for these features)

### Blocklist updates

When the filter updates — automatically or when you tap **Update now** — the app
downloads the latest lists from public sources (GitHub and the jsDelivr CDN). As
with any download, this makes your device's IP address visible to those servers.
No personal information is sent; the app only receives a list of domains.

### DNS lookups (the filter itself)

The app runs a private, on-device VPN that filters DNS — the step that turns a
domain name into an address. Blocked domains are dropped on your phone and never
sent anywhere. Allowed lookups are forwarded to the DNS resolver you choose in
Settings (such as Cloudflare, Cloudflare for Families, or Quad9), optionally
encrypted with DNS-over-HTTPS.

That resolver — not us — handles those lookups under its own privacy policy. We do
not operate a server that sees your browsing, and the VPN is used only for
filtering. Your traffic is never routed through us.

### Community Stories (optional)

Stories is a shared, moderated feed you can read without signing in. If you choose
to post, like, or report a story, the app sends the text you write, an anonymous
random ID created on your device, and your app version.

That random ID is not linked to you, your name, your email, or your Google account.
It only lets the service apply rate limits and let you like or report without
duplicates. Because stories are public, please don't include anything that
identifies you or others. You can ask us to remove a story you posted by emailing us.

## Permissions, and why the app asks

- **VPN** — to filter DNS on your device. It is a local filter, not a tunnel to us.
- **Accessibility** (optional "strong blocking") — watches only the uninstall and
  device-admin screens so protection can't be removed while it's on. It does not
  read, collect, or transmit any other screen content.
- **Device admin** (optional uninstall protection) — adds a deliberate step before
  the app can be removed.
- **Display over other apps** (optional) — to show the calm block screen over a
  blocked app.
- **Notifications** — for the optional daily check-in, block notices, and milestones.
  You choose which.
- **Internet** — for blocklist updates and, if you use it, Community Stories.

## Children

BlockNSFW is a content-filtering tool intended for the owner of the device, or a
parent or guardian setting it up. It is not directed at children and does not
knowingly collect personal information from anyone.

## Keeping and deleting your data

Your on-device data is under your control: clear the app's data in Android settings,
or uninstall the app, to remove it. To remove a story you posted to the community
feed, email us and we'll take it down.

## Changes to this policy

If this policy changes, we'll update the date at the top and the copy here and in
the app. Significant changes will be called out.

## Contact

Questions about privacy? Email **support@monolab.dev**.
