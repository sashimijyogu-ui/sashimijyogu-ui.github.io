# BOOKS / MANUSCRIPT INDEX (ASCII pointer for search tools)

> This file exists so search tools (Codex, ripgrep, grep, IDE search) can locate
> the manuscripts even when querying in English / romaji. The real files use
> Japanese names. Search keywords: manuscript, genko, honbun, sumaho, sagi,
> sedori, KDP, Kindle.

## Branch note (IMPORTANT)

These manuscripts live ONLY on the branch:

    claude/kindle-unlimited-niche-book-cNOXt

They are NOT on `main`. If a tool reports "manuscript not found", it is almost
certainly checked out to `main`. To get the files locally:

    git fetch origin claude/kindle-unlimited-niche-book-cNOXt
    git checkout claude/kindle-unlimited-niche-book-cNOXt
    # or, to bring it into your current branch:
    git pull origin claude/kindle-unlimited-niche-book-cNOXt

## Manuscript files

### Book 2: "スマホで詐欺に遭わない本 ― シニアが今すぐやるべき7つの設定"
- **Main manuscript (honbun / genko):** `KDP_02_スマホ詐欺/04_本文原稿.md`
- Project folder: `KDP_02_スマホ詐欺/`
  - `00_README.md` – project guide
  - `01_表紙生成プロンプト.md` – cover prompt (PHASE 3)
  - `04_本文原稿.md` – **the manuscript body** (序章〜終章＋用語集＋奥付)
  - `05_KDPメタデータ.md` – KDP metadata (PHASE 5)
  - `06_入稿前チェック.md` – pre-submit checklist (PHASE 6)
  - `07_EPUB変換手順.md` – EPUB conversion (PHASE 4)
  - `08_ローンチ戦略.md` – launch plan (PHASE 7)
  - `09_目次.md` – table of contents for KDP
  - `10_法務チェック.md` – legal/compliance review

### Book 1: "不用品せどり入門"
- Manuscript: `manuscript/不用品せどり入門.md`
- Landing page: `sedori-book.html`
