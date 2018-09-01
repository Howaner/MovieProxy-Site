# MovieProxy Webseite

Hier liegt der Quellcode für die https://www.movieproxy.de Webseite.  
Die Webseite wird mittels [Hugo](https://gohugo.io/) in einen statischen HTML Code kompiliert und via Nginx ausgeliefert.  
Als Template wurde [Hugo Fresh](https://themes.gohugo.io/hugo-fresh/) verwendet.

Die Seite in statischen HTML Code kompilieren:  
```
# Vorher Hugo installieren!

# Das Theme Submodule herunterladen
git submodule init
git submodule update

# Die Webseite kompilieren
hugo
# Die Ausgabe befindet sich jetzt unter public/
```

Zum Starten der Debug-Seite:
```
hugo server -D --verbose
```