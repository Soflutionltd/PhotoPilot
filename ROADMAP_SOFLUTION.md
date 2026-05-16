# PhotoPilot Roadmap (Soflution)

Roadmap des additions et personnalisations spécifiques à PhotoPilot par rapport à l'upstream RapidRAW.

## Phase 1: Rebranding et fondations (Q2 2026)

- [x] Fork RapidRAW vers PhotoPilot
- [x] Nouveau README Soflution
- [ ] Remplacer le nom RapidRAW par PhotoPilot dans le code (UI, titres, packaging)
- [ ] Nouvelle icône PhotoPilot (cohérente avec MemoryPilot, McpHub)
- [ ] Nouveau bundle ID Tauri: com.soflution.photopilot
- [ ] Nouveau site getphotopilot.com
- [ ] Signature Apple Developer (Team ID TB8CC687M3)
- [ ] Signature Windows (Authenticode)

## Phase 2: Pilot Suite Design System (Q3 2026)

- [ ] Theme unifié avec MemoryPilot, McpHub, RoomPilot
- [ ] Police, couleurs, animations, raccourcis clavier cohérents
- [ ] Component library partagée
- [ ] Sauvegarde croisée de l'état entre apps Pilot

## Phase 3: Intégration AURA (Q3 2026)

- [ ] Connecteur AURA en alternative à ComfyUI
- [ ] Routage des prompts IA vers AURA local (Gemma 26B)
- [ ] Optimisation Apple Silicon via MLX/Velox
- [ ] Inpainting via modèles locaux dans AURA
- [ ] Tagging et description automatique via AURA

## Phase 4: Presets Soflution (Q3 2026)

- [ ] Pack Hospitality (chambres, espaces communs, piscine, vue mer)
- [ ] Pack Mediterranean (Corse, Côte d'Azur)
- [ ] Pack Art Gallery (LaVillArt: tableaux, sculptures, vernissages)
- [ ] Pack Food (restaurants et chefs)
- [ ] Pack Architecture (intérieur et extérieur)
- [ ] Pack Event Night (Les Nuits de la Villa)

## Phase 5: Cloud Sync (Q4 2026)

- [ ] Sync presets via Supabase
- [ ] Sync ratings et tags via Supabase
- [ ] Sync .rrdata via Cloudflare R2
- [ ] Multi-device login via Better Auth
- [ ] Quota par plan (free, pro, enterprise)

## Phase 6: Multi-photographe (Q4 2026 / Q1 2027)

- [ ] Bibliothèques partagées entre photographes
- [ ] Workflow de review (photographe, éditeur, client)
- [ ] Commentaires sur photos
- [ ] Approbation et rejet de batches
- [ ] Permissions granulaires par dossier

## Phase 7: Intégration Pilot Suite (2027)

- [ ] Export direct vers RoomPilot (photos de chambres)
- [ ] Export direct vers ClickStay (photos de séjour)
- [ ] Export direct vers site LaVillArt
- [ ] API Webhook pour automation n8n

## Idées futures

- [ ] Système de plugins
- [ ] Scripting Lua ou JavaScript
- [ ] Mode présentation diaporama
- [ ] Export PDF album avec mise en page auto
- [ ] Tirages photo (Whitewall, Saal Digital)
- [ ] Stockage photos sur blockchain (WWC)
