# 7D7H — Seven Days, Seven Hosts

![7D7H — Seven Days, Seven Hosts](https://raw.githubusercontent.com/Alpharid/ACH/main/web/assets/filiales/7d7h-1.webp)

An anthology of closed-circle mysteries in isometric pixel art. One fatal day is lived seven times, each
time as a different host; the order of the seven hosts is chosen almost blind, then sealed. Each day, the
hosts you already played re-enact exactly what you made them do: a moved object, a door left open, a
distraction carry over from one day to the next. Only you keep what you learned.

This repository is the game's **public distribution channel**: it only carries binaries (launcher and game
packs), published as GitHub Releases. The source code is private.

## The scenarios

- **La Mascherata**: an Italian Renaissance villa, a masquerade, a quarantine. *Playable.*
- **Oddyseus : F.S.T.**: a colony ark hundreds of light-years away, an AI that claims to have forgotten
  everything. *Coming.*
- **Les Maquisards**: an alternate France, 1957, a buried bunker, seven Moles. *Coming.*

## Features

- Assign the seven hosts to the seven days, then seal the order.
- Earlier days re-enacted by the hosts already played; details (codes, hiding places) change from one
  run to the next.
- Journal, conclusions board, dialogues, documents, inventory.
- A free-form notebook kept from one run to the next.
- A failure ending, a truth ending and a secret ending per scenario.

## Status

Work in progress. **PROD 0.1.0**: La Mascherata opens and plays with the full interface; no music or
sound yet, placeholder sets and characters. The **UNSTABLE** build fixes the feedback from the first
test (crash, display at any window size, more readable text, illustrated intro). Bugs are expected:
tell us what bothers you. The game is in French.

## Play

1. Download **[`7D7H-Launcher.exe`](https://github.com/Alpharid/7d7h-builds/releases/tag/launcher)** once
   and keep it. Windows SmartScreen may warn because the exe is not code-signed: *More info* >
   *Run anyway*.
2. Start it, pick **PROD** (stable) or **UNSTABLE** (newest features, may break), then *Play*. The
   launcher downloads and verifies the game and updates itself: it never needs to be re-sent.

## System requirements

- Windows 10/11 64-bit.
- Vulkan capable GPU.

## Releases

| tag | what |
|---|---|
| `launcher` | the launcher (`7D7H-Launcher.exe`, self-updating) |
| `v<version>` | **PROD** builds |
| `unstable-<version>-<commit>` | **UNSTABLE** builds (prereleases) |
| `runtime-<hash>` | the shared game engine binary used by builds (downloaded automatically) |

A subsidiary of [Alpharium](https://alpharid.github.io/ACH/#filiale/7d7h) — α Games division.
