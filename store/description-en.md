# Tic Tac Pro — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Hand-drawn tic tac toe vs AI. Easy, Normal and Impossible (full minimax,
unbeatable) difficulties, plus Ultimate mode: nine boards at once and every
move sends your opponent to the matching board.

## Details

- Genre: Board / Puzzle / Casual
- Controls: Mouse / Touch (tap a cell). Fully playable one-handed on mobile.
- Modes: Classic 3×3 and Ultimate (nine stacked boards — win a small board to
  claim it, take three in a row on the big board to win; a full or drawn
  small board means free choice).
- Difficulty: Easy (mostly random), Normal (50% optimal), Impossible
  (complete minimax with alpha-beta pruning — mathematically cannot be beaten;
  a draw is the best you can get).
- Features: hand-drawn X/O stroke animations, winning-line glow, active-board
  highlighting, per-mode per-difficulty win/loss/draw records (localStorage),
  procedural WebAudio sounds with mute toggle, start and result screens.
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, zero external
  assets (no CDN, images or web fonts), works offline once loaded. No
  frameworks, no tracking, no external links.

## Tags
tic tac toe, tictactoe, board, puzzle, casual, ai, minimax, ultimate, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to any screen, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: 16:9 (1280×720) — to add
- [ ] Screenshots: raw captures — to add

## GameDistribution
- Upload tictac-ai-gd.zip (index.html only). SDK v2 auto-loads on
  gamedistribution / gd.games domains; gameplayStart/Stop are wired.

## itch.io
- Upload zip (rename to tictac-pro.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480×680, kind: html
- Pricing: $0 (donations optional)
