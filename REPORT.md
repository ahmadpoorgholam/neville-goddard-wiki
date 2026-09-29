# Neville Goddard Open-Source / Free Works Crawl Report

**Crawl root:** `/workspace/neville-goddard-crawl/`  
**Generated:** 2026-09-29 02:33 CEST (Europe/Amsterdam)  
**Subject:** Neville Lancelot Goddard (1905–1972), New Thought author (user spelling “Nevil Godard” = same person)

---

## 1. Summary counts

| Metric | Count |
|---|---|
| Canonical books (Wikipedia list) with local `.md` | **14** |
| Extra local book/series `.md` (The Search, Five Lessons) | **2** |
| Total book markdown files | **16** |
| Lecture transcript markdown files | **240** |
| GitHub repos surveyed/cloned | **11** |
| Repos with actual Neville text corpus | **3** (neville-goddard-rag, NevilleGoddardsVault, Neville-s-Vault) |
| Empty / stub / app-only repos | **8** |

**Primary deliverables**

| Path | Role |
|---|---|
| [`INDEX.md`](INDEX.md) | Master index linking every local `.md` |
| [`books/`](books/) | Full-text book markdown |
| [`lectures/`](lectures/) | Full-text lecture markdown |
| [`corpus-books/`](corpus-books/) | Original RAG `.txt` copies |
| [`inventory.csv`](inventory.csv) | One row per work / repo / archive pointer |
| [`repos/`](repos/) | Shallow clones |

---

## 2. Copyright / public-domain note (not legal advice)

Many mirror sites assert that Goddard’s books and lectures are **public domain**. That claim is **not legally certain** for all titles:

- US publications from **1939–1963** generally required copyright renewal in the 28th year; works **not renewed** may be PD in the US, but renewal status must be checked title-by-title (and edition-by-edition).
- Works first published **1964–1977** have different term rules; renewal / notice issues still matter historically.
- **Later DeVorss editions** and titles such as **He Breaks the Shell (1964)** and **Resurrection (1966)** are **more uncertain**. Estate/publisher interest (e.g. Victoria Goddard / DeVorss reprints) has been asserted for some mid-century titles in modern editions.
- Lecture transcripts circulating online often derive from student notes, radio recordings, or collector digitizations; sites may claim copyright in *their* transcriptions/formatting even when the underlying talk was public.
- This crawl **does not claim legal certainty**. Local files are taken from repos/sites that themselves claim free redistribution. Use at your own risk for anything beyond personal study.

KwaminaWhyte corpus README: app is **MIT**; book `.txt` are described as public-domain extracts. Lectures in that repo are **not** git-committed (source sites allegedly reserve rights) — we therefore used **fraterr vault** lecture MD instead.

---

## 3. Canonical books table

| Title | Year | Local path | Best free URL | Notes |
|---|---|---|---|---|
| At Your Command | 1939 | `books/at-your-command.md` | https://readnevillegoddard.com/ |  |
| Your Faith Is Your Fortune | 1941 | `books/your-faith-is-your-fortune.md` | https://readnevillegoddard.com/ |  |
| Freedom for All | 1942 | `books/freedom-for-all.md` | https://readnevillegoddard.com/ |  |
| Feeling Is the Secret | 1944 | `books/feeling-is-the-secret.md` | https://readnevillegoddard.com/ |  |
| Prayer—The Art of Believing | 1946 | `books/prayer-the-art-of-believing.md` | https://readnevillegoddard.com/ | Some sources say 1945; Wikipedia: 1946 |
| Out of This World | 1949 | `books/out-of-this-world.md` | https://readnevillegoddard.com/ |  |
| The Power of Awareness | 1952 | `books/the-power-of-awareness.md` | https://readnevillegoddard.com/ |  |
| The Creative Use of Imagination | 1952 | `books/the-creative-use-of-imagination.md` | https://archive.org/details/NevilleGoddardWorkbooks |  |
| Awakened Imagination | 1954 | `books/awakened-imagination.md` | https://readnevillegoddard.com/ | Corpus file also includes *The Search* |
| Seedtime and Harvest | 1956 | `books/seedtime-and-harvest.md` | https://readnevillegoddard.com/ |  |
| I Know My Father | 1960 | `books/i-know-my-father.md` | https://readnevillegoddard.com/ | Manifest in RAG had year 1930 (error); Wikipedia/DeVorss: 1960 |
| The Law and the Promise | 1961 | `books/the-law-and-the-promise.md` | https://readnevillegoddard.com/ |  |
| He Breaks the Shell | 1964 | `books/he-breaks-the-shell.md` | https://readnevillegoddard.com/ | Later DeVorss — copyright more uncertain |
| Resurrection | 1966 | `books/resurrection.md` | https://readnevillegoddard.com/ | Later DeVorss — copyright more uncertain |

| The Search | ~1946 | `books/the-search.md` | https://nevillegoddardvault.com/ | Short work; also inside awakened-imagination corpus |
| Five Lessons | ~1948 | `books/five-lessons.md` | https://nevillegoddardvault.com/ | Lecture series (vault chapters combined) |

---

## 4. Open-source repos surveyed

| Repo | Contains Neville texts? | License | Local clone |
|---|---|---|---|
| [KwaminaWhyte/neville-goddard-rag](https://github.com/KwaminaWhyte/neville-goddard-rag) | **Yes** — `corpus/` 14 `.txt` books | MIT (app); texts claimed PD | `repos/neville-goddard-rag/` |
| [fraterr/NevilleGoddardsVault](https://github.com/fraterr/NevilleGoddardsVault) | **Yes** — Books/ + Lectures/ markdown (~240 lectures) | No SPDX; README PD claim + takedown note | `repos/NevilleGoddardsVault/` |
| [fraterr/Neville-s-Vault](https://github.com/fraterr/Neville-s-Vault) | **Yes** — HTML books + ~239 lecture HTML | No SPDX | `repos/Neville-s-Vault/` |
| [mr2020/neville-goddard](https://github.com/mr2020/neville-goddard) | Empty | n/a | `repos/neville-goddard/` |
| [mr2020/free-neville-goddard](https://github.com/mr2020/free-neville-goddard) | README stub only | n/a | `repos/free-neville-goddard/` |
| [NXTLVL-Digital/Chat-with-Neville-Goddard](https://github.com/NXTLVL-Digital/Chat-with-Neville-Goddard) | App code only | unknown | `repos/Chat-with-Neville-Goddard/` |
| [kellyclaudeai/neville-meditation-app](https://github.com/kellyclaudeai/neville-meditation-app) | App + technique docs; no full books | MIT | `repos/neville-meditation-app/` |
| [Fkenogo/Reflect-](https://github.com/Fkenogo/Reflect-) | App code | unknown | `repos/Reflect-/` |
| [genidma/AwakenedImagination](https://github.com/genidma/AwakenedImagination) | Small static site | unknown | `repos/AwakenedImagination/` |
| [Sydney584/imagination-station](https://github.com/Sydney584/imagination-station) | React shell | unknown | `repos/imagination-station/` |
| [djun/NevilleGoddardGuide](https://github.com/djun/NevilleGoddardGuide) | Vite guide app | unknown | `repos/NevilleGoddardGuide/` |

**Skipped (per brief):** empty/spam SEO PDF bait repos (`afpd8/au`, `aeits7/ut`, `ajew9/*`) — not cloned.

### Corpus filenames copied (`corpus-books/`)

- `neville-goddard_at-your-command.txt`
- `neville-goddard_awakened-imagination-and-the-search.txt`
- `neville-goddard_creative-use-of-imagination.txt`
- `neville-goddard_feeling-is-the-secret.txt`
- `neville-goddard_freedom-for-all.txt`
- `neville-goddard_he-breaks-the-shell.txt`
- `neville-goddard_i-know-my-father.txt`
- `neville-goddard_law-and-the-promise.txt`
- `neville-goddard_out-of-this-world.txt`
- `neville-goddard_power-of-awareness.txt`
- `neville-goddard_prayer-the-art-of-believing.txt`
- `neville-goddard_resurrection.txt`
- `neville-goddard_seedtime-and-harvest.txt`
- `neville-goddard_your-faith-is-your-fortune.txt`

Converted to markdown under `books/` (see table above).

### Vault lecture filenames

All **240** cleaned `.md` files live in `lectures/` (see INDEX.md). Source originals under `repos/NevilleGoddardsVault/content/Lectures/` (229 general + 11 radio).

---

## 5. Free online archives (titles / URLs / counts only — no bodies dumped)

| Archive | URL | Approx. content |
|---|---|---|
| Read Neville Goddard | https://readnevillegoddard.com/ | ~14 books online + lecture sidebar |
| Neville Goddard Vault | https://nevillegoddardvault.com/ | Books + lectures + radio + guides (live vault) |
| Real Neville text archive | https://realneville.com/text_archive.htm | Large A–Z lecture list (~180+ linked titles on page) + audio sales |
| The Joy Within PDFs | https://thejoywithin.org/authors/neville-goddard/free-pdf-ebook-downloads | ~10 free PDF ebooks (claims PD); more “coming” |
| Imagination and Faith | https://imaginationandfaith.com/neville-goddard-over-300-free-text-lectures-in-pdf-epub-and-kindle-format/ | Claims **300+** text lectures (PDF/EPUB/Kindle) + ~150 audio |
| Cool Wisdom Books | https://coolwisdombooks.com/neville/ | Ongoing Neville archive; index claims **700+** lectures |
| Cool Wisdom lectures index | https://coolwisdombooks.com/neville-lectures-index/ | Chronological/alpha index + historical research |
| Internet Archive — Workbooks | https://archive.org/details/NevilleGoddardWorkbooks | Multi-format book set (1939–1966 era titles) |
| Wikipedia | https://en.wikipedia.org/wiki/Neville_Goddard | Biography + **14-book** bibliography |

**Blockers / fetch notes:** Cool Wisdom index and some IA search HTML were JS-heavy or returned tiny shells via curl; WebFetch timed out on the lectures index. Counts above use site claims + partial parses. Lecture *bodies* for local markdown were taken from the already-cloned vault repo (no need to scrape those sites).

---

## 6. Where files live on disk

```
/workspace/neville-goddard-crawl/
  INDEX.md
  REPORT.md
  inventory.csv
  books/           # 16 full-text book .md
  lectures/        # 240 full-text lecture .md
  corpus-books/    # 14 source .txt from RAG repo
  repos/           # 11 shallow git clones
  archives/        # reserved (unused)
```

---

## 7. Success criteria checklist

- [x] `REPORT.md` complete
- [x] Corpus books copied to `corpus-books/` and converted to `books/*.md` (14 + 2 extras)
- [x] Lecture markdown maximized from free vault source (240 files)
- [x] `INDEX.md` master index
- [x] `inventory.csv` with type/title/source/url_or_path/license_note
- [x] Copyright nuance flagged (no legal certainty claimed)
