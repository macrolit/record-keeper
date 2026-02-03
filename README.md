# Record Keeper

Advanced CLI tool for Personal Knowledge Management and automation

## What is it?

A modular, highly-configurable, platform-agnostic, extensible, universal yaml-markdown workflow for bulk processing and archival of exportable collections from any source.

## What does it do?

It supports a decentralized info-management workflow by converting any filetype into markdown with yaml frontmatter. 
The project also features optional remote or local (ollama) LLM categorization and enrichment.


"The missing link between website exports, knowledge management tools, categorization and 
AI enrichment - with a CLI-first, plugin-extensible, git-native architecture."


### Similar tools exist, but none combine these features:

**vs. bookmark managers (buku, linkding, shiori):**
- Portable YAML files (not locked in a database)
- Plugin system for extensibility
- AI-powered metadata enrichment

**vs. web clippers (Obsidian clipper, Notion clipper):**
- Works with bulk HTML exports (not one-at-a-time)
- Imports from most-if-not-all file types instead from HTML
- Tool-agnostic (works with Obsidian, Emacs, or plain files)
- Self-contained (no browser extension required)

**vs. archival tools (ArchiveBox, Wallabag):**
- Lightweight metadata focus (not full page archival)
- CLI-first (not web UI)
- Knowledge management integration
- AI enhancements and automated categorisation

**vs. data liberation tools (yt-dlp, gallery-dl):**
- Easy integration with existing repositories
- Parsing, organization and enrichment only (not extraction)
- Multi-platform unified handling

`rk` is the tool for when platforms lack export APIs and you need
your saved content in a format that will outlive social media hosting.


## Features

- Convert and normalize exports into Markdown with YAML frontmatter.
- Bulk-process large archives or collections from any source.
- Enrich and categorize files with local or remote LLM models.
- Integrate cleanly with existing systems like Obsidian, Emacs, and Git-based vaults.
- Automate post-processing with a flexible plugin/module system.

### Module System

record-keeper supports git-managed plugin modules for parsing, processing, automation, and prompts.
Anyone can easily contribute by simply uploading an installable plugin to github.

### Platform Support

The tool will ship with basic support for JSON , CSV , HTML, etc. and specific conversion handlers for data formats such as Google-Takeout, Meta Exports, Bookmarks and some specific website exports.
For conversion methods, handlers or platforms not yet supported; Any individual is free to create a plugin and submit a PR to be added as core utility. 
Documentation is provided as guides for creating modules.

## Workflow

Default: Export > Convert > Parse > Process > Deploy 
Optional: Categorize(AI), Enrich(AI)

## AI

Optional, configuration-oriented, platform-agnostic 

Configurable Remote endpoints
Ollama or other OpenAi-compatible generic apis

## Current Progress

The project is currently in a Closed Beta.
You can request access by becoming a patreon member. 
API endpoints are provided for AI testing.

## Future

- Widespread compatibility
- Extensive support (testing) of newer Ai models
- Exportable datasets
- Platform migration options 
- Automated, isolated Agentic Jobs

