# M1-Visualisierung
***
## Table of Contents
#### 1. Projekthintergrund und -ziele
#### 2. Layoutideen 
#### 3. Umsetzung 
#### 4. Code
***
# 1. Projekthintergrund und -ziele
Entwicklung eines interaktiven Studienverlaufsplans: 
Visualisierung des Modulhandbuchs für den Bachelor Lehramt Sekundarstufe 1

#### Projektidee:
- Entwicklung eines Prototyps zur Visualisierung des Modulhandbuchs für den Bachelorstudiengang Lehramt Sekundarstufe 1  [Modulhandbuch](/2020_12_15_MHB_BA_LA_SekI.pdf) 
- Ziel ist die Erstellung eines interaktiven Studienverlaufsplans, ergänzt durch ein Dashboard zur übersichtlichen Darstellung des Studienfortschritts.
- Im Anschluss wird der Prototyp im Rahmen von Usability-Tests mit Lehramtsstudierenden evaluiert.
- Optional erfolgt eine weiterführende Evaluation durch Experteninterviews zur Optimierung des Konzepts.
 
#### Forschungsfrage:
*Wie kann eine interaktive Visualisierung eines Modulhandbuchs für das Lehramtsstudium (Sekundarstufe 1) gestaltet werden, um den Studierenden eine verbesserte Übersicht über den Studienverlauf zu ermöglichen, und welche Usability-Aspekte sind für die Zielgruppe besonders relevant?* 
 
#### Vorgehensweise:
##### 1. Literaturrecherche:
- Analyse bestehender Visualisierungsansätze und Usability-Prinzipien in der Hochschullehre.
- Untersuchung bereits existierender interaktiver Studienverlaufspläne und Dashboard-Lösungen.
- Identifikation der besonderen Anforderungen von Lehramtsstudierenden (Sekundarstufe 1).
 
##### 2. Anforderungsanalyse:
- Interviews oder Umfragen mit Lehramtsstudierenden zur Ermittlung der Bedürfnisse und Herausforderungen im Studium.
- Analyse der Modulhandbücher und curriculare Anforderungen für das Lehramt Sekundarstufe 1.

#### 3. Prototypenentwicklung:
- Design und Entwicklung eines interaktiven Studienverlaufsplans, der die Modulhandbücher visualisiert.
- Implementierung eines Dashboards zur Darstellung von Fortschritt, Modulen und Meilensteinen.
- Fokussierung auf eine benutzerfreundliche und intuitive Bedienung.
 
##### 4. Usability-Test:
- Durchführung von Usability-Tests mit Lehramtsstudierenden zur Evaluation des Prototyps.
- Anwendung von Usability-Methoden wie "Think-Aloud", Eye-Tracking oder heuristische Evaluation.
- Qualitative und quantitative Auswertung der Usability-Daten.
 
##### 5. Experteninterview (optional):
- Interviews mit Expert:innen aus den Bereichen Hochschuldidaktik, Usability oder Lehramtsausbildung.
- Diskussion von Optimierungspotenzialen und Integration von Expertenfeedback in die Weiterentwicklung des Prototyps.
 
##### 6. Analyse und Auswertung:
- Auswertung der Usability-Tests und der Experteninterviews.
- Identifikation von Stärken und Schwächen des Prototyps.
- Empfehlungen zur Weiterentwicklung und Implementierung des Tools in die Praxis.
 
 ####  Wichtige Punkte:
- Zielgruppe: Lehramtsstudierende und deren spezifische Anforderungen in der Studienorganisation.
- Usability: Benutzerfreundlichkeit und intuitive Bedienbarkeit des Prototyps sind zentral.
- Interaktivität: Der Prototyp sollte einen hohen Grad an Interaktivität bieten, um eine flexible und individuelle Studienplanung zu ermöglichen.
- Visualisierung: Effektive Visualisierung von Modulen, Studienfortschritt und Wahlmöglichkeiten.
- Feedback: Kontinuierliche Einbindung der Zielgruppe (Studierende) und Expert:innen, um den Prototyp praxisnah zu entwickeln

***

# 2. Layoutideen
#### 1. Dashboard-Struktur

Bildungswissenschaften, zwei Fächer & Praxis: Die Struktur sollte drei Hauptbereiche enthalten:
   -   Bildungswissenschaften (Pflicht für alle)
   -   Zwei gewählte Fächer (z.B. Deutsch, Mathematik, Biologie etc.)
   - Praxis (wie z.B. das Orientierungspraktikum)
     
#### 2. Hauptfunktionen
- Studienplan-Generator: Studierende wählen die zwei Fächer, die sie studieren möchten, und das Dashboard generiert automatisch einen passenden Studienverlaufsplan, der die Pflichtmodule der Bildungswissenschaften sowie die gewählten Fächer enthält.
- Zeitplanung: Ein Semesterplaner zeigt, in welchem Semester welche Module belegt werden müssen, basierend auf der Modulverteilung (z.B. 1. Semester: Erziehungswissenschaften, 2. Semester: Einführung in die Pädagogische Psychologie, 3. Semester: Fachdidaktik für das gewählte Fach).
- ECTS-Punkte-Anzeige: Das Dashboard berechnet automatisch die gesammelten ECTS-Punkte und zeigt an, wie viele noch benötigt werden.
- Semesterübersicht: Zeigt eine Übersicht der zu belegenden Module pro Semester an, basierend auf den gewählten Fächern und den Bildungswissenschaften.
- Pflichtmodule vs. Wahlmodule: Eine klare Unterscheidung zwischen Pflichtmodulen und Wahlpflichtmodulen (wie z.B. Wahlseminare in den Bildungswissenschaften oder in den Fachbereichen).

#### 3. Interaktivität
- Modul-Details: Beim Klicken auf ein Modul im Studienverlaufsplan sollten Details zum Modul angezeigt werden, wie z.B. Lehrveranstaltungen, Prüfungsformen, Workload und ECTS-Punkte.
- Zeitliche Anpassung: Studierende können Module, die nicht in einem bestimmten Semester passen, in andere Semester verschieben, solange die Vorgaben des Modulhandbuchs beachtet werden (z.B. müssen gewisse Bildungswissenschaften-Module vor bestimmten Fachmodulen abgeschlossen sein).
  
#### 4. Visualisierung
-	Gantt-Chart-ähnliche Darstellung: Eine visuelle Semesterübersicht zeigt den Studienfortschritt und die noch zu absolvierenden Module.
- Modulabhängigkeiten: Zeigt auf, welche Module Vorbedingungen für andere sind (z.B. Modul X muss vor Modul Y absolviert werden).
  
#### 5. Such- und Filteroptionen
- Suche nach Modulen: Eine Suchfunktion, um Module nach Titel, Inhalten oder ECTS-Punkten zu finden.
- Filter nach Semestern oder Workload: Filteroptionen, um Module nach Semester oder dem Workload (z.B. „nur Module unter 6 ECTS“) anzuzeigen.

#### 6. Dynamische Anpassung für Wahlfächer
- Wenn ein Benutzer das Fach oder die gewählten Wahlpflichtmodule ändert, passt sich der Studienverlaufsplan automatisch an, um die neuen Anforderungen zu berücksichtigen.

***

# 3. Umsetzung

### 1. Planung & Datenaufbereitung
#### Datenmodellierung: 
Zunächst musst du die Informationen aus dem Modulhandbuch strukturiert erfassen. Dies umfasst:
- Module: Name, Semester, ECTS-Punkte, Workload, Prüfungsformen, Voraussetzung/abhängige Module.
- Verbindungen zwischen Modulen: Modulabhängigkeiten (z.B. Module, die vor anderen absolviert werden müssen).
- Fachwahl: Bereite eine Liste der angebotenen Fächer und Wahlpflichtmodule vor.

#### Tools:
- Eine Excel-Tabelle oder Google Sheets kann zunächst als Basis verwendet werden, um die Module, ihre Inhalte und Verbindungen zu organisieren. Später kannst du die Daten in eine Datenbank überführen.

Hier sind unsere Excel-Tabellen: 
- [Modulhandbuch](/2020_12_15_MHB_BA_LA_SekI.pdf) und [Modulhandbuch](/2020_12_15_MHB_BA_LA_SekI.pdf) und 

### 2. Technologieauswahl
#### Frontend (Benutzeroberfläche)
- HTML/CSS/JavaScript für eine interaktive Webanwendung.
- Frameworks wie React oder Vue.js bieten dynamische und responsive Benutzeroberflächen.
- Charting-Bibliotheken: Nutze D3.js, Chart.js oder Plotly.js für die visuelle Darstellung von Studienplänen, ECTS-Punkten und Fortschritt.
- UI-Komponenten: Bibliotheken wie Material-UI (für React) oder Vuetify (für Vue.js) ermöglichen benutzerfreundliche und ansprechende Dashboards.

#### Backend (Datenverarbeitung und -speicherung)
- Node.js (in Verbindung mit Express.js) als Backend-Server zur Verwaltung von Anfragen.
- Datenbank: Nutze eine relationale Datenbank wie PostgreSQL oder MySQL, um die Modulstrukturen und Studentendaten zu speichern. Diese kann leicht Abhängigkeiten und Verbindungen zwischen Modulen handhaben.
- REST-API oder GraphQL: Entwickle eine API, die dem Frontend erlaubt, auf die Module und Studienverlaufsdaten zuzugreifen und Interaktionen zu verarbeiten.

#### Interaktive Features und Benutzerinteraktionen
- Drag-and-Drop Funktionen für Module innerhalb des Studienverlaufsplans lassen sich mit Bibliotheken wie React DnD oder Vue Draggable umsetzen.
- Dynamische Updates: Wenn der Benutzer Module verschiebt oder auswählt, sollte der Plan automatisch aktualisiert werden. Dafür kannst du State-Management-Lösungen wie Redux (React) oder Vuex (Vue.js) verwenden.

### 3. Implementierungsschritte

#### 1. Frontend-Design
- Erstelle eine einfache Benutzeroberfläche, die Module als Karten oder Kacheln anzeigt.
- Implementiere ein Dropdown-Menü, um die zwei Fächer auszuwählen.
- Zeige die Modulübersicht in einer semestergliederten Zeitleiste an. Hier könnte ein Gantt-Chart oder eine tabellarische Ansicht für jedes Semester genutzt werden.

#### 2. Backend-Entwicklung
- Entwickle ein Modulverwaltungssystem, das auf deine Datenbank zugreift. Es stellt sicher, dass Abhängigkeiten zwischen Modulen, Prüfungen und Voraussetzungen korrekt berücksichtigt werden.
- Implementiere eine Benutzerverwaltung, die es ermöglicht, dass Studierende ihre eigenen Studienpläne speichern und bearbeiten können.

#### 3. Interaktive Funktionen
- Integriere ein Drag-and-Drop-System, um Module in der Zeitachse hin- und herzuschieben. Dies erlaubt dem Benutzer, seinen Plan individuell zu gestalten.
- Datenvalidierung: Überprüfe bei jedem Update, ob der Plan den Vorgaben entspricht (z.B. müssen Bildungswissenschaften in den ersten Semestern abgeschlossen sein, gewisse Module bauen aufeinander auf).

#### 4. Dynamische Berechnungen
- Berechne automatisch die ECTS-Punkte und den Workload für jedes Semester basierend auf den ausgewählten Modulen.
- Stelle sicher, dass Studierende Warnungen erhalten, wenn sie nicht genügend ECTS in einem Semester oder insgesamt nicht genügend Module belegen.

#### 5. Datenbankdesign
- Tabellenstruktur: Du könntest Tabellen für:
   - Module (Name, ECTS, Semester, Abhängigkeiten, Beschreibung),
   - Nutzer (um individuelle Pläne zu speichern),
   - Prüfungen und weitere Attribute erstellen.
- Abhängigkeiten: Integriere Logik für Modulabhängigkeiten direkt in die Datenbank oder in das Backend (z.B. durch die Verwendung von SQL-Beziehungen).

#### 4. Zusätzliche Funktionen
- Suche und Filter: Implementiere eine Suche, mit der die Studierenden nach Modulen, ECTS-Punkten, Prüfungsformen etc. filtern können.
- Export-Funktion: Füge eine Export-Funktion hinzu, die es den Studierenden ermöglicht, ihren individuellen Studienplan als PDF oder Excel zu exportieren.
- Benachrichtigungen: Zeige Benachrichtigungen an, wenn Module Anforderungen nicht erfüllen (z.B. „Dieses Modul setzt den Abschluss von X voraus“).

#### 5. Deployment und Hosting
- Frontend: Hoste die Anwendung auf einer Plattform wie Netlify oder Vercel.
- Backend & Datenbank: Setze eine Cloud-Datenbank (z.B. Amazon RDS) und ein Backend auf Heroku oder einer ähnlichen Plattform auf, um den Server zu betreiben.

#### 6. Testen und Feedback
- Benutzerfreundlichkeit testen: Lade Studierende ein, das Dashboard zu testen und sammle Feedback, um die Benutzerführung zu verbessern.
-       https://www.usability.de/leistungen/methoden.html
- Automatische Tests: Entwickle Tests für die korrekte Berechnung von ECTS-Punkten und Workload, sowie die ordnungsgemäße Abbildung der Modulabhängigkeiten.

#### 7. Iterative Entwicklung
- Beginne mit einer MVP (Minimal Viable Product): Eine einfache Version, die nur den Studienverlaufsplan für einen Benutzer erstellt und die Module anzeigt.
- Füge schrittweise erweiterte Funktionen wie Drag-and-Drop und ECTS-Berechnungen hinzu.

### Beispiel-Technologie-Stack
#### 1. Frontend: React.js oder Vue.js, Chart.js oder D3.js für Diagramme.
#### 2. Backend: Node.js mit Express.js, PostgreSQL/MySQL.
#### 3. Deployment: Netlify/Vercel für das Frontend, Heroku/AWS für das Backend.

# 4. Code 
