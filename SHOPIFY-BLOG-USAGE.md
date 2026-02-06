# Shopify Blog Page - Anleitung / Usage Guide

## Über diese Datei / About This File

Die Datei `puppy-play-blog.html` ist eine vollständige, responsive Blog-Seite über Puppy Play, die direkt in Shopify als "Custom Liquid" Section eingefügt werden kann.

The file `puppy-play-blog.html` is a complete, responsive blog page about Puppy Play that can be directly inserted into Shopify as a "Custom Liquid" section.

---

## Verwendung in Shopify / Using in Shopify

### Schritt 1: Datei öffnen / Step 1: Open File
1. Öffnen Sie `puppy-play-blog.html` in einem Text-Editor
2. Kopieren Sie den **gesamten Inhalt** der Datei

### Schritt 2: In Shopify einfügen / Step 2: Insert into Shopify
1. Gehen Sie zu Ihrem Shopify Admin Panel
2. Navigieren Sie zu: **Online Store → Themes**
3. Klicken Sie auf **Customize** bei Ihrem aktiven Theme
4. Wählen Sie die Seite, wo Sie den Blog einfügen möchten
5. Klicken Sie auf **Add section**
6. Scrollen Sie nach unten und wählen Sie **Custom Liquid**
7. Fügen Sie den kopierten HTML-Code ein
8. Klicken Sie auf **Save**

---

## Funktionen / Features

✅ **Vollständig responsiv** / Fully Responsive
- Mobile (375px+)
- Tablet (768px+)
- Desktop (1024px+)

✅ **SEO-optimiert** / SEO Optimized
- Semantisches HTML5
- Meta-Tags
- Korrekte H1-H3 Struktur

✅ **Performance**
- Keine externen Abhängigkeiten
- Inline CSS
- Schnelle Ladezeiten

✅ **Design**
- Minimalistisch & modern
- Viel Weißraum
- Klare Typografie
- Highlight-Boxen
- FAQ-Bereich

---

## Anpassungen / Customization

### Farben ändern / Change Colors
Suchen Sie im `<style>`-Block nach:
```css
/* Hauptfarben / Main Colors */
color: #2c3e50;      /* Textfarbe / Text color */
color: #4299e1;      /* Akzentfarbe / Accent color */
background: #f7fafc; /* Hintergrund / Background */
```

### Schriftgröße anpassen / Adjust Font Size
```css
html {
    font-size: 16px;  /* Basis-Schriftgröße / Base font size */
}
```

### Maximale Breite ändern / Change Max Width
```css
.blog-container {
    max-width: 800px;  /* Ändern Sie diesen Wert / Change this value */
}
```

---

## Inhalt bearbeiten / Edit Content

Der Inhalt befindet sich im `<article>`-Tag. Sie können:
- Überschriften ändern
- Absätze hinzufügen/entfernen
- Listen bearbeiten
- FAQ-Einträge anpassen

**Wichtig:** Behalten Sie die HTML-Struktur bei (z.B. `<h2>`, `<p>`, `<section>` Tags).

---

## Technische Details / Technical Details

- **Sprache:** Deutsch (lang="de")
- **Dateigröße:** ~18KB
- **Zeilen:** 454
- **Technologie:** Pure HTML + CSS
- **Kompatibilität:** Alle modernen Browser
- **Shopify:** Custom Liquid kompatibel

---

## Support

Bei Fragen oder Problemen:
1. Überprüfen Sie, ob der gesamte Code kopiert wurde
2. Stellen Sie sicher, dass "Custom Liquid" als Section-Typ gewählt ist
3. Überprüfen Sie die Browser-Konsole auf Fehler

---

## Lizenz / License

Dieses Template kann frei für kommerzielle und private Projekte verwendet werden.

This template can be freely used for commercial and private projects.
