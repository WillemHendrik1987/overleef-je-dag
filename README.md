# Overleef je dag

Educatief verzekeringsspel van Hanze Verzekeringen Achtergael (Brugge) voor www.hanze.be.

- `index.html` — de volledige spelmotor (camera, effecten, geluid, inhoud in `PROFILES`).
- `assets/` — 40 scènebeelden (A = situatie, B = gevolg), groepsbeeld en 4 muziekstukken.
- `vercel.json` — caching van de assets en toelating om het spel enkel op hanze.be/Wix in een iframe te tonen.

Statische site: geen build nodig. Elke push naar `main` gaat automatisch live via Vercel.
