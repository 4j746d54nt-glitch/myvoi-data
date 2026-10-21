# MyVoi — Demo-Daten

Dieses Repository enthält `demos.json`: eine automatisch wöchentlich aktualisierte
Liste von Demonstrationen in Deutschland, recherchiert aus öffentlichen Quellen
(z. B. offizielle Versammlungsbehörden-Register der Städte).

Die MyVoi-App ruft diese Datei beim Start ab und zeigt die enthaltenen Demos als
**"automatisch importiert"** an — klar erkennbar und mit Link zur Originalquelle,
nicht vermischt mit Demos, die echte Nutzer*innen selbst angelegt haben.

- `demos.json` wird von einer wöchentlichen, automatisierten Recherche überschrieben.
- Qualität und Vollständigkeit hängen davon ab, was die jeweiligen Quellen zum
  Zeitpunkt der Recherche strukturiert veröffentlichen — es ist keine Garantie auf
  Vollständigkeit.
- Jeder Eintrag verweist über `sourceUrl` auf seine Originalquelle, damit das
  nachprüfbar bleibt.
