# Privacy

A_PersonalRecords stores the user's records and plugin settings locally in the user's Obsidian vault and Obsidian plugin data.

## Network features

The plugin uses network access only for features that require it:

1. **License activation and verification.** The plugin sends the license information and device identifier required to activate or verify the purchased license. License state is stored locally.
2. **Optional node illustrations.** When the user checks or downloads illustration resources, the plugin requests a version manifest and static PNG resource package from the public `VinVinVin444/A-Personal-Records-Releases` GitHub repository. Vault notes and personal records are not uploaded to GitHub.
3. **Cover downloads.** When the user explicitly downloads a cover from a URL, the plugin requests that URL and saves the returned image into the relevant local record folder.
4. **Search and external links.** Search engines and author profile links open only after the user activates the corresponding control. Their privacy policies apply after leaving Obsidian.

## Telemetry

The plugin does not include client-side behavioral telemetry or advertising. Server-side request logs may be retained by the licensing service, GitHub, or a user-selected external website according to those services' policies.

## Local data

Uninstalling the plugin does not automatically delete the user's Markdown records or downloaded resources from the vault. Users control backup, synchronization, and deletion of their vault data.
