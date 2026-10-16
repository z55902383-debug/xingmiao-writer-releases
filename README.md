**English** | [简体中文](README.zh-CN.md)

# Xingmiao Writer · Full Edition Downloads

A local-first fiction workspace for manual writing, AI-assisted drafting and story organization.

**v0.6.13 · Windows x64**

[Download Windows installer](https://github.com/z55902383-debug/xingmiao-writer-releases/releases/download/v0.6.13/XingmiaoWriter-0.6.13-x64-Setup.exe) · [Release notes and files](https://github.com/z55902383-debug/xingmiao-writer-releases/releases/tag/v0.6.13) · [Open Core source](https://github.com/z55902383-debug/xingmiao-writer-core)

**Membership is free.** In the Full edition, member status is a way to manage access to the shared prompt library, rather than a paid subscription. Third-party model and image services may charge separately. Open Core has no account or community modules.

![Xingmiao Writer library with demonstration books](docs/assets/library.png)

The image uses demonstration content. The application also supports an English interface; repository language links only change the documentation.

## New in v0.6.13

- Separate story-reference and writing-style libraries, each with its own multi-selection and blend weights. Writing requirements stay independent.
- Batch source import, individual analysis and reviewed adoption; changed sources block stale analysis. Inspect actual references and candidate snapshots.
- Synchronized blend controls in the main workspace and assistant, clearer filters and details, keyboard adjustments and narrow-window menus.
- Separate instruction and data layers; send complete selected positive-weight profiles. Structured generation validates its format and target, with another check before adoption.

[Story references and style blending guide (中文)](docs/仿写与多风格融合使用说明.md)

## Features

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

[Detailed features (中文)](docs/features.md) · [Verification (中文)](docs/检查记录-v0.6.13.md) · [Story-data guide (中文)](docs/资料整理使用说明.md) · [Writing workflow (中文)](docs/分步创作流程与采用说明.md) · [Upload guide (中文)](docs/GitHub上传步骤.md)

Full-edition add-ons are not open source and are not covered by the core MIT license.

For feedback, include your version and reproduction steps in Issues. Remove credentials, sessions and private manuscript text.
