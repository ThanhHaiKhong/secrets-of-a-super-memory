# Secrets of a Super Memory — completion log

Book: Eran Katz — *Secrets of a Super Memory* (1999) · VN *Bí mật của một trí nhớ siêu phàm* (Alpha Books & NXB KH&KT, 2022, dịch giả Bùi Như Quỳnh).
Palette: xanh lá trí tuệ. Storage keys: `memory-reading-mode` / `memory-lang`. Three VI reading modes (Dễ hiểu / Tóm tắt / Đầy đủ) + EN layer.
Gate: `book-fidelity-auditor` **PASS** (2026-09-04, whole-site after Cụm 2 wave). This file authorises the ✅ rows.

## Status: Cụm 1 + Cụm 2 complete — cover + chapters 1–16

### Cover
| Page | book-qa | State | Nav |
|------|---------|-------|-----|
| `index.html` | ✅ PASS (cover) | 23 rows = 16 live + 7 dim; arcs 8/8 · 8/8 · 0/7; mind-map banner disabled | ch1–16 live, ch17–23 no-href |

### Cụm 1 (Ghi nhớ hiệu quả) — ch1–8
| Page | book-qa | Faithfulness (không bịa) | Nav |
|------|---------|--------------------------|-----|
| `chapter-1-self-deception.html` | ✅ PASS¹ | 500-digit/Guinness [4][6], confirmed vs Rappler; ref-1 = book | index ⇄ ch2 |
| `chapter-2-a-new-approach.html` | ✅ PASS | Four pillars → book [1] + Rappler [4]; easy examples flagged | ch1 ⇄ ch3 |
| `chapter-3-the-quiz.html` | ✅ PASS | Quiz contents generic; flagged companion-added | ch2 ⇄ ch4 |
| `chapter-4-hello-ron-don.html` | ✅ PASS | Next-in-line effect [7]; Katz record [4]; names flagged | ch3 ⇄ ch5 |
| `chapter-5-this-reminds-me-of.html` | ✅ PASS | Mnemonic/association [7]; examples flagged | ch4 ⇄ ch6 |
| `chapter-6-the-woman-in-golden-shoes.html` | ✅ PASS | Vivid-image mnemonic [7]; golden-shoes flagged | ch5 ⇄ ch7 |
| `chapter-7-cat-and-gory-category.html` | ✅ PASS | Substitute-word [7]; splits flagged | ch6 ⇄ ch8 |
| `chapter-8-the-roman-room.html` | ✅ PASS | Method of loci / Simonides [7]; Katz's use [6]; rooms flagged | ch7 ⇄ ch9 |

### Cụm 2 (Ghi nhớ thông minh) — ch9–16
| Page | book-qa | Faithfulness (không bịa) | Nav |
|------|---------|--------------------------|-----|
| `chapter-9-papers-tasks-order.html` | ✅ PASS | Absent-mindedness [7]; ordering examples flagged | ch8 ⇄ ch10 |
| `chapter-10-where-are-the-keys.html` | ✅ PASS | Attention/absent-mindedness [7]; key example flagged | ch9 ⇄ ch11 |
| `chapter-11-remembering-numbers.html` | ✅ PASS | Major system [7]; "395" illustrative (flagged) | ch10 ⇄ ch12 |
| `chapter-12-your-perfect-phone-book.html` | ✅ PASS | Major system [7]; phone entries flagged | ch11 ⇄ ch13 |
| `chapter-13-from-louisiana-to-napoleon.html` | ✅ PASS | Linking method [2][4]; Louisiana→Napoleon companion example | ch12 ⇄ ch14 |
| `chapter-14-memory-for-study-and-exams.html` | ✅ PASS | Spaced repetition [7]; study examples flagged | ch13 ⇄ ch15 |
| `chapter-15-memory-for-presentations.html` | ✅ PASS | Method of loci [7]; talk outline flagged | ch14 ⇄ ch16 |
| `chapter-16-memory-for-languages.html` | ✅ PASS | Substitute-word / keyword method [1][7]; word pairs flagged | ch15 → ch17 disabled |

¹ ch1's lone book-qa flag is a self-comparison artifact (ch1 is its own template); re-run vs ch2 → ALL CHECKS PASS. Not a defect.

## Site-level
- **book-qa:** 17/17 PASS (ch1 self-comparison artifact only).
- **Links/anchors:** every internal `.html` href + `#anchor` resolves; chain index → ch1 ⇄ … ⇄ ch16 → (ch17 disabled); zero dead links, zero dangling anchors; no live link points at ch17–23.
- **Citations:** every inline `[N]` resolves to `<li id="ref-N">`; ref-1 = primary book (no URL, accepted), ref-2…7 external. External URLs verified reachable (Rappler confirms the 500-digit/Guinness feat; Haaretz ref-6 paywalled to WebFetch but same fact independently confirmed by Rappler; Wikipedia technique pages support their claims).
- **Bilingual/modes:** VI (std/easy/deep) + `en-only lang="en"` balanced on all 17 pages; 0 missing `lang="en"`; storage keys intact.
- **Reading modes:** Tóm tắt vs Đầy đủ differ (~+52% content in Đầy đủ via deep-only blocks); engine correct, kept as designed.
- **Curator region:** Cụm 2 integration touched only `index.html` (cover roster) + `chapter-8` NAV fences — 0 style/script/prose leak.

## References (shared vetted set)
1. Eran Katz, *Secrets of a Super Memory*, Modan Press, 1999 (primary, print).
2. alphabooks.vn — Bí mật của một trí nhớ siêu phàm (edition/translator/TOC).
3. erankatz.net/about-eran (author; trained, auditory skill).
4. Rappler — memory is a learned skill (four pillars, 500-digit/Guinness record).
5. The Korea Times — enthusiasm is key to good memory.
6. Haaretz — how to become a memory whiz (500-digit feat, Roman Room).
7. Wikipedia — Next-in-line effect / Mnemonic / Method of loci / Major system / Spaced repetition / Absent-mindedness (per-chapter, technique-level).

## Deferred (later waves)
- Cụm 3 (ch17–23) — further `book-chapter-author` wave + curator promotion.
- `mind-map.html` (main-session hand-work, once all chapters exist).
