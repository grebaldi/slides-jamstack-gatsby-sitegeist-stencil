# Static Site Generators

Jekyll, Next, Gatsby...

---

## Es war einmal, das Internet...

(_ToDo: Maybe not the right slide for this_)

- 2000 -> Statisches Html
- - Mit Frames, nicht Suchmaschinenfreundlich
- - Ohne Frames aufwändig zu pflegen

- 2002 -> Erste CMS
- - Syteme wie Postnuke, PHP Nuke, PHP Kit usw kamen auf.
- - Seiten und Content konnten Dynamisch zusammengebaut und mit wenig Aufwand gepflegt werden
- - CMS wurden mit der Zeit immer komplexer und Resourcenhungriger
- - Ein wechsel auf ein anderen CMS bedeutete meist den kompletten Neubau der Seite.

- 24 Jun 2010 -> Back to the Roots
- - Jekyll erblickt das Licht der welt und statische Seiten erheben sich wie Phönix aus der Asche....
- - Datenraupen aus Markdownfiles und Schnittstellen, wandelten sich wie von Zauberhand, zu kompletten Website-Schmetterlingen.
- - Lediglich das statische HTML wird an den Hoster ausgeliefert.
- - Googles Suchbots sind, ob der Geschwindigkeit, ganz aus dem Häuschen und der Pöbel tobt vor begeisterung. Welch eine Performance, Welch einfaches und günstiges Hosting... Mit Forken und Fackeln machen sie sich auf zum Elfenbeintum der CMS um diese Halunken hinfort zu jagen...

- wenige Jahre später:
- - im Dunstkreis des React Universums formieren sich Componenten Haufen zu 2 neuen Galaxien: Next.js und Gatsby.
- - Next.js ist eine Server Side Rendering Galaxie, deren Jetstream vorgerenderte React Componenten in die unedlichen Weiten des Internets ausschüttet.
- - Gatysby hingegen ist eine Static-Site-Generator-Galaxie welche regelmäßg Gammablitze von statischen fertig gerenderten Seiten abgibt.

# Funktionsweise

(_ToDo: Visualisierung der Punkte als Flussdiagramm_)

- Content wird einfach aus Markdown files, REST API, GraphQL oder JSON Api eines, oder mehrerer CMS gelesen.
- Statische Seiten werden generiert
- Seiten werden zum Hoster deployed

# Vorteile

- Sehr einfaches Hosting
- Für Start der Entwicklung ist kein CMS und komplexes Hosting notwendig,
- Veränderungen am Frontend schnell und unabhängig vom CMS durchführbar, dadurch mvp möglich.
- Da nur statisches HTML im Browser geladen wird, ein maximum an Performance für den User ( und google bots ;) )
- Progressive Web App's möglich
- Backend kann ausgetauscht werden, ohne die eigentliche Website neu implementieren zu müssen
- Wieder verwendbare Frondend Komponenten
- Security (No server side application code)

# Nachteile

- Changes werden erst nach Build und Deployment sichtbar

# Verbreitete Generatoren

Jekyll, Gatsby, (Next.js)...
