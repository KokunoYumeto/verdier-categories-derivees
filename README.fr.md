# Jean-Louis Verdier, *Des catégories dérivées des catégories abéliennes* (Astérisque 239, 1996)

[English](README.md)

La thèse de Verdier, où sont exposées les catégories triangulées et les catégories dérivées, telle que publiée dans
*Astérisque* 239 (Société Mathématique de France, 1996) : édition établie et annotée par Georges Maltsiniotis, avec
une préface de Luc Illusie. Le corps de la thèse a été laissé inachevé par son auteur, et rien n'y est ajouté ici.
Cette édition donne toutes les pages du volume de 1996 en LaTeX : en français, et en traductions anglaise, chinoise
(simplifiée) et japonaise.

| | |
|---|---|
| [Français (PDF, 244 pages)][fr] | transcription du volume imprimé |
| [Anglais (PDF, 244 pages)][en] | traduction |
| [Chinois simplifié (PDF, 143 pages)][zh] | traduction |
| [Japonais (PDF, 147 pages)][ja] | traduction |
| [Sources LaTeX (ZIP)][zip] | aussi consultables dans ce dépôt |

Compiler le français et l'anglais avec LuaLaTeX, en deux passes (`lualatex fr.tex`, `lualatex en.tex`) ; le chinois
et le japonais avec XeLaTeX dans leurs dossiers sous `translations/` : `main-reader.tex` donne l'édition de lecture
continue, `main.tex` une version mise en page page par page comme le volume imprimé.

## Comment elle a été faite

Transcription et traductions produites par IA (OpenAI Codex, surtout GPT-5.6 Sol, avec des parties par GPT-6 Astra,
tous deux en effort Ultra), août 2026, à partir de la numérisation d'*Astérisque* 239 sur Numdam
([AST_1996__239__R1_0](https://www.numdam.org/item/AST_1996__239__R1_0/)).

## Qualité : un contrôle de plus est nécessaire

Un contrôle ponctuel par Claude (Anthropic), novembre 2026, a comparé les p. 129 et 205 à la numérisation :

- Les mathématiques et les diagrammes sont justes.
- Par endroits, la formulation française s'écarte de l'imprimé : « On peut prendre pour foncteur ℛ le foncteur
  ΨQ₁ » devient « On peut prendre ℛ = ΨQ₁ », et « i.e. » devient « c'est-à-dire ».
- L'anglais est par endroits moins soigné : « degré de m = 0 » devient « m = 0 means that the former morphism has
  degree 0 », ce qui se lit comme si le morphisme lui-même était nul.
- Les traductions chinoise et japonaise n'ont pas été contrôlées.

L'édition demande encore une relecture complète sur la numérisation avant qu'on puisse se fier à sa formulation. D'ici
là, citer le volume imprimé.

## Droits

Les droits sur l'œuvre originale appartiennent à ses auteurs ou à leurs représentants ou ayants droit. Dans la mesure
où nous détenons des droits sur la transcription, la traduction, les corrections et la composition produites par IA,
ils sont dédiés au domaine public sous CC0 1.0. Cette édition est publiée à des fins éducatives et non lucratives, et
nous ne revendiquons aucun droit que nous ne détenons pas. Si vous détenez des droits sur cette œuvre et vous opposez
à sa publication ici, ouvrez une issue GitHub et nous la retirerons.

[fr]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-fr.pdf
[en]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-en.pdf
[zh]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-zh-Hans.pdf
[ja]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-ja.pdf
[zip]: https://github.com/KokunoYumeto/verdier-categories-derivees/releases/download/edition-2026-11-06/verdier-sources.zip
