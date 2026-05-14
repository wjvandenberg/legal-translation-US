# `legal-translation-US` — publication-quality legal translation into English, format-preserving and gate-checked

A skill for anyone needing legal documents translated into publication-ready English. Hand it a Word file in any language; get back an English `.docx` with formatting preserved, delivering notably higher quality than e.g. Legora's DeepL tool.

This is the US English default version (even though UK English can be triggered on request). UK English version is available here: https://github.com/wjvandenberg/legal-translation-UK

---

## What it does

Hand the skill a **Word document** (`.docx` or `.doc`) in any language and get back an English `.docx` that opens cleanly in Word, preserves every font, heading, table, footer, comment, footnote, numbering scheme, and signature block, and reads like it was drafted in English by a senior associate.

Translation runs as an eleven-step pipeline with automated quality gates at every junction. You never have to fight Word's XML, hand-place a redline, or re-bold a single defined term.

---

## Why it leads to higher-quality translations

- **Built-in legal vocabulary, by language and field of law.** Curated English legal lexicons (built-in dictionaries) plus per-language sub-lexicons (phrasebooks) for finance, M&A, corporate, IP, IT/SaaS, tax, litigation, employment, and more — supply the right English term every time, consistent across a long agreement.
- **US English by default; UK English on request.** The lexicons cover both variants. Spelling, date format, and the Section-vs-Clause cross-reference convention all flip appropriately at the post-processing stage.
- **Track changes read correctly whether accepted *or* rejected.** Both views flow as clean English — no garbled redlines.
- **Original-language typos don't survive.** Tracked spelling fixes are collapsed, not carried into the English.
- **Full formatting preserved.** Bold defined terms, italics, fonts, tables, footers, and comments all come through unchanged.
- **Non-Latin scripts handled like Latin ones.** Japanese, Chinese, Korean, Cyrillic, Arabic, Hebrew — all read just as cleanly.
- **Definitions reordered alphabetically in English.** A term that sat under "E" in Hungarian ("Elidegenítési tilalom") moves to "P" in English ("Prohibition on transfer"), where the reader expects it.
- **Headers, footers, comments and footnotes translated too.** Agreement titles, page labels, draft/confidentiality watermarks, and comment threads all come out in English.
- **Cross-references repaired and normalised.** "Article" becomes "Section" (US default) or "Clause" (UK), "Annex" becomes "Schedule", and broken Word reference errors are resolved from context.
- **Word-for-word translation mistakes caught automatically.** A scanner checks the English against an avoid-list and flags common literal-translation slips before delivery.
- **Quality gates throughout.** Automated checks run between translation batches and before final packaging — anything that fails blocks delivery.

---

## Languages

The skill can translate from **any language** Claude or other LLM can read — and that is most languages in the world. Quality is consistently high across the board.

For eleven languages we have additionally **built specialised legal lexicons and sub-lexicons** to further strengthen accuracy and consistency. These are the languages where we anticipated the highest volume of legal-document traffic, and where authors of legal content can expect the most polished output:

**Spanish · French · German · Italian · Dutch · Portuguese · Polish · Hungarian · Finnish · Chinese · Japanese**

If your source language is not on this list, the skill still translates it really well too — the general lexicons cover cross-language English conventions for any source. The eleven lexicon languages just get an extra layer of domain-specific polish.

---

## Domains

The skill is **designed for any legal document.** The general lexicons cover the cross-cutting English-legal conventions that apply to every contract, agreement, deed, or filing regardless of subject matter.

On top of that, specialised sub-lexicons strengthen accuracy in: **finance · M&A · corporate · IP · real estate · banking · regulatory · litigation · employment · consumer · transport & insurance · taxes · permitting & environmental · public procurement · NDAs and service agreements · trading & capital markets · SaaS.**

These cover the great majority of legal-document categories in practice. A document outside these domains still translates well — the sub-lexicons only add polish where they apply.

---

## Trade-off

Translation takes minutes rather than seconds, and the skill is larger than simpler translation tools because the dictionaries are bundled in. What you get in return is a publication-ready legal document a reviewer can ship after a sanity pass — not a rough draft requiring a full second round of rewriting.

---

## How to install

The easiest way to install from GitHub:

Click the green Code button at the top right of this repository's landing page.

At the bottom of the dropdown, choose Download ZIP.

Open Claude Desktop → Customize → Skills → click + → Create Plugin → Upload Plugin.

Select the downloaded ZIP file. Claude Desktop handles the wrapper folder automatically.

The skill is ready to use immediately. You can also install via Lawve.ai (https://lawve.ai/en/skills/en-us-legal-translation-wouter-van-den-berg) for the same one-click experience.
