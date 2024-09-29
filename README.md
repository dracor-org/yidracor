# yidracor
The Yiddish Drama Corpus (YiDraCor) is a repository for TEI editions of Yiddish dramatic texts. Work on the corpus began at the [DraCor Onboarding Workshop for Hebrew and Yiddish](https://www.ada.fu-berlin.de/en/kalender/HeDraCorWorkshop.html), when Sinai Rusinek and Ruthie Abeliovich came to the Freie Universität Berlin. They laid the groundwork for the corpus with their work on the [Dybbuk project](https://www.dybbuk.co/), and their introduction of Transkribus models for Yiddish drama. Since then, [Stephan Schwarz](https://github.com/esteeschwarz) has been a major force in the creation of the corpus, doing corrections for *Yudale der blinder*, and ensuring its correct (and reproducible) encoding into TEI. The corpus is currently edited and maintained by [Jonah Lubin](https://github.com/sreyfe).
## Encoding aspects:
* Page numbers are kept (```<pb n="1"/>```)
* Orthography follows the source text, including vocalization (if needed spelling must be normalized in preprocessing)
* If groups can be reduced to individual members, then they should be encoded as individuals (```<sp who="#person_a #person_b">```), otherwise groups are encoded as groups (```<sp who="#all">```)
4. TEI thinning for elements:
* fw
* pb
* choice (prefer corr and reg) 
