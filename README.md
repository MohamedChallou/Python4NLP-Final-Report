# Python4NLP-Final-Report

0. Organisatorisches

- Deadline: 24.07.2026
- Link für die Abgabe https://uni-duesseldorf.sciebo.de/s/m2D6nWFCmnErsnd
- Filename für die Abgabe: universityID_surname_final_project.pdf
- Voller Name und Uni-Id im Report angeben
- Abgabeformat: PDF und Repository, welches den Code oder Notebook enthält und eine README.md

1. Überblick

- Methoden aus dem Kurs verwenden um eine Forschungsfrage zu beantworten
- Inklusive einem Experiment, Evaluation der Ergebnisse und Erklärung was man gelernt hat
- Projekt sollte die Kursprojekte erweitern

2. Projektrichtung
3. 
  2.1 Study the Effect of Training-Data Size
   
  - Die selben Modelle mit unterschiedlicher Menge an gelabelten Daten trainieren
    
  Mögliche Fragen:
  - Wie schnell verbessert sich die Leistung bei zunehmnder Trainingsmenge?
  - Profitieren vortrainierte Modelle mehr, wenn Traingsdaaten limitiert sind?
  - Ab wann reduzieren zusätzliche Trainingsbeispiele die Modelleistung?

3. Projekt Anforderungen

- klare und machbare NLP-Forschungsfrage oder Hypothese
- dokumentierter Datensatz mit passender Quelle und Lizenz
- begründete Trainings-, Validierungs- und Testsplits
- mindestens eine sinnvolle Baseline
- ein kontrollierter Vergleich von mindestens zwei Modellen oder experimentellen Bedingungen
- passende quantitative Bewertungsmetriken
- Diskussion über Limitationen, Rechenaufwand und Verbesserungen
- korrekte Zititation von Datensätzen, pretrained Models, software und papers
- reproduzierbarer Code, aufgezeichnete Hyperparameter und feste random seeds an geeigneten Stellen
- Eine Erklärung zur Nutzung von KI

4. Anforderungen an den Code

- dependency und environment information
- Anleitung zum beschaffen oder Vorbereiten der Daten
- Anleitung zum Ausführen von Training und Evaluation
- random seeds
- Wichtige Hyperparameter
- gespeicherte oder reproduzierbare Ergebnisse
- klare Verbindung zwischen Code und den berichteten Experimenten im Report

- in der Lage sein den eingereichten Code und methodische Entscheidungen erklären zu können

## Forschungsfrage:

*Sind einfache oder sequenzbasierte NLP-Modelle bei der IMDB-Sentimentklassifikation dateneffizienter, und ab welcher Trainingsdatenmenge zeigen komplexere Modelle einen klaren Vorteil?*

### Mögliche Unterfragen

- Wie schnell steigt Performance mit mehr Daten?
- Welches Modell ist bei wenig Daten stabiler?
- Gibt es einen Punkt, ab dem zusätzliche Daten kaum noch helfen?
- Rechtfertigt ein komplexeres Modell den höheren Trainingsaufwand?
- Profitieren vortrainierte Modelle mehr, wenn Traingsdaaten limitiert sind?
