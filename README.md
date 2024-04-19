# yidracor
Yiddish Drama Corpus
## Encoding aspects:
* Page numbers are kept (```<pb n="1"/>```)
* Orthography follows the source text, including vocalization (if needed spelling must be normalized in preprocessing)
* If groups can be reduced to individual members, then they should be encoded as individuals (```<sp who="#person_a #person_b">```), otherwise groups are encoded as groups (```<sp who="#all">```)
4. TEI thinning for elements:
* fw
* pb
* choice (prefer corr and reg) 