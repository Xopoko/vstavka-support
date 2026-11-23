# Vstavka privacy policy

Publisher **Horoko**

Effective November 23, 2026

Privacy questions: [Vstavka support on GitHub](https://github.com/Xopoko/vstavka-support/issues/new/choose). This is a public channel; do not include private information.

## Clipboard information

Vstavka processes supported clipboard changes so you can view, search and reuse previous items. This can include copied text, links, color values, images, file paths, the time of a copy and available information about the source app, such as its name and icon. Clipboard contents can contain personal or sensitive information.

On macOS versions that offer clipboard controls, you can grant or revoke clipboard access in System Settings. On Windows, choose **Enable history** before Vstavka starts saving. Vstavka saves new changes while it is running. File entries store paths to the original files. Your language, appearance, history and startup preferences are saved locally. On Windows this also includes any sound preferences you set.

## Local storage and security

- On macOS, Vstavka encrypts the history file with AES-256-GCM and stores the key in macOS Keychain. If the key is unavailable, history stays in memory until you quit.
- On Windows, Vstavka saves history and settings in your Windows user profile and encrypts history with the Windows Data Protection API for your account.

Vstavka decrypts items in memory as needed. Someone using your unlocked computer can see items while Vstavka is running.

Vstavka keeps clipboard contents, history, searches and preferences on your device. The app has no accounts, advertising, analytics or cloud sync. Link previews use information already present on the device. Apple handles Mac App Store downloads and updates under [Apple's privacy policy](https://www.apple.com/legal/privacy/). Microsoft handles Microsoft Store downloads and updates under [Microsoft's privacy statement](https://privacy.microsoft.com/privacystatement).

## Your controls

You can pause history saving, exclude source applications, delete individual items, clear history, and change the available retention settings. By default, history retains up to 500 items for 30 days. Pinned items are kept beyond these age and count limits until you unpin or delete them, subject to the app's storage limits.

Vstavka honors supported clipboard privacy markers and its excluded-app list. Pause saving or exclude a source app before copying secrets as ordinary text. On Windows, an optional copy sound may play for an excluded clipboard change. Optional paste sounds recognize paste shortcuts.

Deleting an item or clearing history removes it from Vstavka. Original files, the system clipboard, copies already pasted into other apps and any operating-system backups are managed separately.

## Pasting and support

When you select an item for copying or pasting, Vstavka places it on the system clipboard. The receiving app handles the item when you paste it. In the Mac App Store version, you paste the item with **Command–V**. Versions that offer automatic paste can send the paste shortcut to the previously active app. The macOS preview requires optional Accessibility permission for automatic paste.

Support is provided through public GitHub issues. Submitting an issue requires a GitHub account. The publisher can read the GitHub username, issue text, comments and attachments that you voluntarily submit and use them to respond. These contributions are visible to others on the public repository. Include the app version, your macOS or Windows version and a description using harmless sample data. Leave out clipboard history, passwords, tokens, private documents and screenshots containing personal information.

GitHub hosts the support repository and handles accounts, support-page visits, and submitted content under its own [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). GitHub issues are separate from the Vstavka app: the app does not automatically upload diagnostics or open support requests. If you need a public support contribution corrected or removed, identify the contribution without repeating the sensitive information. Public content may already have been copied by others; removal is not a guarantee that every copy will disappear.

## Changes

The publisher will update this policy and its effective date if the app's data practices change. Questions about this policy can be sent to the privacy contact above.
