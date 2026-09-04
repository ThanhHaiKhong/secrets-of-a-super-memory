# Secrets of a Super Memory — Wave 1 completion

Book: Eran Katz — *Secrets of a Super Memory* (1999) · VN *Bí mật của một trí nhớ siêu phàm* (Alpha Books & NXB KH&KT, 2022, dịch giả Bùi Như Quỳnh).
Scope: genesis + wave 1 (cover + chapters 1–3). Palette: xanh lá trí tuệ. Storage keys: `memory-reading-mode` / `memory-lang`.
Gate: `book-fidelity-auditor` returned **PASS** (2026-09-04). This file authorises the ✅ rows below.

| Page | book-qa | Scaffold / modes | Faithfulness (không bịa) | Nav state |
|------|---------|------------------|--------------------------|-----------|
| `index.html` | ✅ PASS (`--kind cover`) | VI std/easy + `en-only lang="en"` balanced; keys intact | Hero: record framed, "500 digits" not asserted as fact | 23 rows (8+8+7); ch1–3 live, ch4–23 dim `<span>` (no href); arcs 3/8 · 0/8 · 0/7; mind-map banner `soon`/disabled |
| `chapter-1-self-deception.html` | ✅ PASS (`--kind chapter`) | std/easy/deep + 89 `en-only` (all `lang="en"`) | 500-digit hedged "báo chí thuật lại… [6]" + caveat; corroborated by Rappler [4] | prev→index, next→ch2 |
| `chapter-2-a-new-approach.html` | ✅ PASS (`--kind chapter`) | std/easy/deep + `en-only` balanced | Four pillars cited to book [1] + Rappler [4]; easy-mode stories flagged supplementary | prev→ch1, next→ch3 |
| `chapter-3-the-quiz.html` | ✅ PASS (`--kind chapter`) | std/easy/deep + `en-only` balanced | Quiz described generically — no invented quiz words/numbers; pedagogy cited [1][4][6] | prev→ch2, next→disabled (no dead ch4 link) |

## Site-level
- **Links/anchors:** all internal `.html` hrefs resolve (index, ch1–3); zero links to ch4–23; all in-page `#id` anchors resolve; ch3 `.nav-next` + all ch4–23 cover rows are non-linked spans — no dead links.
- **Citations:** every inline `[N]` resolves to a `<li id="ref-N">`; refs 2–6 carry external `https://` links; ref-1 is the primary book entry (no URL, allowed).
- **Bilingual:** VI (std/easy/deep) + `en-only lang="en"` on every content block; storage keys intact on all 4 pages.
- **Advisory applied:** ch2 four-pillars enumeration now cites `[1][4]` (author's own framework + press corroboration) on all three occurrences.

## References (shared vetted set)
1. Eran Katz, *Secrets of a Super Memory*, Modan Press, 1999 (primary).
2. alphabooks.vn — Bí mật của một trí nhớ siêu phàm (edition/translator/TOC).
3. erankatz.net/about-eran (author; trained, auditory skill — not photographic).
4. Rappler — memory is a learned skill (four pillars, Guinness record).
5. The Korea Times — enthusiasm is key to good memory.
6. Haaretz — how to become a memory whiz (500-digit feat, Roman Room).

## Deferred (later waves)
- Chapters 4–23 (further `book-chapter-author` waves + curator promotions).
- `mind-map.html` (main-session hand-work, once enough chapters exist).
- GitHub remote / push — NOT done; awaiting user confirmation (new public repo is outward-facing).
