# Synkrisis

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23127836.svg)](https://doi.org/10.5281/zenodo.23127836)

Εργαλείο συγκριτικής αξιολόγησης μεταφραστικών εκδοχών στον browser: κατάτμηση, παραλληλοποίηση και αντιπαραβολή πολλών εκδοχών του ίδιου κειμένου ως προς ένα κείμενο-βάση, με περιγραφικό (van Leuven-Zwart) και αξιολογικό (MQM) σχολιασμό. Κάθε κατηγορία σχολιασμού συνοδεύεται από ορισμό. Ένα αυτόνομο αρχείο HTML, χωρίς εγκατάσταση και χωρίς εξωτερικές εξαρτήσεις. Τα κείμενα υποβάλλονται σε τοπική επεξεργασία και δεν αποθηκεύονται.

A browser-based tool for the comparative evaluation of translation versions: segmentation, alignment and collation of multiple versions of the same text against a base text, with descriptive (van Leuven-Zwart) and evaluative (MQM) annotation. Every annotation category comes with a definition. A single self-contained HTML file, with no installation and no external dependencies; texts are processed locally and are not stored.

**Live:** https://elenitziafa.com/synkrisis.html

## Περιεχόμενα / Contents

- `synkrisis.html`: το εργαλείο / the tool
- `examples/daudet-la-mule-du-pape.json`: σχολιασμένη συνεδρία (Daudet, «La mule du Pape», πέντε εκδοχές μηχανικής μετάφρασης). Ανοίγει με «Φόρτωση συνεδρίας» / annotated session (Daudet, "La mule du Pape", five machine translation outputs); open it with "Load session"

## Πλαίσιο και πηγές / Framework and sources

Η περιγραφική διάσταση βασίζεται σε προσαρμοσμένο υποσύνολο του μοντέλου μεταφραστικών μετατοπίσεων της van Leuven-Zwart και η αξιολογική σε επιλεγμένους τύπους σφάλματος της τυπολογίας MQM Core. Οι αποκλίσεις από τα δύο πλαίσια και οι ορισμοί όλων των κατηγοριών βρίσκονται στα πτυσσόμενα πεδία «Πλαίσιο και πηγές» και «Ορισμοί κατηγοριών» του εργαλείου, κάτω από τις «Οδηγίες χρήσης». / The descriptive dimension is based on an adapted subset of van Leuven-Zwart's model of translation shifts, and the evaluative dimension on selected error types of the MQM Core typology. Departures from the two frameworks and the definitions of all categories are given in the tool's collapsible fields "Framework and sources" and "Category definitions", below "How to use".

- Baker, M. (1996). Corpus-based translation studies: The challenges that lie ahead. In H. Somers (Ed.), *Terminology, LSP and Translation: Studies in language engineering in honour of Juan C. Sager* (pp. 175–186). John Benjamins. https://doi.org/10.1075/btl.18
- Lommel, A., Uszkoreit, H. & Burchardt, A. (2014). Multidimensional Quality Metrics (MQM): A framework for declaring and describing translation quality metrics. *Tradumàtica*, 12, 455–463. https://doi.org/10.5565/rev/tradumatica.77
- MQM Council. The MQM Core Typology. https://www.themqm.org/mqm-pillars/the-mqm-core-typology/
- van Leuven-Zwart, K. M. (1989). Translation and original: Similarities and dissimilarities, I. *Target*, 1(2). https://doi.org/10.1075/target.1.2.03leu
- van Leuven-Zwart, K. M. (1990). Translation and original: Similarities and dissimilarities, II. *Target*, 2(1). https://doi.org/10.1075/target.2.1.05leu

Οι ορισμοί των αξιολογικών κατηγοριών αποδίδουν, σε μετάφραση και συντόμευση, τους ορισμούς της τυπολογίας MQM Core (The MQM Council, themqm.org, άδεια CC BY 4.0). / The definitions of the evaluative categories are abridged paraphrases of those in the MQM Core typology (The MQM Council, themqm.org, CC BY 4.0 licence).

## Εκδόσεις / Versions

- **1.1.0** (2026): Ορισμοί για όλες τις κατηγορίες, στον επιλογέα και σε γλωσσάρι. Νέα εξαγωγή σχολιασμών σε πίνακα 0/1 με σταθερά κλειδιά. Καταγραφή της έκδοσης του εργαλείου και του σχήματος σχολιασμού στη συνεδρία και στα αρχεία CSV. Ακριβέστερη περιγραφή της σχέσης με το μοντέλο της van Leuven-Zwart και με το MQM Core. Οι κατηγορίες και τα κλειδιά τους δεν άλλαξαν. Οι συνεδρίες της 1.0.0 ανοίγουν χωρίς μετατροπή. / definitions for all categories, in the picker and in a glossary; new export of annotations as a 0/1 table with stable keys; tool and annotation-scheme versions recorded in the session and CSV files; a more accurate account of the relation to van Leuven-Zwart's model and to MQM Core. Categories and their keys are unchanged; 1.0.0 sessions open without conversion.
- **1.0.0** (2026): πρώτη δημόσια έκδοση / first public release.

## Δημιουργός / Author

Ελένη Τζιάφα (Eleni Tziafa), Εθνικό και Καποδιστριακό Πανεπιστήμιο Αθηνών / National and Kapodistrian University of Athens.
Σχεδιασμός και υλοποίηση σε συνεργασία με τα μοντέλα Claude Opus 5.5, Claude Fable 5 και Claude Fable 5.2 (Anthropic) / Designed and implemented in collaboration with Claude Opus 5.5, Claude Fable 5 and Claude Fable 5.2 (Anthropic).

## Παραπομπή / Citation

Tziafa, E. (2026). *Synkrisis: A browser-based tool for the comparative evaluation of translation versions* [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.23127836

Το DOI αυτό αντιστοιχεί σε όλες τις εκδόσεις και οδηγεί πάντα στην πιο πρόσφατη. Για συγκεκριμένη έκδοση, δείτε τη σελίδα του Zenodo. / This DOI represents all versions and always resolves to the latest one; for a specific version, see the Zenodo record.

## Άδεια / License

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

Εξαίρεση: οι ορισμοί των αξιολογικών κατηγοριών που βασίζονται στην τυπολογία MQM Core διατίθενται με άδεια [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). / Exception: the definitions of the evaluative categories that are based on the MQM Core typology are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
