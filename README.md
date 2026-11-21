# Receptsajten

En enkel, svenskspråkig receptsajt med vardagsrecept för frukost, middag, efterrätt och fika. Besökaren kan bläddra bland utvalda recept, läsa ett recept steg för steg och fylla i ett formulär för att tipsa om ett eget.

## Sidor

- **Om sajten (`index.html`)** – startsida med introduktion, kategorier och tre receptkort: pannkakor, teriyaki laxbowl och mjuk nötkaka med kolasås.
- **Receptsida (`pannkakor.html`)** – pannkaksrecept för fyra portioner med ingredienslista, tillagningssteg och serveringsbilder. Ingredienserna går att bocka av.
- **Dela recept (`recept.html`)** – formulär för receptnamn, kategori, tillagningstid, portioner, svårighetsgrad, ingredienser, instruktioner och avsändarens kontaktuppgifter.

## Teknik och design

Webbplatsen är byggd med HTML och CSS. Den använder inga JavaScript-filer, ramverk, byggverktyg eller backend. Layouten använder bland annat CSS Grid och Flexbox för att anpassa innehållet efter skärmbredden. Färger, typografi, avstånd och andra designvärden finns som CSS-variabler i `variables.css`.

Sidorna delar stilmallarna `reset.css`, `variables.css` och `styles.css`. Bilder och logotyp ligger i `images/`. Typsnittet Open Sans hämtas från Google Fonts; utan internet används reservtypsnitt från systemet.

## Kom igång

Öppna `index.html` i en webbläsare. Projektet har inga beroenden som behöver installeras och behöver ingen byggprocess eller lokal server för att visa sidorna.

## Tillgänglighet

Sidorna har svenska som sidans språk, en länk för att hoppa till huvudinnehållet och etiketter för formulärfält. Bilderna har alternativtexter, och receptets ingredienser kan markeras med tangentbord eller mus.

## Nuvarande begränsningar

- Kategorilänkarna är platshållare och leder inte till filtrerade recept.
- Alla tre receptkorten på startsidan leder för närvarande till pannkaksreceptet.
- Formuläret för att dela recept har ingen serverkoppling eller lagring. Det är en formulärskiss och skickar inte in recept till sajten.
