# Record Keeper

Advanced CLI tool for automation of Personal Knowledge Management

## What is it?

A modular, highly-configurable, platform-agnostic, extensible, universal yaml-markdown workflow for bulk processing and decentralized archival of exportable collections from any source.

## What does it do?

- Turn your social media exports into .md notes with flexible properties.
- Integrate seamlessly with RRSS feeds and categorize your highlights
- Avoid Zettelkasten chaos and aglomeration
- File-system based categorization

It supports a flexible info-management workflow by converting individual entries from most filetype contents imports into yaml frontmatter (.md). 
The project also features optional remote or local (ollama) LLM categorization and enrichment.



<img src="https://i.postimg.cc/zfbphsk2/edit14.gif" alt="Demo" width="400">

![Demo](https://raw.githubusercontent.com/macrolit/record-keeper/main/assets/edit14.gif)

https://i.postimg.cc/zfbphsk2/edit14.gif

![Demo](https://raw.githubusercontent.com/macrolit/record-keeper/main/assets/edit14.gif)

https://i.postimg.cc/0j8pVF7t/edit24.gif

[https://i.postimg.cc/zfbphsk2/edit14.gif](https://i.postimg.cc/zfbphsk2/edit14.gif)

![PlayStore](https://i.postimg.cc/0j8pVF7t/edit24.gif)

![Tiktok](https://i.postimg.cc/zfbphsk2/edit14.gif)


<img src="./assets/edit14.gif" alt="Demo of the app's login flow" width="500" height="300">

<img src="https://i.postimg.cc/zfbphsk2/edit14.gif" alt="Demo of the app's login flow" width="500" height="300">


<img src="./assets/edit14.gif"/>

>  "The missing link between website exports, knowledge management tools, categorization and 
>  AI enrichment - with a CLI-first, plugin-extensible, git-native architecture."


![Note Formatting](https://i.postimg.cc/mgd6CNWx/Screenshot-from-2026-02-16-05-26-02.png)

![Note Formatting](https://i.postimg.cc/WpXr29G4/Screenshot-from-2026-02-16-04-26-57.png)

![Note Formatting](https://i.postimg.cc/cHdgWY6M/Screenshot-from-2026-02-16-04-22-58.png)


[![Watch Demo](https://img.shields.io/badge/Watch%20Demo-GIF-blue?style=flat&logo=github)](https://i.postimg.cc/zfbphsk2/edit14.gif)


[![Watch Demo](https://img.shields.io/badge/Watch%20Demo-GIF-blue?style=flat&logo=github)]([https://i.postimg.cc/zfbphsk2/edit14.gif](https://i.postimg.cc/0j8pVF7t/edit24.gif))

[![Watch Demo](https://img.shields.io/badge/Watch%20Demo-GIF-blue?style=flat&logo=github)](https://i.postimg.cc/0j8pVF7t/edit24.gif)


[Watch demo GIF](https://i.postimg.cc/zfbphsk2/edit14.gif)


[Watch demo GIF](https://imgur.com/a/SqnJqMx)
![Watch demo GIF](https://imgur.com/a/SqnJqMx)

## How to use it?

Simply clone the git repo and install it with -e (editable) in an accessible location ()

```sh
git clone https://github.com/macrolit/record-keeper
cd record-keeper
pipx install -e . --python3.11
```
Currently stable using python <3.12

Test the tool

```sh
rk --help
rk ls
rk init ls
```

## Features

- Convert and normalize exports into Markdown with YAML frontmatter.
- Bulk-process large archives or collections from any source.
- Enrich and categorize files with local or remote LLM models.
- Integrate cleanly with markdown-based PKM systems.
- Automate processing with a flexible user-driven plugin/module system.

## Module System

record-keeper supports git-managed plugin modules for parsing, processing, automation, and prompts.
Anyone can easily contribute by simply uploading an installable plugin to github.


## Open Source Models 

==The tool will ship along a dedicated endpoint==
An AI categorization endpoint will be launched along the tool, so that users can quickly try it out!
Tuned infrastructure for large cost-efficient workloads, easy to use and try out with curl commands

It's always opt-in, optional and configurable. You can simply use ollama or your preference of infrastructure

(support for other OpenAi-compatible generic localhost api's soon!)


### Markdown Accent

The project currently supports standard GFM (Git Flavored Markdown) with YAML frontmatter as metadata.
Support for other metadata types may be added in future updates.


### Individual Online Site Support

The tool will ship with general basic support for `JSON , CSV , HTML,` and etc. 
As well as specific conversion handlers for data export formats such as Google-Takeout, Meta Exports, Bookmarks and more.
For new conversion methods, handlers or platforms not yet supported; 
                                          ==Any individual is free to create a dedicated plugin or submit a PR to be added as core utility.==
Documentation is provided as well as guides for creating modules.

### Expand beyond basics

The `rk init <source> <type>` ships an array of category directories. 
You can easily create or remove categories and subcategories manually and these will be valid sources for directory creation as `<source>`.
The prompts can be edited in the `src/rk/prompts/` and directories will be recognized as categories.
You can also create new .yaml files in the `config/sources/` directory or modify existing, these will be added as category context for the LLM prompt.
For personalized LLM processing, you can define custom system messages as well.

Early roadmap development:
(Additional arguments for defining custom temperature, Top-P , Top-K etc.)


# Support the release of the project through donations!

The more you give the more you get

# Self managed, decentraliced activity management

## Keep your footprints

Secure and backup your valued information

Properly track and archive data throughout account migrations

Import and store relevant activity from your online profiles

Essential tool for giving users control over their records

## Browse with Relief

Protect against user policies embracing data loss or account suspension

Avoid reliance on third-party servers that don't care about your data

Backup valuable information stored on infrastructure you don't fully know or trust

## Internet Hygiene

Address, prevent and minimize unnecessary rss recurrence

Teach and rewire platform algorythms about what actually matters

Formalize your activity with curated resources

Cut ties with undesired online behavior

## AI the right way

Filter out noise from your collections

Automate connections in your notes

Elevate RRSS feeds to the next level




# RecordKeeper's Unique Position

## Similar tools exist, but none combine these features:

**vs. bookmark managers (buku, linkding, shiori):**
- Portable YAML files (not locked in a database)
- Plugin system for extensibility
- AI-powered metadata enrichment

**vs. web clippers (Obsidian clipper, Notion clipper):**
- Works with bulk HTML exports (not one-at-a-time)
- Imports from most-if-not-all file types instead from HTML only
- Editor-agnostic (works with Obsidian, Emacs, or plain files)
- Self-contained, deployable (no browser extension required)

**vs. archival tools (ArchiveBox, Wallabag):**
- Lightweight metadata focus (not full page archival)
- CLI-first (not web UI)
- Personal Knowledge management integration
- AI enhancements and automated categorisation

**vs. data liberation tools (yt-dlp, gallery-dl):**
- Easy integration with existing repositories
- Parsing, organization and enrichment only (not extraction)
- Multi-platform unified handling



>  `rk` is the tool for when platforms lack export APIs and you need
>  your saved content in a format that will outlive social media hosting.


# No conversion support for your export type? make your own!

Plugins are very easy to make, 
- Use existing templates 
- Simply follow a guideline
- Vibe-coding ready prompts. just copy-paste
- Package manager `mod` as using `rk mod get username/plugin` with smart git integration

Plugins are dead-simple to make. Please read the PLUGINS.md and simply follow the guide.


Share your plugin in [website still not decided] and help the community grow!


# No export? No problem

IF you can acces YOUR data through a browser, it's completely yours.
Use dev tools and parse HTML with two clicks. No built-in export required.

# For developers

You can review the `cli.py` logic and make adjustments to your preferences or add feature improvements.
Code changes are instant and live, so you don't need to reload or recompile anything.

Make a pull request and will be reviewed ASAP

## File Processing Workflow

Default: Export > Convert > Parse > Process > Deploy 

Optional: Retrieve, Categorize(AI), Enrich(AI)



## Future implementations

- Extensive support (testing) of newer Ai models
- Image-to-text character recognition and sketch/drawing interpretation
- Widespread compatibility
- Exportable datasets
- Platform migration options 

Take a look at the ==ROADMAP.md== for more




# Editor Support Beyond Basic Markdown

Any Markdown-enabled editor should be sufficient for viewing and editing the generated notes.

Nevertheless, some PKMs have more comprehensive toolkits and feature support than others. 
So here is a feature breakdown for the most suitable popular Personal Knowledge Managers; 

| PKM                  | YAML Parsing                         | Image Embeds (HTTP)    | Wiki Links                     | Querying                               | Notes Database                        | Large Vault (>5K) | MD (GFM) Exceptions                  | Notes Display                                                                     |
| -------------------- | ------------------------------------ | ---------------------- | ------------------------------ | -------------------------------------- | ------------------------------------- | ----------------- | ------------------------------------ | --------------------------------------------------------------------------------- |
| **Emacs**            | ✅ Full support                       | ✅ Native GUI images    | ✅ Via plugins                  | ✅ Org-roam/queries                     | ✅ Org-roam DB                         | ✅ Excellent       | ✅ Org-mode to Markdown adaptation    | Live Org-mode to MD rendering                                                     |
| **Obsidian (Bases)** | ✅ Properties UI parsed               | ✅ MD Live              | ✅ `[[ ]]` native               | ✅ Bases(native) or Dataview (SQL-like) | ✅ Bases (views/tables) or Dataview DB | ✅ Excellent       | ✅ Supports OFM + GFM                 | Live MD rendering                                                                 |
| **TiddlyWiki**       | ✅ Importing or Via plugins           | ✅ Using HTML img src   | ✅ `[[ ]]`                      | ✅ Powerful filters/macros              | ✅ Filter language/macros              | ✅ Excellent       | ✅ Converted to Wikitext syntax       | Live WikiText, MD for reading view using plugins                                  |
| **SiYuan**           | ✅ Import/export                      | ✅ Block embeds         | ✅ `[[ ]]` (imported into json) | ✅ Block queries                        | ✅ Block-based DB                      | ✅ Good            | ✅ All MD converted into Block syntax | Live block editor. No MD                                                          |
| **SilverBullet**     | ✅ Index queries                      | ✅ MD Live preview      | ✅ `[[ ]]`                      | ✅ `^` queries native                   | ✅ Full-text index                     | ✅ Excellent       | ✅ None                               | Live MD rendering per-line                                                        |
| **Neovim**           | ✅ LSP parsing, obsidian.nvim support | ✅ Via Plugins          | ✅ Via plugins                  | ✅ Telescope queries                    | ✅ Neorg workspace                     | ✅ Excellent       | ✅ Neorg syntax adaptation            | Live LSP<br>//<br>Browser sync <br>//<br>Live TUI  emulator overlay using plugins |
| **VSCode**           | ✅ Front-matter extension             | ✅ Preview Via Plugins  | ✅ Foam `[[ ]]`                 | ✅ Dendron queries                      | ✅ Dendron schema                      | ✅ Good            | ✅ None                               | No inline rendering. Preview MD via command                                       |
| **QOwnNotes**        | ✅ Tags/metadata                      | ✅ MD Live preview      | ⚠️ Custom links                | 🟡 Tag search only                     | ❌ Folder-based                        | ✅ Great           | ✅ None                               | Live preview pane                                                                 |
| **Logseq**           | ❌ Block properties only              | ✅ Block embeds         | ✅ `[[ ]]` blocks               | ✅ Live queries                         | ✅ Block DB                            | ⚠️ Slow           | ✅ GFM + Syntax Variations            | Live syntax highlight.<br>Requires switching for preview                          |
| **Zettlr**           | ⚠️ Preserves text only               | ✅ MD Live preview      | ❌ Pandoc links                 | ❌ Basic search                         | ❌ Project mgmt                        | ✅ Great           | ✅ GFM + Pandoc extensions            | Live preview pane                                                                 |
| **Trilium**          | ❌ Attributes only                    | ❌ Local images Only    | ✅ `[[ ]]`                      | ✅ JS relation queries                  | ✅ Full relation DB                    | ✅ Good            | ✅ GFM + HTML variations              | Live MD rendering                                                                 |
| **Sublime Text**     | ✅ YAML package                       | ✅ Plugins for previews | ❌ Plain text                   | ❌ None                                 | ❌ Project folders                     | ✅ Great           | ✅ Indifferent                        | Raw source mode. Plugins for previews                                             |
| **Typora**           | ⚠️ Preserves/reads                   | ✅ Live MD              | ❌ Plain text                   | ❌ None                                 | ❌ Folders only                        | ✅ Good            | ✅ Yes GFM + extensions               | Live MD rendering                                                                 |
| **MarkText**         | ⚠️ Preserves text only               | ✅ MD Live preview      | ❌ Plain text                   | ❌ None                                 | ❌ Folders                             | ✅ Great           | ✅ None                               | Live preview pane                                                                 |
| **Zim**              | ⚠️ Preserves text only               | ❌ No preview           | ❌ Wiki                         | ❌ Basic text search                    | ❌ Folder of .txt files                | ✅ Great           | ❌ Wiki. Lacking import capability    | Raw source mode. No MD                                                            |



## Advanced functionality for graphical setups
For users wanting more elaborate metadata utilization, such as Visual Library / Query Table Previews (like shown in the demo) here is a detailed breakdown; 

| PKM                  | Display Method                    | Metadata support for Queries                                                             | Lists + Thumbnails Linking                                                                          | Implementation Notes                                                                                                                  |
| -------------------- | --------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Obsidian (Bases)** | ✅ Local image links or URL embeds | ✅ Native                                                                             | ✅ Full out-of-the-box(title/tags → Bases views)                                                     | Bases queries `title: "X" AND tags: "#work"` → thumbnail grid                                                                         |
| **Emacs GUI**        | ✅ `image-dired` + packages        | ✅ Native                                                                             | ✅ org-roam + dired thumbnails + query                                                               | `consult-org-roam` + `image-dired` → YAML tags → image gallery                                                                        |
| **TiddlyWiki**           | ✅ HTML tags for URL embeds        | ✅ Imports to native fields, else YAML<br>plugins parse to tiddler fields.            | ✅ Via filters, gallery plugins show thumbnails from covers                                          | **Filter** queries tiddlers → Template renders each as card → CSS Grid/Flexbox: done.<br>(Alternatively just use **Gallery plugins**) |
| **SiYuan**           | ✅ Image Block Embeds              | 🟡 Import/export workflow → Internal attributes                                      | ✅ Queries → Block properties → cards                                                                | Cards (formerly gallery) shows block content and images                                                                               |
| **Neovim+Kitty**     | 🟡 Plugins + Kitty protocol setup | 🟡 obsidian.nvim or other dedicated parsing                                          | 🟡 Rich telescope previews + yaml frontmatter parsers + queried tables + managing Kitty constraints | Technically possible but demanding (plugin combinations may achieve this)                                                             |
| **Logseq**           | ✅ Local + URL Image Embeds        | ⚠️ Only block properties supported (manual conversion)                               | ✅ Property queries → custom CSS view → Card Queries                                                 | `{{query (property status in-progress)}}` → CSS panel → visual blocks/lists                                                           |
| **Trilium**          | ✅ Local image links               | ⚠️ Attributes format only (manual conversion needed)                                 | ✅ Built‑in list → thumbnail‑style via extension                                                     | Tree shows content → YAML to attributes conversion →  thumbnail‑style via extension "Collection Views"                                |
| **QOwnNotes**        | ✅ Local image links               | ✅ YAML → Tags/metadata                                                               | ❌ Tag search → list → workarounds → local image file lists only                                     | Local thumbnails via file manager + tag search integration. No true visual display or queries.                                        |
| **VSCode+Dendron**   | ✅ Dendron images                  | 🟡 Front-matter extension → internal metadata                                        | ❌ No current Dendron integration                                                                    | Requires creating a custom blocked querying plugin +<br>Another Dendron plugin integration for preview buffers                        |
| **SilverBullet**     | ✅ Local + URL Image Embeds        | ✅ Fully Natively                                                                     | ❌ Index queries + Text list, no thumbnails                                                          | `list from #work where status = "done"`                                                                                               |
| **Zettlr**           | ✅ Local image files or URL embeds | ✅ Native Yaml frontmatter handling → Pandoc metadata                                 | ❌ File list filtering, no thumbnails                                                                | Project manager only shows YAML-tagged files                                                                                          |
| **Sublime Text**     | ✅ With plugins + config           | ✅ YAML package                                                                       | ❌ Basic find                                                                                        | Sidebar only                                                                                                                          |
| **MarkText**         | ✅ Local or URL embeds             | ⚠️ Only preserves text                                                               | ❌ Simple text search                                                                                | File explorer only                                                                                                                    |
| **Typora**           | ✅ Local or URL embeds             | ⚠️ Only preserves text                                                               | ❌ Metadata filtering only                                                                           | File list only                                                                                                                        |
| **Zim**                  | ✅ Yes, displayed in preview pane  | ❌ No editor parsing/import. Native metadata: page properties in `key:: value` format | ❌ Basic text search                                                                                 | File list only                                                                                                                        |



# Release Date

Anytime before Q3 2026




