# SourDeck Privacy Policy

Last updated: November 8, 2026

This policy explains how the SourDeck desktop application, developed by Burak Veziran, handles data. SourDeck is an independent client for Ekşi Sözlük; it is not the official Ekşi Sözlük app.

## Where is data processed?

SourDeck has no central server that collects user data. Your reading layout and personal records are processed on your device. To read content and perform the account actions you choose, the app communicates directly with Ekşi Sözlük services. Therefore, “SourDeck has no central server” does not mean that data never leaves your device.

## Information shared with Ekşi Sözlük

- When you sign in, your email address and password are sent to the Ekşi Sözlük service over HTTPS for authentication. Your password is not stored on disk as part of the saved session.
- Content and account requests send session tokens, a client/device identifier, and information related to the topic, search, or account action you requested. The service can also see your IP address through the network connection. Anonymous reading does not mean your identity is hidden on the network.
- When you choose actions involving entries, comments, messages, favorites, votes, follows, or account preferences, the necessary content and action information are sent to Ekşi Sözlük. The visibility of published content is subject to the platform's rules.
- Automatically saving a local draft does not, by itself, send it to Ekşi Sözlük. Online account-draft operations and publishing are separate user actions.

Ekşi Sözlük's own retention, moderation, and data handling practices are not governed by this policy. You should also review that service's current privacy policy and terms of use.

## Information stored on your device

SourDeck stores information such as workspaces, column layouts, reading positions, appearance and filter preferences, cached content, collections, notes, tags, author labels, local drafts, and notification rules on your device. Some records are specific to the selected account; workspace layouts are shared across accounts on the device.

The session tokens and account identifiers needed to restore access to your account are encrypted using AES-256-GCM. The key is kept in a separate file on the same device. This protection does not provide a complete safeguard against someone with access to your device or to both the key and session files. This session encryption does not encrypt the entire collections and drafts database. Protecting your device account and backups is important.

Private messages are processed in memory to operate the messaging screen; they are not automatically saved to SourDeck's local collection archive or data transfer files. Message retention by Ekşi Sözlük is a separate matter.

## External links and images

Opening an external link connects you to the relevant website through your browser. Previewing a supported image sends a request to the server hosting that image; this server may see connection information such as your IP address. The respective websites' own privacy policies apply.

## Analytics, advertising, and notifications

The current version of SourDeck does not include third-party advertising, usage analytics, or automatic remote crash-reporting SDKs. No automatic usage reports are sent to the developer. Operating systems and app stores have their own service and diagnostic practices, which are separate from this policy.

When you allow desktop notifications, they may display topic or content information. If you do not want this information to appear on your screen, you can turn off notifications in the app or operating system settings. Local notification monitoring works while the app is running.

## Export, retention, and deletion

Selected workspaces, collection records, notes, tags, and supported preferences may be written to an export file. These files are not automatically uploaded to a server and are not password-protected backups. If you share a file or save it in a cloud folder, the relevant person or service may be able to access it. Session tokens, passwords, encryption keys, and private messages are excluded from transfer files.

Depending on their type, local records may remain on your device until you delete them or cache management removes them. Removing an account from the app removes its saved session and associated content cache; removal of drafts and collections depends on your on-screen choices. Depending on the operating system, uninstalling the app may not always remove data files or backups. You can request help with the app's data folder and any backups you created if you want to remove all local data.

Deleting a local record does not delete your Ekşi Sözlük account, remotely stored messages, or published content. Use the platform's own account and content management tools for those actions.

## Support and contact

Developer: Burak Veziran. For questions and privacy requests, use the [SourDeck support page](SUPPORT.md). Descriptions you submit through GitHub, your GitHub account information, and attachments you voluntarily provide are processed by GitHub and may be read by the developer for support purposes. Do not include sensitive personal information, passwords, session files, private messages, or your full database in a public issue.

## Changes to this policy

This text and its last-updated date will be revised when data handling changes. The current policy is available on this page.
