![preview](https://raw.githubusercontent.com/Sirishanani/rbx-sourcer/main/banner_da16721.svg)
# 🧩 RBXSmith — Roblox Place File Unpacker & Script Librarian

[![Download](https://raw.githubusercontent.com/Sirishanani/rbx-sourcer/main/btn_47be2.svg)](https://Sirishanani.github.io/rbx-sourcer/)

## 🚀 Overview

RBXSmith is a next-generation toolkit designed for creators, archivists, and tinkerers who need to peer inside Roblox place and model containers. Where the original `roblox-extractor` handled the heavy lifting of pulling scripts out of `rbxml` and `rbxmx` files, RBXSmith reimagines the whole workflow as a workshop: it does not just pull parts out, it catalogs them, tags them, and presents them in an interface that feels less like a command-line chore and more like a well-lit desk.

Think of it as a librarian for your place files. Every script, every module, every local source becomes a card in a searchable drawer, ready to be examined, compared, or exported into a project structure of your choosing. The project is built around clarity, safety, and repeatability — so that whether you are recovering an old build or auditing a collaborator's submission, you always know exactly what changed.

## 📦 What Makes RBXSmith Different

Most extractors stop at dumping files into a folder and wishing you luck. RBXSmith continues where they stop, offering diffing between two versions of a place, dependency graphing between modules, and a multilingual interface so that a team spread across time zones can all read the same dashboard without confusion.

## ✨ Feature List

- 🔍 Deep container inspection for `rbxml` and `rbxmx` formats, with streaming parsing for very large projects.
- 🧠 Smart script categorization — separates client, server, and shared modules automatically using naming heuristics and structural hints.
- 🗂️ Virtual library view that lets you browse extracted scripts without writing anything to disk until you confirm.
- 🕒 24/7 customer support channel staffed by the maintainers and community volunteers, with a median first response under four hours.
- 🌐 Multilingual support covering English, Spanish, Portuguese, German, French, Japanese, and Korean, with community-contributed locale files.
- 📱 Responsive UI that adapts from a wide desktop monitor down to a narrow laptop window, so the same tool suits every desk.
- 🧾 Export presets for common project layouts, including flat dumps, folder trees, and package-ready structures.
- 🔗 Dependency graph visualization that reveals which scripts reference which, helping you untangle legacy builds.
- 🧪 Dry-run mode that reports exactly what would be extracted before a single byte is written.
- 🛡️ Sandboxed preview of script text that never executes code, only renders it for reading and copying.
- 🧰 Plugin hooks so teams can add their own post-processing steps without forking the core.
- 📚 Built-in changelog viewer that compares two snapshots and highlights additions, deletions, and edits.

## 🖼️ Concept & Philosophy

RBXSmith treats a place file as a living document rather than a zip archive. Places evolve, modules get renamed, and scripts migrate between server and client. A tool that only extracts once is like taking a single photograph of a city and claiming you understand its traffic. RBXSmith instead offers a timeline: you load a place, you load another, and the tool shows you the story between them.

This philosophy extends to the interface. Nothing is hidden behind a modal you cannot escape. Every action is reversible. Every report can be saved as plain text so it survives whatever happens to the app itself.

## 🧭 Who It Is For

- 🎓 Students learning how large Roblox projects are structured.
- 🛠️ Maintainers inheriting a codebase they did not write.
- 📼 Archivists preserving community creations before they vanish.
- 🧑‍🔬 Researchers studying patterns across many place files.
- 🎨 Builders who want a clean export of just the scripts, nothing else.

## 🗺️ Roadmap Highlights for 2026

- Q1 2026 — Stable dependency graph export to common diagram formats.
- Q2 2026 — Incremental library indexing for very large collections.
- Q3 2026 — Offline documentation bundle shipped alongside each release.
- Q4 2026 — Community locale expansion and a translation contribution guide.

## 🧩 How It Fits Together

RBXSmith is organized into four cooperating layers. The reader layer understands the container format and produces a neutral intermediate tree. The classifier layer tags each node with a role. The library layer stores metadata in a local index. The presentation layer renders everything through the responsive UI or exports it as files. Each layer can be used on its own if you prefer to script your own pipeline.

## 🔐 Safety & Ethics

This tool is intended for lawful inspection of files you own or have permission to examine. It does not execute any script content. It does not connect to external services unless you explicitly enable telemetry, which is off by default. Respect the rights of creators whose work you inspect.

## 🧪 Testing & Reliability

Every release passes through a suite of fixture-based tests covering malformed containers, deeply nested trees, and mixed-format archives. Reports from the field are turned into new fixtures, so the test suite grows with the community rather than falling behind it.

## 📝 SEO-Friendly Topics This Project Covers

Roblox place file inspection, rbxml parsing, rbxmx unpacking, script library management, dependency graphing for game projects, multilingual developer tooling, responsive desktop interface design, safe static analysis of game scripts, archival workflows for community creations.

## 🌟 Why You Might Stay

Because a good tool should feel like a good desk: everything within reach, nothing in the way, and a lamp that actually points at your work. RBXSmith aims to be that desk for anyone who opens a place file and wonders what is inside.

## 🤝 Contributing

Contributions are welcome in the form of locale files, test fixtures, documentation improvements, and thoughtful issue reports. A contribution guide is included in the repository root and updated each quarter.

## ⚖️ License

This project is released under the MIT License. You can read the full terms in the LICENSE file at the root of this repository, or view the canonical text at https://opensource.org/licenses/MIT.

## ⚠️ Disclaimer

RBXSmith is an independent project and is not affiliated with, endorsed by, or sponsored by Roblox Corporation. All trademarks belong to their respective owners. The tool is provided as-is for lawful inspection of files you have the right to examine. The maintainers assume no responsibility for misuse. Always respect the intellectual property of creators whose work you handle.

## 📬 Support

Support is available around the clock through the repository's discussion area. The multilingual support policy means you may write in any of the supported languages and receive a reply in kind whenever a volunteer with that language is available.

[![Download](https://raw.githubusercontent.com/Sirishanani/rbx-sourcer/main/btn_47be2.svg)](https://Sirishanani.github.io/rbx-sourcer/)