# Bullinger Digital (Korpus in TEI-XML)

Bullinger Digital war von 2020-2025 ein am Institut für Computerlinguistik der Universität Zürich angesiedeltes Projekt mit dem Ziel, 
den 12'000 Briefe umfassenden Bullinger-Briefwechsel online verfügbar zu machen. Das Projekt war in zwei Phasen aufgeteilt: 
In der ersten Projektphase haben wir eine Datenbank aufgebaut und ein individuelles Online-Suchsystem entwickelt 
(vgl. https://github.com/bullinger-digital/bullinger-korpus), in der zweiten Projektphase haben wir die Daten in das vorliegende 
Korpus in TEI-XML überführt mit dem Ziel, dass die Informationen langfristig via TEI-Publisher online verfügbar bleiben und
über das Projektende hinaus bearbeitbar bleiben. Diese Aufgabe übernimmt das Staatsarchiv des Kantons Zürich, das bereits den
grossteil der überlieferten Briefe aufbewahrt, sodass wir per Projektende das Korpus sowie die Website www.bullinger-digital.ch dem 
Staatsarchiv des Kantons Zürich übertragen. Dieses stellt u.a. sicher, dass die neu von der HBBW-Edition edierten Briefe ins Korpus 
eingespielt werden. Die im vorliegenden Verzeichnis abgelegten Daten geben den Stand per xx.Mai 2025 wieder. 

Folgende Arbeitsschritte liegen dem Korpus zugrunde und sind unter https://github.com/bullinger-digital/bullinger-korpus-tei/tree/main/docs 
ausführlicher beschrieben: 
- Sammlung der verfügbaren Informationen pro Brief
  - Metadaten (aus der gedruckten HBBW-Edition, aus den Karteikarten des HBBW-Editionsteams)
  - Regesten (aus der gedruckten HBBW-Edition)
  - Kommentarapparat als Fussnoten (aus der gedruckten HBBW-Edition)
  - Brieftexte (aus der gedruckten HBBW-Edition, aus anderen gedruckten Editionen, aus den Vorarbeiten des HBBW-Editionsteams, automatisch erstellte Transkriptionen)
  - Faksimile der Briefe (hauptsächlich aus dem Staatsarchiv des Kantons Zürich und der Zentralbibliothek Zürich)
- Normalisierung der frühneuhochdeutschen Brieftexte
- Auszeichnung der Briefsprache (Code-Switching)
- automatische Eigennamenerkennung mit manueller Kontrolle mittels Citizen Science-Kampagne
- automatische Übersetzung der Regesten und Brieftexte
- automatische Verschlagwortung

### Impressum
Folgende Personen haben an der Erstellung des Bullinger-Korpus mitgewirkt:
- Projektleitung: Patricia Scheurer, Phillip B. Ströbel, Martin Volk
- Technische Umsetzung: Raphael Müller, Bernard Schroffenegger
- Korpus-Aufbereitung und Annotation: Lukas Fischer, Dominic P. Fischer, Anastassia Shaitarova
- Linguistische Beratung und Annotation: Raphael Schwitter
- Abstimmung mit der HBBW-Edition am IRG der UZH: Tobias Jammerthal, David Mache, Paul Neuendorf, Peter Opitz, Judith Steiniger
- Recherchen und Annotation: Peter Rechsteiner
- Bibliothekarische und archivarische Koordination: Jesko Reiling (ZB Zürich), Christian Sieber (Staatsarchiv Zürich)
- Automatische Handschriften-Erkennung: Andreas Fischer und Team an der Hochschule Fribourg, Tobias Hodel und Team an der Universität Bern
- Technische und administrative Unterstützung: Eyal Dolev, Leo Rutschmann, Elainne Vibal
- Studentische Mitarbeitende: Donn Edvard Anin, Sabrina Brändle, Nikolaj Bauer, Isabelle Cretton, Angela Heldstab, Jana-Maria Humbel, Diana Merkle, Maria Christina Panagiotopoulou, Antonia Popp, Ismail Prada, Benjamin Suter
- Finanzielle Förderung: UZH Foundation
- Kontakt: bullinger-digital@protonmail.com

### Zitiervorschlag
@misc{Scheurer_et_al_2025,
	author = {Patricia Scheurer and Raphael M{\"u}ller and Bernard Schroffenegger and Phillip B. Str{\"o}bel and Martin Volk},
	howpublished = {Digitale Edition},
	month = {Mai},
	title = {Bullinger Digital Briefkorpus. Briefe von und an Heinrich Bullinger 1523 bis 1575},
	year = {2025},
	school = {Universität Zürich, Institut für Computerlinguistik},
	url = {https://github.com/bullinger-digital/bullinger-korpus-tei}}

### Weiterführende Informationen Bullinger Digital 2.0 (Januar 2024 bis Juni 2025)
- HBBW-Edition: https://www.irg.uzh.ch/de/forschung/bullinger/edition-briefwechsel.html
- Bullinger Digital Projekt: https://www.cl.uzh.ch/de/research-groups/texttechnologies/research/digital-humanities/bullinger.html
- Forschungsbeiträge aus dem Bullinger Digital Projekt: https://www.cl.uzh.ch/de/research-groups/texttechnologies/research/digital-humanities/bullinger.html
- TEI-Publisher: https://www.e-editiones.org/
- laufend aktualisiertes Online-Suchsystem: www.bullinger-digital.ch

### Urheberrecht
Das Projekt Bullinger Digital ist der Open-Science-Policy und den FAIR-Prinzipien verpflichtet. Texte sind unter
Creative Commons BY-NC-ND 3.0 CH lizenziert und können unter Angabe des Urhebers (s. Zitiervorschlag) und einem Link zur
Lizenz für wissenschaftliche, private und nicht-kommerzielle Zwecke vervielfältigt und weiterverbreitet werden.
Die Faksimiles sind unter Creative Commons BY-SA 4.0 lizenziert und können unter Angabe des Urhebers (= Ort der
Aufbewahrung und Signatur; gemäss Quellenangabe oberhalb des Digitalisats) und einem Link zur Lizenz für
wissenschaftliche, private, nicht-kommerzielle und kommerzielle Zwecke frei verwendet werden. Bei den Faksimiles ist
zusätzlich die Signatur anzugeben. 
