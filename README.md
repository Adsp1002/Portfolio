# Portfolio Website

Een moderne portfolio website om je projecten te tonen.

## 📁 Bestandsstructuur

- `index.html` - Hoofdpagina met overzicht van alle projecten
- `dark-tech.html` - Projectpagina voor Dark Tech project
- `project-2.html` tot `project-7.html` - Template pagina's voor je andere projecten
- `styles.css` - Alle styling voor de website
- `README.md` - Deze handleiding

## 🚀 Lokaal gebruiken

1. Open `index.html` in je browser
2. Of gebruik een lokale server:
   ```bash
   # Met Python
   python -m http.server 8000
   
   # Met Node.js (npx)
   npx serve
   ```

## ✏️ Projecten invullen

### Op de hoofdpagina (index.html):
1. Vervang de placeholder afbeeldingen met echte screenshots
2. Update de project titels en beschrijvingen
3. Zorg dat de links naar de juiste projectpagina's wijzen

### Op individuele projectpagina's:
Elke projectpagina heeft de volgende secties die je moet invullen:

1. **Project Meta** (bovenaan):
   - Je rol in het project
   - Het jaar waarin je het project hebt gemaakt
   - Type project (School/Stage)

2. **Over het Project**:
   - Wat was het doel?
   - Wat heb je gemaakt?
   - Wat was de uitdaging?

3. **Mijn Rol**:
   - Jouw specifieke verantwoordelijkheden
   - Taken die je hebt uitgevoerd

4. **Gebruikte Skills & Technologieën**:
   - Voeg skill-tags toe (bijv. HTML, CSS, JavaScript, React, etc.)
   - Pas de skill-tags aan naar wat je daadwerkelijk hebt gebruikt

5. **Project Details**:
   - Technische implementatie
   - Design keuzes
   - Problemen en oplossingen
   - Resultaten en feedback

6. **Project Afbeeldingen**:
   - Vervang placeholder afbeeldingen met echte screenshots
   - Voeg meerdere afbeeldingen toe om je project te tonen

7. **Resultaat**:
   - Wat heb je bereikt?
   - Wat was de impact?
   - Wat heb je geleerd?

### Afbeeldingen toevoegen:
1. Maak een map `images/` aan in dezelfde directory
2. Plaats je screenshots daar
3. Update de `src` attributen in de HTML:
   ```html
   <img src="images/dark-tech-screenshot1.png" alt="Dark Tech Screenshot">
   ```

## 🌐 Publiceren op GitHub Pages

1. **Maak een GitHub repository aan**:
   - Ga naar GitHub.com
   - Klik op "New repository"
   - Geef het een naam (bijv. "portfolio")
   - Maak de repository aan

2. **Upload je bestanden**:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/JOUW-GEBRUIKERSNAAM/JOUW-REPO-NAAM.git
   git push -u origin main
   ```

3. **Activeer GitHub Pages**:
   - Ga naar je repository op GitHub
   - Klik op "Settings"
   - Scroll naar "Pages" in het menu links
   - Bij "Source" selecteer "Deploy from a branch"
   - Kies "main" branch en "/ (root)" folder
   - Klik "Save"
   - Je website is nu live op: `https://JOUW-GEBRUIKERSNAAM.github.io/JOUW-REPO-NAAM/`

## 🎨 Aanpassingen maken

### Kleuren aanpassen:
Open `styles.css` en pas de CSS variabelen aan in `:root`:
```css
:root {
    --primary-color: #6366f1;    /* Hoofdkleur */
    --secondary-color: #8b5cf6;  /* Secundaire kleur */
    --accent: #06b6d4;           /* Accent kleur */
}
```

### Tekst aanpassen:
- "Mijn Portfolio" in de navigatie
- "Over Mij" sectie op de hoofdpagina
- Footer tekst

## 📝 Tips

- **Kwaliteit over kwantiteit**: Focus op je beste projecten
- **Consistentie**: Houd hetzelfde format aan voor alle projecten
- **Visueel**: Gebruik goede screenshots en afbeeldingen
- **Details**: Beschrijf niet alleen wat je hebt gemaakt, maar ook hoe en waarom
- **Skills**: Laat zien welke vaardigheden je hebt gebruikt en ontwikkeld

## ✅ Checklist voor elk project

- [ ] Project titel en beschrijving ingevuld
- [ ] Rol duidelijk beschreven
- [ ] Skills en technologieën toegevoegd
- [ ] Minimaal 2-3 screenshots toegevoegd
- [ ] Project details beschreven
- [ ] Resultaat en leerpunten beschreven
- [ ] Links naar live demo/GitHub (indien beschikbaar)

Veel succes met je portfolio! 🎉

