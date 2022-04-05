# Bewerbungsaufgabe Frontend Developer bei Heise Medien

## Dashboard

Bauen Sie eine kleine Dashboard-Seite. Sie soll dem User das Wetter und eine Liste von News-Teasern anzeigen. Ein Klick auf einen News-Teaser führt zu einer Detailseite mit dem vollständigen Text.

### Wetter

Das Wetter soll die Wettervorhersage für Berlin anzeigen. Für die Wettervorhersage können Sie sich eine beliebige Wetter-API aussuchen. Die Qualität der Vorhersage hat keinen Einfluss auf unsere Beurteilung.

### News

Für die News nutzen Sie bitte die Heise-API unter folgender URL:
https://www.heise.de/extras/frontend/news/

Es gibt zwei Endpoints, beide liefern JSON zurück:
- `/news/`
- `/news/:id`

Der erste Endpoint (`/news/`) kennt außerdem noch die Get-Parameter `limit` und `offset` mit denen Sie einen bestimmten Abschnitt der News-Liste abfragen können. Ohne diese Parameter wird die gesamte Liste mit 100 News zurück geliefert.

Beim zweiten Endpoint (`/news/:id`) kann `:id` durch die ID einer einzelnen News ersetzt werden und liefert dann alle Details dieser News für eine Detailseite. Die ID einer News ist Teil der Antwort von `/news/`.

Anmerkung zum Bild: Der Key `src` unter `image` beinhaltet eine Bild-URL, welche das Bild in seiner größtmöglichen Auflösung ausgibt. Die Parameter `width` (Breite) und `q` (Qualität) können Sie nach Bedarf anpassen.

## Aufgaben

### 1. Die Basis-Seite bauen

Bauen Sie die zuvor beschriebene Dashboard-Seite.

### 2. Erweiterung des Wetters

Erweitern Sie die Wetter-Abfrage, sodass die Wettervorhersage des User-Standorts angezeigt wird. Kann diese Information nicht ermittelt werden dient Berlin als Fallback.

### 3. Kurz und knapp: ein paar CSS-Fragen

Hier haben wir noch ein paar kleine CSS-Aufgaben. Stecken Sie nicht zu viel Zeit in ihre Beantwortung, es geht nicht darum jeden Edge-Case abzudecken. Erklären Sie kurz welchen Layout-Mode Sie verwendet haben und weshalb.

#### 3.1 Layout 1

Bauen Sie eine kleine Seite, die sich verhält wie im folgenden Video:

![Video des Verhaltens von Layout 1](layout1.mp4)

#### 3.2 Layout 2

Bauen Sie eine kleine Seite, die sich verhält wie im folgenden Video:

![Video des Verhaltens von Layout 2](layout2.mp4)

#### 3.3 Layout 3

Bauen Sie eine kleine Seite, die sich verhält wie im folgenden Video:

![Video des Verhaltens von Layout 3](layout3.mp4)

#### 3.4 Styling mit Tailwind vs. Sass

Stellen Sie kurz das Styling mit Tailwind und Sass gegenüber (wesentliche Unterschiede, Vor-/Nachteile,...).

#### 3.5 CSS Box-Modell

Erklären Sie kurz das CSS Box-Modell.

## Hinweise zur Einreichung

Die Gestaltung der Seiten ist vollkommen Ihnen überlassen. Wie das Wetter präsentiert wird, ob die News-Teaser alle gleichförmig oder unterschiedlich gestaltet sind, etc. liegt ganz bei Ihnen. Wir freuen uns vor allem über eine moderne, ansprechende, aufgeräumte Gestaltung.

Bitte reichen Sie auch produktionsfertigen Code ein. Damit meinen wir HTML/CSS/JavaScript, das von einem beliebigen Web-Server ausgeliefert werden kann.

Idealerweise schicken Sie uns einen Link zu Ihrem Code-Repository (GitHub, GitLab,...) mit der Lösung.

Beachten Sie bei der Umsetzung gängige Frontend-Anforderungen, wie Responsive Web-Design, Web-Performance und Accessibility. Aktuelle Browser sollten unterstützt werden, der Internet Explorer 11 zählt definitiv nicht dazu!

Bei Fragen wenden Sie sich gerne an uns.

