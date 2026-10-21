# Privacy Policy for YouTube Summarizer

_Last updated: 2026-10-21_

YouTube Summarizer is a Chrome extension that gives you a one-click TL;DR and
timestamped key takeaways for any YouTube video. This policy explains what the
extension does, and does not do, with your data.

## The short version

**No trackers. No analytics. No ad tech. No browsing history.** The extension
does not profile you and never sells or transfers your data to anyone for
marketing. A minimal amount of data moves over the network — only because
generating a summary requires it, and only in the ways listed below.

## What YouTube Summarizer stores on your device

Everything below lives in your browser's per-extension storage
(`chrome.storage.local`) and never leaves it unless explicitly stated:

- **Anonymous install ID** — a random ID for this installation, used to look up
  your Pro entitlement and daily Free Quota.
- **Free Quota counter** — how many summaries you have used today (resets daily).
- **Pro status flag** — whether this installation has an active Pro entitlement.
- **Hourly Rate and Money Saved** (optional) — your self-entered rate and the
  total value of time saved. Entered only if you choose to; stored only on this
  device; never uploaded.

## What it sends over the network

The extension makes requests to exactly three kinds of destinations:

1. **YouTube (www.youtube.com)** — fetches the captions (transcript) of the
   specific video you click "Summarize" on. It does not read or send anything
   else from the page.
2. **Our summary API (summarizer-proxy.jenoughdev.workers.dev)** — sends the
   selected video's captions, its video ID, and your anonymous install ID to
   produce your summary; checks and restores your Pro entitlement; opens the
   Pro checkout. The captions are forwarded to our AI provider to generate the
   summary and are not kept beyond that request.
3. **Paddle (checkout)** — when you buy Pro, the checkout page is operated by
   Paddle, our merchant of record. Your payment details go to Paddle only — the
   extension never sees your card. We receive only the subscription status.
   When you upgrade or use Restore, your purchase email is sent to our API and
   stored with your entitlement record so your subscription can be managed and
   re-installed.

## What it does NOT do

YouTube Summarizer does **not**:

- Track you across sites, or collect browsing history.
- Use analytics, error-reporting, advertising, or fingerprinting services.
- Read or modify pages other than the YouTube watch page it runs on.
- Sell, rent, or share data with third parties for any purpose beyond
  generating your summary (via our AI provider, under our instruction).
- Execute any remotely-hosted code — all JavaScript is bundled in the package.

## Deleting your data

Uninstall the extension at `chrome://extensions`. This removes all of its local
storage. To remove your entitlement record, email jenoughdev@gmail.com with your purchase email.

## Children

YouTube Summarizer is general-purpose and does not knowingly collect personal
information from children — because it does not collect personal information
from anyone beyond what is stated above.

## Changes

Material changes are reflected in the "Last updated" date above and in the
project's commit history.

## Contact

Email **jenoughdev@gmail.com** for any request about this policy or the
extension — including deletion of your entitlement record (include your
purchase email).
