# Privacy Policy — TabAutopilot

**Last updated:** September 16, 2026

TabAutopilot (also written **Tab Autopilot**) is a browser extension for **Google Chrome**
and **Mozilla Firefox** that organizes your browser tabs. We take your privacy seriously.
Here's how we handle your data — in plain English.

This policy covers both builds:

- **TabAutopilot for Chrome** — [Chrome Web Store](https://chromewebstore.google.com/detail/nplekjmldglpfcdiechmgahoefhfheom)
- **TabAutopilot for Firefox** — [addons.mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/tabautopilot/)

## The Short Version

We don't collect anything. Everything happens on your device. Your browsing data never
leaves your browser. There is no account, no server, and no analytics in either build.

## What We Access

TabAutopilot reads your **tab URLs and titles** to:

- Group tabs by topic into native tab groups
- Find and close duplicate tabs
- Track which tabs are inactive for hibernation
- Save and restore workspaces

This data is only processed locally inside your browser.

## Categorization & AI Processing

Grouping is driven by a **local rule engine** — a built-in domain table, keyword and title
matching, your own rules and categories, and what it learns from tabs you move by hand.
This engine runs entirely in your browser on both Chrome and Firefox.

**Chrome build:** optionally uses Chrome's built-in **Gemini Nano** model to polish tab
group names. This AI runs entirely on your device — it is part of Chrome itself, not an
external service. No tab data is sent to Google, OpenAI, or any other AI provider. If your
device doesn't support Gemini Nano, the rule engine handles everything.

**Firefox build:** contains **no AI model at all** and makes **no network requests of any
kind** — no fetch, no remote scripts, styles, fonts, or images. It is declared to Mozilla
as `data_collection_permissions: { required: ["none"] }`.

## What We Store

All data is saved locally in your browser using the browser's own extension storage and
IndexedDB:

- Your settings (theme, hibernation timeout, grouping preferences)
- Saved workspaces (tab URLs, group names, colors)
- Tab activity data (when you last used each tab)
- Usage statistics — registrable domains only (`github.com`), never full URLs or page titles
- Any category corrections you make

This data stays on your machine. If you uninstall the extension, it's deleted.

## What We Don't Do

- We **don't** collect personal information
- We **don't** send data to any server
- We **don't** use analytics or tracking
- We **don't** use cookies
- We **don't** show ads
- We **don't** sell or share any data
- We **don't** require an account or sign-up
- We **don't** load any remote code

## Third Parties

We don't share data with anyone. There are no third-party scripts, no analytics services,
no ad networks, in either build.

## Your Control

- Turn usage-stats tracking off at any time in Settings, and clear its history from the dashboard
- Disable AI categorization at any time (Chrome build)
- Export and import your settings from the Settings page
- Choose when to save or restore workspaces
- Delete all stored data by uninstalling the extension

## Permissions

Both builds request only what the features need — `tabs` and `tabGroups` to read and
organize tabs, `storage` for local settings and workspaces, `alarms` for snooze and
hibernation timers, `contextMenus` for the right-click actions, and `browsingData` for the
clear-site-data feature. None of these send anything off your device.

## Changes

If we change this policy, we'll update the date above and note it in the extension's
changelog. We won't suddenly start collecting data — that would go against everything this
extension stands for.

## Contact

Questions about privacy? Reach out:

- GitHub Issues: [github.com/rocke3/TabAutopilot/issues](https://github.com/rocke3/TabAutopilot/issues)
- Email: mail@mdrashid.com
