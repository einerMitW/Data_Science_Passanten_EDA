# Explorative Datenanalyse zum Datensatz Passanten in Würzburg

Dieses Projekt führt eine explorative Datenanalyse (EDA) des Datensatzes "Passanten in Würzburg" für das Jahr 2024 durch. Die Analyse wurde im Rahmen der Lehrveranstaltung "Grundlagen Data Science" an der DHBW Stuttgart erstellt.

## Projektübersicht

Das Ziel dieser Analyse ist es, Muster und Rhythmen in der Passantenfrequenz an drei verschiedenen Standorten in der Würzburger Innenstadt zu identifizieren. Die Analyse untersucht die Daten auf Jahres-, Wochen- und Tagesebene, um Einblicke in die Nutzung der Innenstadt zu gewinnen.

## Datensatz

Der verwendete Datensatz `passanten_wuerzburg.csv` enthält stündliche Passantenzählungen von drei Messstationen in Würzburg:

-   **Kaiserstraße**
-   **Schönbornstraße**
-   **Spiegelstraße**

Die Daten umfassen den Zeitraum vom 1. Januar 2024 bis zum 31. Dezember 2024.

## Verwendete Technologien

-   **R:** Programmiersprache für statistische Analysen und Visualisierungen.
-   **RStudio:** Integrierte Entwicklungsumgebung für R.
-   **R Markdown:** Für die Erstellung des Analyseberichts (`Weiner_Passanten01.Rmd`).
-   **tidyverse, readr, broom, gridExtra, stats, janitor, skimr, lubridate, dplyr, ggplot2, fmsb, corrplot:** R-Pakete, die für die Datenmanipulation, -analyse und -visualisierung verwendet wurden.

## Ausführung der Analyse

Um die Analyse zu reproduzieren, öffnen Sie die R-Projekt-Datei `Weiner_inf24_Passanten.Rproj` in RStudio und führen Sie das R-Markdown-Skript `Weiner_Passanten01.Rmd` aus. Stellen Sie sicher, dass alle oben genannten Pakete installiert sind.