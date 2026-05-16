# Cursor Global Prompt: PhotoPilot

## Project Context

PhotoPilot is a Soflution-branded photo editor based on RapidRAW.

Stack:
- Rust 2024 (backend, image pipeline)
- WGPU + WGSL (GPU rendering)
- React + TypeScript + Vite (frontend)
- Tauri v2 (desktop wrapper)
- ONNX Runtime v2 (AI inference)
- rawler (RAW decoding)
- Lensfun (lens correction)

## Coding Rules

- No em dashes, no en dashes, anywhere. Use commas, parentheses, or separate sentences.
- Numbers as digits, never spelled out.
- No bullet-heavy responses, prefer prose.
- Always execute commands directly, never ask the user to run them manually.
- All work happens locally in /Users/antoinepinelli/Cursor/App/PhotoPilot/
- All commits use clear, present-tense English commit messages.

## Branding Rules

When renaming RapidRAW to PhotoPilot:
- Keep all legal attribution to Timon Käch and the original RapidRAW project in code comments, LICENSE, and credits.
- Keep AGPL-3.0 license intact.
- Replace user-facing strings (window title, menu items, About dialog, package metadata) from "RapidRAW" to "PhotoPilot".
- Update Tauri bundle identifier to com.soflution.photopilot.
- Update package.json name to photopilot.
- Update Cargo.toml package name to photopilot.

## File Layout

- src/: React + TypeScript frontend
- src-tauri/: Rust backend, including WGSL shaders
- data/: AI models and lens correction data
- packaging/: distribution files (icons, manifests)
- public/: static frontend assets

## Build Commands

- npm install: install JS dependencies
- npm start: dev mode (Tauri + Vite)
- npm run build: production build
- npm run tauri build: produce distributable

## Soflution Roadmap

See ROADMAP_SOFLUTION.md for the Soflution-specific feature roadmap.

Priority for the next sessions:
1. Rebranding: rename all user-facing strings, update icon, update bundle ID
2. Pilot Suite design tokens: align colors and typography with MemoryPilot/McpHub
3. AURA connector: wire generative AI to local AURA instance instead of ComfyUI

## Reference Repositories

- Upstream: https://github.com/CyberTimon/RapidRAW
- Soflution fork: https://github.com/Soflutionltd/PhotoPilot (new clean repo, no fork relationship)
- Sister Pilot apps: MemoryPilot, McpHub, RoomPilot, ClickStay
