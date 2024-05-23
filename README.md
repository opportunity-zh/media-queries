# SCSS und Media Queries

In dieser Übung lernst Du den Umgang mit SCSS und die Anwendung von Media Queries.
Für diese Übung werden drei **Geräte** definiert, die du verwenden kannst:

- Mobile: <= 768px
- Tablet: > 768px und < 1024px
- Desktop: >= 1024px

Die Website soll von dir **Mobile First** aufgebaut werden. Das bedeutet, dass das Grunddesign von einem mobilen Endgerät ausgeht und die Media Queries für die grösseren Geräte verwendet werden.

## Starten

Lade das Projekt auf deinen Ordner und installiere das SASS Package, das sich im package.json befindet, mit folgendem Befehl:

```bash
npm install
```

## Übung

### SCSS

1. Lese folgenden [Artikel](https://matthewelsom.com/blog/simple-scss-playbook.html) und erstelle passende Partials
2. Verwende CSS Custom Properties oder SCSS Variablen für die Farben

### Media Queries

#### Mobile

- [ ] die Navigationselemente sollen ausgeblendet sein
- [ ] der Footer soll die gleiche Farbe haben, wie der Header
- [ ] die Farbe der Sidebar soll dieselbe Farbe haben wie der Main Tag
- [ ] Sidebar und Main Tag sollen untereinander sein

#### Tablet

- [ ] die Navigationselemente sollen untereinander platziert sein
- [ ] der Hintergrund der Navigationselemente soll weiss sein
- [ ] Sidebar und Main Tag sollen nebeneinander

#### Desktop

- [ ] Die Navigationselemente sollen nebeneinander stehen
- [ ] der Hintergrund der Navigationselemente soll transparent sein
- [ ] Die Karten im main Tag sollen nebeneinander platziert werden
- [ ] der Footer soll die Farbe #FFDA78 erhalten
