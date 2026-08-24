R-Code zur quantitativen Analyse für den Beitrag:

Hofmann, L. (2026). Zwischen Projektion und Vertrauen: Rechte Einstellungen und Wissenschaftsvertrauen in Österreich.

#### Projekt

Der Beitrag prüft, ob rechte Einstellungen in Österreich besser durch die Projektion ökonomischer Unsicherheiten und Zukunftsängste oder durch
Institutionenvertrauen erklärt werden. Statistisch werden dafür herangezogen:

1.	Lineare Modelle basierend auf z-standardisierte Daten. Abhängige Variablen umfassen die Migrationsablehnung (ökonomisch oder kulturell gerahmt), die Wahlwahrscheinlichkeit
	der FPÖ (PTV) und die Links-Rechts-Selbstpositionierung. Unabhängige Variablen sind wahrgenommene und tatsächliche ökonomische Lage sowie Vertrauen in sieben Institutionen.
	(Abb. 4, Appendix)
2.	Korrelationsmatrix
3.	Mittelwertvergleiche (t-Tests und Cohen's d)
4. 	Deskriptive Statistiken und Visualisierungen der absoluten Vertrauenswerte nach politischer Selbstverortung und nach PTV FPÖ (Abb. 1 und 2) sowie nach wissenschaftlichen 	Disziplinen auf Basis der ESS-Daten (Abb. 3).

### Daten

Dieses Repo enthält keine Daten.

Die verwendeten Digitize!-Daten sind unter dem im Beitrag angeführten Link für wissenschaftliche Zwecke zugänglich.
	Der Code erwartet diese als 'data_full' (n=10,551)

Die ESS Daten sind unter dem im Beitrag angegebenen Link frei zugänglich.
	Der Code erwartet diese nach dem im Beitrag beschriebenem Filtern und Zusammenführen in EXCEL (n=604) als 'ESS_data'

### Reproduktion

- Die Datensäte müssen entsprechend der oben aufgeführten Erwartungen importiert werden
- Die libraries dplyr, corrplot, modelsummary, tidyr, ggplot2, ggforce, Hmisc, effectsize, gt, lmtest, sandwich und optional writexl (für den Export der bereinigten Daten) werden erwartet.

### Zitation

Bei Nutzung des Codes bitte den Beitrag sowie die Primärdatensätze (Digitize!,
ESS/CRONOS-2) gemäß den Vorgaben der jeweiligen Anbieter zitieren.

### Kontakt

Lukas-Hofmann@uni-graz.at

