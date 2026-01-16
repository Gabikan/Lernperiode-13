# Lernperiode-14
## 9.1
**React** ⚛️
    * *Typ:* JavaScript-Bibliothek für User Interfaces.
    * *Fokus:* Komponenten-basierte Entwicklung, Single Page Applications (SPA).
2.  **WordPress** 📝
    * *Typ:* Content Management System (CMS).
    * *Fokus:* Schnelles Erstellen von Webseiten und Blogs, PHP-basiert.
3.  **Spaghetti-JS 🍝 (Legacy Edition)**
    * *Typ:* Veraltetes, fiktives Framework.
    * *Fokus:* Code ohne Struktur schreiben, den niemand mehr warten kann.

### ✅ Entscheidung & Begründung

**Gewählte Technologie:** **React**

**Begründung:**
Die Entscheidung fiel eindeutig auf **React**.
* **Gegenüber WordPress:** Wir wollen eine moderne Web-Applikation entwickeln und keine reine Content-Seite. WordPress wäre hier zu starr und bringt zu viel unnötigen Ballast (Backend, Datenbank-Zwang)
* mit, während React uns volle Flexibilität im Frontend bietet.
* **Gegenüber Spaghetti-JS:** React bietet eine klare Struktur durch Komponenten, ein riesiges Ökosystem und eine starke Community. Das sorgt für wartbaren Code und eine gute Lernkurve, im Gegensatz zum
* chaotischen Ansatz der Alternative.
  
## 16.1
## 🚀 Planung der nächsten Sitzung

Hier sind die 4 definierten Arbeitspakete für die Weiterentwicklung:

1.  [ ] **Komponenten & Props verstehen**
    * Zerlegen der App in wiederverwendbare Teile (z.B. eine `<Header />` oder `<UserCard />` Komponente erstellen).
    * Daten mittels *Props* von der Hauptkomponente an die Unterkomponenten übergeben.

2.  [ ] **Interaktivität mit State (useState)**
    * Einbau einer einfachen Interaktion, z.B. ein Zähler-Button oder ein Textfeld, das den Inhalt live auf dem Bildschirm ändert.
    * Ziel: Verstehen, wie sich die UI ändert, wenn sich Daten ändern.

3.  [ ] **Styling & Layout**
    * Entfernen des Standard-React-Logos und der Standard-Styles.
    * Anwenden von eigenem CSS (oder einer Bibliothek wie Bootstrap/Tailwind), um ein einfaches Raster-Layout zu erstellen.

4.  [ ] **Deployment (Asynchron)**
    * *Aufgabe:* Verknüpfung des GitHub-Repositories mit einem Hostinganbieter (Empfehlung: **Vercel** oder **Netlify**).
    * *Ziel:* Die App soll nicht mehr nur auf `localhost` laufen, sondern über eine öffentliche URL für jeden erreichbar sein.
