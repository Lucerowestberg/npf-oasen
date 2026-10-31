# NPF-Oasen

En fristående svensk webbprototyp med daglig NPF-pepp, ett kort lågaffektivt vardagstips och en personlig verktygslåda.

## Starta

Öppna `index.html` i en webbläsare för lokal förhandsvisning. Ingen byggkedja eller externa paket behövs.

## Funktioner

- Dagens pepp och tips väljs utifrån dagens datum.
- Dagens konkreta NPF-strategi roterar bland 21 förslag och kan sparas i verktygslådan.
- Dagens ordspråk roterar bland 35 traditionella japanska uttryck, med japansk skrift, romaji, engelsk betydelse och tema.
- Spara pepp och tips i verktygslådan.
- Lägg till och ta bort egna strategier.
- Skriv och spara personliga anteckningar.
- Växla mellan ljust och mörkt läge; valet sparas på enheten.
- Ställ in en morgonpåminnelse. Webbläsarnotiser kräver tillåtelse och visas bara när appen är öppen.
- Anpassad layout för mobil och större skärmar.
- Installerbar PWA med appikon och offline-cache efter första besöket.

Strategier, sparat innehåll, anteckningar och påminnelseinställningar sparas i webbläsarens lokala lagring på den här enheten. De synkas inte mellan enheter.

## Installera på mobilen

Publicera hela projektmappen på en HTTPS-adress. Behåll `index.html`, `manifest.webmanifest`, `sw.js` och mappen `icons/` på samma sökvägar. En lokal `file://`-öppning fungerar för förhandsvisning men kan inte installeras som PWA.

- Android: öppna HTTPS-adressen i Chrome och välj **Installera app** eller **Lägg till på startskärmen**.
- iPhone: öppna adressen i Safari, tryck på **Dela** och välj **Lägg till på hemskärmen**.

Efter första onlinebesöket kan appens grundinnehåll öppnas offline. En HTTPS-värdtjänst, till exempel GitHub Pages eller Netlify, behöver konfigureras separat.
