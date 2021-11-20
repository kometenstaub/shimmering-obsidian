# Shimmering Obsidian 🎩
*An Alfred Workflow with dozens of features for [Obsidian](https://obsidian.md/)*.

![](https://img.shields.io/github/downloads/chrisgrieser/shimmering-obsidian/total?label=Downloads&style=plastic) ![](https://img.shields.io/github/v/release/chrisgrieser/shimmering-obsidian?label=Latest%20Release&style=plastic)

<img src="https://user-images.githubusercontent.com/73286100/139678407-9ac39baa-5f49-42a0-9622-0fbaf68540b2.gif" alt="promo video" width=70%> 

## ⚠️ Breaking Changes
When updating from version 1.x to version 2.x, there are some breaking changes for certain commands. Most importantly, this plugin now requires the [metadata extractor plugin](https://github.com/kometenstaub/metadata-extractor) to run most of its features.

Please refer to [the Breaking Changes Docs](documentation/Breaking%20Changes.md) for more in-detail information.

## Installation & Configuration
- [Installation and Setup](documentation/Installation.md)
- [Workflow Configuration](documentation/Workflow%20Configuration.md)
- [Troubleshooting](documentation/Troubleshooting.md)

## Feature Overview
- *For a full documentation & usage guide, follow the links to the respective subsection.*
- *Features marked with the 🆕 emoji are newly introduced in version 2.0.*
- *Features marked with ✴️ been improved with version 2.0. Refer to the documentation to see what's new.*

### Powerful Alfred-based Quick Switcher
- ✴️ Search Notes
- Open Notes in new pane, append to notes, copy Markdown links, …
- ✴️ Includes Aliases
- 🆕 Search Headings (included heading levels configurable)
- Search Starred Notes
- Search Recent Notes
- ✴️ Browse folders (move to parent folders, create notes in folders)
- 🆕 Search Notes via Tags
- 🆕 Browse a note's links (outgoing, backlinks, external)
- 🆕 Open External Links of a Note (without switching to the document or opening Obsidian)
- 🆕 Graph Traversal via Alfred
- 🆕 Smart Search: A query like `o foobar #moc starred` displays only files named "foobar" with the tag "#moc" that are also starred.

➡️ [Documentation of Quick Switcher Features](documentation/Alfred-based%20Quick%20Switcher.md)

### Utility Features
- OCR Screenshots
- 🆕 Paste URL into selection
- 🆕 Move Note to a different folder
- Create new Notes (based on Template or via QuickAdd)
- Backup your Vault
- Dual Mode (Edit + Preview)
- Conveniently access various folders like `.obsidian` or `.trash`
- 🆕 Daily Notes
- 🐢 Carl Auto-Responses

➡️ [Documentation of all Utility Features](documentation/Utility%20Features.md)

### Plugin & Theme Search
- Search Community Plugins and Themes
- Open in Obsidian or GitHub
- 🆕 Access Plugin Settings
- 🆕 Search & Create GitHub Issues
- 🆕 *No annoyed developers! When the installed version is out of date, issue creation is blocked and replaced by a shortcut to update the plugin instead.*

➡️ [Documentation of the Plugin & Theme Search](documentation/Plugin%20and%20Theme%20Search.md)

### Workspace Switcher
- ✴️ Quickly switch workspaces
- 🆕 Manage workspaces
- 🆕 Automatically toggle spellchecking when switching to certain workspaces

➡️ [Documentation of the Workspace Switcher](documentation/Workspace%20Switcher.md)

### 🆕 Settings Search
- Search & quickly open specific Settings Tabs, the Theme Browser, or the Community Browser.
- Quickly update all plugins.
- Open Plugin Settings.
- Open local plugin folders in `.obsidian/plugins/`

➡️ [Documentation of the Settings Search](documentation/Settings%20Search.md)

### Documentation Search
- Search the Official Obsidian Documentation
- 🆕 Simultaneously search the Obsidian Hub
- Search the Forum

➡️ [Documentation of the Documentation Search](documentation/Documentation%20Search.md)

### Vault Switcher
- Switch the Vault controlled by this Alfred workflow.
- 🆕 Open vaults in Obsidian, Finder, or the Terminal.

➡️ [Documentation of the Vault Switcher](documentation/Vault%20Switcher.md)

### CSS-related Features
- Access themes & CSS Snippets via Alfred
- Create new Snippets from Clipboard content
- 🆕 Quick Access to cheat sheets for theme development, e.g. default variables
- 🆕 Download a theme's CSS file via Theme Search
- Convert a font file base64-encoded CSS

➡️ [Documentation of CSS-related Features](documentation/CSS-related%20Features.md)

### Features for Developers 🆕
- 🆕 Quick Access to cheat sheets for Plugin Development, e.g. the Obsidian API
- ✴️ Quickly open various development-related folders
- 🆕 Open a local plugin's folder in Finder or the Terminal
- 🆕 Quick Copy of a plugin's ID
- Clone a plugin's repository via the Plugin Search
- Open the Vault's root in the default Terminal or in Finder
- Add & Update Beta Plugins via [BRAT](https://github.com/TfTHacker/obsidian42-brat)

➡️ [Documentation of Features for Developers](documentation/Features%20for%20Developers.md)

## Credits

### Thanks
- Big shout-out to @koala for developing the [metadata extractor plugin](https://github.com/kometenstaub/metadata-extractor), for which this workflow is right now the main client.
- Also thanks to [@Vinzent03](https://github.com/Vinzent03) for his invaluable [Advanced URI plugin](https://github.com/Vinzent03/obsidian-advanced-uri), which enables Alfred to control various aspects of Obsidian.
- Main icon by [Jack Liu](https://www.reddit.com/user/jackliu1219), with some additional icons from [Freepik](https://www.freepik.com/).

### Donations 🙏
- [PayPal](https://www.paypal.com/paypalme/ChrisGrieser)
- [Ko-Fi](https://ko-fi.com/pseudometa)

### About the Developer
- This Alfred workflow has been created by @pseudometa#9546 ([Discord](https://discord.gg/veuWUTm)) aka [@pseudo_meta (Twitter)](https://twitter.com/pseudo_meta), aka Chris Grieser (rl).
- In my day job, I am a PhD student in sociology, investigating the governance of the app economy. If you are interested in this subject, feel free to visit [my academic homepage](https://chris-grieser.de/) and get in touch!
