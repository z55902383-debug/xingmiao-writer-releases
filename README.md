**English** | [简体中文](README.zh-CN.md)

<p align="center">
  <img src="public/cat-avatar.png" width="112" height="112" alt="Xingmiao Writer logo">
</p>

<h1 align="center">Xingmiao Writer</h1>

<p align="center"><strong>A local-first fiction workspace for manual writing, AI drafting, story planning and connected reference materials.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-x64-28486b" alt="Windows x64">
  <img src="https://img.shields.io/badge/version-1.0.0-326b62" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/storage-local--first-766540" alt="Local-first storage">
</p>

<p align="center">
  <a href="https://github.com/z55902383-debug/xingmiao-writer-releases/releases/download/v1.0.0/XingmiaoWriter-1.0.0-x64-Setup.exe">Download for Windows</a> ·
  <a href="https://github.com/z55902383-debug/xingmiao-writer-releases/releases/tag/v1.0.0">Release notes</a> ·
  <a href="https://github.com/z55902383-debug/xingmiao-writer-core">Open Core source</a>
</p>

![Xingmiao Writer · current interface with demonstration books](docs/assets/library.png)

**Membership is free.** Full-edition member status manages access to the community prompt library; it is not a paid subscription. Third-party model and image providers may charge separately. Open Core has no account or community modules.

## New in v1.0.0

- **Richer story organization:** knowledge blueprints, place maps, character/item links and parent/child map navigation; separate multi-holder ability profiles with explicit enabled scopes.
- **Connected writing workflows:** categorized memos, manual-writing inspiration references and navigation; review chapter-data synchronization before finalizing, with evidence and duplicate-write checks.
- **More reliable everyday editing:** preserve prose and block navigation after a failed save; retain new-story drafts within the app session; improve dialog focus, keyboard tabs, low-height layouts, theme contrast and startup.
- **One release version:** existing projects, application metadata, installers and release records now use 1.0.0.

Full-edition tools can analyze generated material, preview its destination and add it to a selected book after review. The guided new-book preparation route reuses confirmed story data. **Automatic writing is a configuration and run-page preview:** it can save settings into a real book, but its run page is a timed demonstration. Unattended whole-book generation, background scheduling and crash resume are not implemented.

[1.0.0 guide (中文)](docs/1.0使用指南.md)

## Features

Knowledge blueprints and maps, ability profiles, categorized memos and reviewed chapter synchronization complement the writing workflow.


- **Plan and draft step by step.** Short stories go from an idea to an outline and chapters. Longer works use a whole-book outline, volumes, volume outlines/details, chapter plans and chapter text. Review each result before adopting it into its named destination.
- **Write by hand.** A separate writing pad offers drafts, a focus timer, goals, search and replace, manuscript formatting and history. Side-by-side writing keeps an AI reference snapshot and a separate manual draft.
- **Control AI context.** Select writing styles, requirements, Skills and reference materials for each request. Inspect generation stages and the context actually sent; stop generation and review candidates before replacing saved content.
- **Maintain continuity.** Writing cards, continuity state, selected old-text excerpts, relationships, timelines and source checks support revisions. New books default to the latest 10 finalized chapters; saved settings remain in effect.
- **Organize story data.** Manage characters, world settings, relationships, foreshadowing, memos and canvases. The story-data assistant proposes individually reviewed changes; it does not edit chapter text, chapter outlines, style profiles or memos.
- **Import, export and recover.** Import TXT/Markdown manuscripts, rebuild story data with source-evidence review, export TXT/Markdown, create JSON backups and restore copies. Trash retention is configurable and automatic cleanup is off by default.
- **Personalize the workspace.** English and Simplified Chinese interfaces, light/dark themes, editable writing materials and reusable built-in techniques.

## Full-edition additions

Creative tools, cover-image generation, accounts, the free-member community prompt library and installer updates. Offline editing does not require login. Account and community features depend on the maintainer's backend. Model and image generation require your own service configuration.

Community tools support task tags and complete prompt bodies. Refreshing or adding an item again synchronizes its tags while preserving local edits, enabled state and custom scopes.

## Install and update

Download the Setup.exe and choose an installation directory, including a location on D: if preferred. Before updating, save your work and back up the library. The update wizard starts with the current application location; confirm the directory before installing. Changing the application directory does not automatically move your books.

This repository distributes the Full edition and its documentation. The [MIT-licensed core source](https://github.com/z55902383-debug/xingmiao-writer-core) is maintained separately.

## Data and usage

Books are stored locally. The library location can be changed in Settings and is separate from the installation directory. Back up before updating or moving your library.

AI requests send the selected context to your configured model provider. Review generated text and proposed changes before adopting them. Model and image providers may charge separately.

JSON backups include final story data, chapters and history, Skills and trash. They exclude API keys, account sessions, story-data conversations, proposal undo history and analysis-run history. Restore creates copies.

Desktop checks use isolated test libraries and mock model services; they do not certify real-provider output quality or availability. Windows x64 installers are unsigned.

## Documentation and feedback

[Detailed features (中文)](docs/features.md) · [Verification (中文)](docs/检查记录-v1.0.0.md) · [Story-data guide (中文)](docs/资料整理使用说明.md) · [Writing workflow (中文)](docs/分步创作流程与采用说明.md) · [Upload guide (中文)](docs/GitHub上传步骤.md)

Full-edition add-ons are not open source and are not covered by the core MIT license.

For feedback, include your version and reproduction steps in Issues. Remove credentials, sessions and private manuscript text.
