# Jean-Louis Verdier, *Des catégories dérivées des catégories abéliennes* (Astérisque 239, 1996)

[Français](README.fr.md) · [简体中文](#简体中文) · [日本語](#日本語)

Verdier's thesis, in which triangulated and derived categories were set out, as published in *Astérisque* 239
(Société Mathématique de France, 1996): edited and annotated by Georges Maltsiniotis, with a preface by Luc Illusie.
The body of the thesis was left unfinished by its author, and nothing is added to it here. This edition gives every
page of the 1996 volume in LaTeX: in French, and in English, Simplified Chinese and Japanese translation.

| | |
|---|---|
| [French (PDF, 244 pages)][fr] | transcription of the printed volume |
| [English (PDF, 244 pages)][en] | translation |
| [Simplified Chinese (PDF, 143 pages)][zh] | translation |
| [Japanese (PDF, 147 pages)][ja] | translation |
| [LaTeX sources (ZIP)][zip] | also browsable in this repository |

Build the French and English readers with LuaLaTeX, two passes (`lualatex fr.tex`, `lualatex en.tex`). Build the
Chinese and Japanese ones with XeLaTeX in their folders under `translations/`: `main-reader.tex` gives the
continuous reader, `main.tex` a version laid out page by page like the printed volume.

## How it was made

AI-transcribed and AI-translated by OpenAI Codex, mainly GPT-5.6 Sol, with parts by GPT-6 Astra, both at Ultra
effort, in August 2026, from the scan of *Astérisque* 239 on Numdam
([AST_1996__239__R1_0](https://www.numdam.org/item/AST_1996__239__R1_0/)).

## Quality: one more check needed

A spot check by Claude (Anthropic), November 2026, compared pp. 129 and 205 with the scan:

- The mathematics and the diagrams are right.
- In places the French wording drifts from the print: "On peut prendre pour foncteur ℛ le foncteur ΨQ₁" is rendered
  "On peut prendre ℛ = ΨQ₁", and "i.e." becomes "c'est-à-dire".
- The English is less careful in places: "degré de m = 0" becomes "m = 0 means that the former morphism has degree
  0", which reads as if the morphism itself were zero.
- The Chinese and Japanese translations have not been spot-checked.

The edition needs one more checking pass against the scan before its wording can be relied on. Until then, cite the
printed volume.

## Rights

The rights in the original work belong to its authors or their representatives or heirs. Where we hold rights, in
the AI-produced transcription, translation, corrections and typesetting, they are dedicated to the public domain
under CC0 1.0. This edition is published for educational, non-profit purposes, and we claim no rights we do not hold.
If you hold rights in this work and object to its publication here, please open a GitHub issue and we will take it
down.

## 简体中文

本仓库收录维尔迪耶（Jean-Louis Verdier）的博士论文《Des catégories dérivées des catégories abéliennes》（Astérisque
239，1996）的简体中文译本（[PDF，143 页][zh]）。译文由人工智能（OpenAI Codex）翻译，尚未经过人工抽查。

## 日本語

このリポジトリには、ヴェルディエ（Jean-Louis Verdier）の学位論文『Des catégories dérivées des catégories
abéliennes』（Astérisque 239、1996年）の日本語訳（[PDF、147ページ][ja]）が含まれています。翻訳は AI（OpenAI
Codex）によるもので、まだ抜き取り検査を行っていません。

[fr]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-fr.pdf
[en]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-en.pdf
[zh]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-zh-Hans.pdf
[ja]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-ja.pdf
[zip]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-sources.zip
