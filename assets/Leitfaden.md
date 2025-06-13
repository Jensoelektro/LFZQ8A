**Anleitung zur Erstellung einer Website: Ein 5-Schritte-Leitfaden für Anfänger**

Das Erstellen einer Website kann ist eine spannende Möglichkeit, deine Fähigkeiten und Projekte von dir oder deinen Kunden online zu präsentieren. Dieser Leitfaden führt  Schritt für Schritt durch den Prozess, von der Planung bis zur Veröffentlichung deiner Website.

### **Schritt 1: Planung und Vorbereitung**

**Ziel:** Definition des Zwecks deiner Website und Sammlung aller notwendigen Materialien.

1. **Thema festlegen:** Entscheide was das Thema deiner Webiste sein soll. Eine Visitenkarte für dich (Portfolio)? Oder eine für deinen lokalen Dönermann? Hast du einen bekannten der eine Website für sein Business gebrauchen könnte? Dann kannst du sie in diesem Workshop umsetzen.
2. **Zweck festlegen:** Überlege dir, welchen Zweck deine Website erfüllen soll. Was soll sie für den Nutzer leisten – und was willst du mit ihr erreichen? (Informationen über ein Produkt oder eine Dienstleistung bereitstellen, Eine Person oder ein Unternehmen vorstellen (z. B. als digitale Visitenkarte), Eine Bewerbung oder Arbeitsproben präsentieren)
3. **Zielgruppe Definieren**: Wer soll deine Website später sehen? Recruiter einer Firma? Kunden die schauen wollen, ob das Essen gut ist? Überlege dir auf wen die Website ausgerichtet sein soll und wie man die Gestaltung an die Zielgruppe anpasst um das Ziel der Website zu erreichen.
3. **Inhalte vorbereiten:** Sammel alle relevanten Inhalte, wie Texte, Bilder, und Projektbeschreibungen.
Lizenzfreie Bilder: (https://unsplash.com/de)
4. **Designidee skizzieren:** Überlege, wie deine Website aussehen soll. Möchtest du ein minimalistisches Design oder ein farbenfrohes Layout?

### **Schritt 2: Einrichtung der Projektstruktur**

**Ziel:** Erstellung der grundlegenden Dateistruktur und Vorbereitung der Arbeitsumgebung.

1. **Projektordner erstellen:** Erstelle einen Ordner für dein Projekt, z.B. "doenerladen".
2. **Unterordner anlegen:** Lege Unterordner für CSS, LESS, Bilder (img), und JavaScript (js) an.
3. **Dateien vorbereiten:** Erstelle grundlegende Dateien wie `index.html` für den HTML-Code, `styles.less` für LESS-Stile, und `scripts.js` für zukünftige JavaScript-Funktionalitäten.

### **Schritt 3: Entwicklung der HTML-Struktur**

**Ziel:** Strukturierung der Inhalte der Website mit HTML.

1. **Grundgerüst erstellen:** Beginne mit der Erstellung des Grundgerüsts in `index.html`. Verwende HTML5-Elemente wie `<header>`, `<section>`, und `<footer>`.
2. **Inhalte einfügen:** Füge Inhalte wie Überschriften, Texte, Bilder und Links ein. Denke daran, die Struktur logisch und übersichtlich zu gestalten.
3. **Navigation einbauen:** Erstelle eine Navigation, die Benutzern hilft, sich auf deiner Website zurechtzufinden.
4. **Kontaktformular implementieren:** Baue ein einfaches Kontaktformular mit Namem E-Mail und Nachricht ein. Achte darauf, dass du auf die DSGVO und SSL Zertifikate hinweist. 

### **Schritt 4: Stilgestaltung mit CSS und LESS**

**Ziel:** Gestaltung des Aussehens deiner Website mit CSS, unterstützt durch LESS für erweiterte Stilmöglichkeiten.

1. **Klassen Definieren:** Definiere Klassen in deiner html-Datei um einheitliche Stile umsetzen zu können.
2. **LESS einrichten:** Schreibe Stile in der `styles.less` Datei. LESS ermöglicht es dir, Variablen und Mixins zu verwenden, was die Stilverwaltung erleichtert.
3. **Kompilieren:** Kompiliere die LESS-Datei zu CSS mit einem LESS-Compiler (z.B. mit dem Befehl `lessc less/styles.less css/styles.css`).
4. **CSS anpassen:** Passe das Erscheinungsbild deiner Website an, indem du Farben, Schriften, Abstände und Layouts festlegst. Verwende eine ausgewählte Farbpalette, um ein Zielgruppenorientiertes Aussehen zu erzielen. Mit https://coolors.co/ kannst du dir Farbpaletten generieren lassen.

### **Schritt 5: Responsive Design - Mobile First**

**Ziel:** Deine Website soll auf allen Geräten gut aussehen – vom Smartphone bis zum großen Bildschirm.

1. **Media Queries einsetzen:** Mit sogenannten Media Queries in den Styles kannst du gezielt Regeln für bestimmte Bildschirmgrößen definieren. 
Beispiel:
```
@media screen and (min-width: 768px) {
  /* Layout-Anpassungen für Tablets und größere Bildschirme */
  .container {
    display: flex;
    flex-direction: row;
}
```
2. **Layout anpassen:**  Achte darauf, dass sich Navigation, Texte und Bilder flexibel anpassen. Verwende z. B. Prozentwerte oder flexbox, um Elemente beweglich zu machen.

### **Schritt 6: Testen und Veröffentlichen**

**Ziel:** Sicherstellung, dass deine Website auf verschiedenen Geräten gut funktioniert - anschließende Veröffentlichung.

1. **Testen:** Überprüfe deine Website auf verschiedenen Geräten und Browsern, um sicherzustellen, dass sie gut funktioniert und responsiv ist.
2. **Fehler beheben:** Beheben Sie eventuelle Fehler in der Darstellung oder Funktionalität.
3. **Veröffentlichen:** Laden Sie Ihre Website auf einen Webserver oder nutzen Sie Hosting-Dienste wie GitHub Pages, um sie online zu stellen.

### **Zusammenfassung:**

Dieser Leitfaden bietet eine strukturierte Herangehensweise an die Erstellung einer Website. Es ist wichtig, jeden Schritt sorgfältig zu durchlaufen und sicherzustellen, dass deine Website sowohl technisch einwandfrei als auch ansprechend gestaltet ist. 