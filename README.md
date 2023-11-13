# Forschungsdaten zur Promotionsschrift 

> Christian Thomas: *„… ein Gemisch von Gehörtem und selbst Zugeseztem“. Nachschriften der ‚Kosmos-Vorträge‘ Alexander von Humboldts: Dokumentation, Kontextualisierung und exemplarische Analysen.* Dissertation, Humboldt-Universität zu Berlin: edoc-Server, Version 1.0 vom 1. November 2023. DOI: [https://doi.org/10.18452/27521](https://doi.org/10.18452/27521).

* Lizenz des Textes: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de)
* Lizenz der in diesem Repository bereitgestellten Forschungsdaten: [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)
* weiterer Hintergrund: [Projekt *Hidden Kosmos—Reconstructing Alexander von Humboldt’s “Kosmos-Lectures”*](https://www.culture.hu-berlin.de/de/forschung/projekte/hidden-kosmos) der Humboldt-Universität zu Berlin (2014–2016)
* Subkorpus [„Alexander von Humboldts Kosmos-Vorträge“ im _Deutschen Textarchiv_](http://www.deutschestextarchiv.de/search/metadata?corpus=avhkv)

Work in Progress. Erstes Release der Forschungsdaten geplant mit Veröffentlichung der Promotionsschrift.

## Inhaltsübersicht dieses Repositoriums

### [Copyfind-Reports](https://github.com/cthomasdta/diss-avhkv/tree/master/Copyfind-Reports)
– versammelt Ergebnisse der Korpusanalyse mit dem Tool *WCopyfind*, mit dem Instanzen von "Text Re-Use" und somit potentielle Abschreibeverhältnisse innerhalb des Korpus ermittelt wurden. Grundlage der Vergleiche sind die stundenweise gesplitteten und teilautomatisch normalisierten XML-Dokumente aus dem Ordner [../sessions](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/sessions), jeweils die Datei mit der Endung `.norm.xml`, die per XSLT-Skript in eine HTML-Fassung umgewandelt und an *WCopyfind* übergeben wurden. Siehe dazu Diss. [Thomas 2023](https://doi.org/10.18452/27521), S. 374–392.
#### [all-exc-Hufeland_vs_Humboldt-1827-1830](https://github.com/cthomasdta/diss-avhkv/tree/master/Copyfind-Reports/all-exc-Hufeland_vs_Humboldt-1827-1830) 
– Vergleich aller Dateien miteinander und mit Humboldts Aufsatz [„Über die Haupt-Ursachen der Temperatur-Verschiedenheit auf dem Erdkörper“ (Humboldt 1827)](https://www.deutschestextarchiv.de/humboldt_ursachen_1830), unter Ausschluss der Dateien aus [../XML-Files/sessions/hufeland_privatbesitz_1829](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/sessions/hufeland_privatbesitz_1829) (siehe dazu den folgenden Punkt).
#### [all-except-Hufeland](https://github.com/cthomasdta/diss-avhkv/tree/master/Copyfind-Reports/all-except-Hufeland) 
– Vergleich aller Dateien miteinander, unter Ausschluss der Dateien aus [../XML-Files/sessions/hufeland_privatbesitz_1829](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/sessions/hufeland_privatbesitz_1829), da hier bereits feststeht, dass es sich dabei um eine (indirekte) Abschrift von [../XML-Files/sessions/nn_msgermqu2124_1827](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/sessions/nn_msgermqu2124_1827) handelt und diese daher nicht nochmals auf "Text Re-Use" hin untereucht werden müssen. Vgl. dazu Diss. [Thomas 2023](https://doi.org/10.18452/27521), S. 323.
#### [norm-xml-html_all_vs_all](https://github.com/cthomasdta/diss-avhkv/tree/master/Copyfind-Reports/norm-xml-html_all_vs_all) 
– Vergleich aller Dateien aus [../XML-Files/sessions](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/sessions) miteinander.
### [Gliederung](https://github.com/cthomasdta/diss-avhkv/tree/master/Gliederung) 
– Listen zu den Daten und Themen der beiden Vortragskurse der Kosmos-Vorträge in der Berliner Universität und der Sing-Akademie. Vgl. dazu Diss. [Thomas 2023](https://doi.org/10.18452/27521), Kap. 5.4 (S. 156–163) sowie Kap. 6.2 (S. 178–196; insbes. die Übersicht über beide Kurse auf S. 189).
### [XML-Files](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files)
#### [DTABf-Original_TEI-P5-xml](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/DTABf-Original_TEI-P5-xml) 
– XML-Dateien der Nachschriften und Abschriften der Kosmos-Vorträge A. v. Humboldts, kodiert in TEI-XML gemäß DTA-Basisformat für Manuskripte, mit kleineren projektspezifischen Anpassungen. Vgl. zu den Transkriptionsrichtlinien und zur Annotation [Thomas 2023](https://doi.org/10.18452/27521), Kap. 8 (S. 225–272).
#### [NER-experiments](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/NER-experiments)
– Versuch, mittels automatischer Methode zu einer "Named Entity Recognition" (NER) innhalb des Korpus zu gelangen; aus Zeitgründen zunächst nicht weiter verfolgt.
#### [sessions](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/sessions) 
– Dokumente aus [../XML-Files/DTABf-Original_TEI-P5-xml](https://github.com/cthomasdta/diss-avhkv/tree/master/XML-Files/DTABf-Original_TEI-P5-xml), per Skript gesplittet in Einzelstunden. Vgl. dazu [Thomas 2023](https://doi.org/10.18452/27521), S. 348, Anm. 25.
### [juXta-collation-sets](https://github.com/cthomasdta/diss-avhkv/tree/master/juXta-collation-sets)
– Ergebnisse der automatischen Kollation ausgewählter Dokumente mit *juXta*, vgl. Diss. [Thomas 2023](https://doi.org/10.18452/27521), Kap. 9.2, insbes. S. 276‒282.
