# Promptboek Grok Imagine: Sam (pilot "Overleef je dag 2.0")

Doel: Sams vijf momenten fotorealistisch maken. Per moment maak je **2 beelden + 2 clips**:

| Bestand | Wat | Hoe in Grok |
|---|---|---|
| `sam0A.jpg` | Vlak vóór het misloopt. Het risico is zichtbaar, maar subtiel (de speler moet het spotten) | Beeld genereren met de referentie van Sam erbij |
| `sam0B.jpg` | Exact hetzelfde kader, net erna | *Edit* van A: "keep everything identical, change only…" |
| `sam0-rust.mp4` | 6 s lus op beeld A: ademen, kijken, stoom van de koffie | *Make video* van A |
| `sam0-impact.mp4` | 6 s: het ongeluk gebeurt, eindigt ongeveer zoals B | *Make video* van A |

**Waarom zo?** De engine blijft dezelfde: A en B zijn de keyframes, en de spot-vraag en de quiz werken erop. De rustclip speelt terwijl de speler het risico zoekt. De impactclip vervangt de "PLONS!"-flits. Ik lijn de clips daarna pixel-exact uit op de stills en maak de rustclip naadloos. De Engelse audio van Grok haal ik eruit, net zoals bij de AV-simulator.

## Werkwijze

1. **Eerst het referentieblad van Sam** (stap 0). Gebruik dat beeld als bijlage bij elk volgend beeld. Zo blijft het overal hetzelfde gezicht.
2. **Formaat: verticaal 4:5** (zoals nu, 1080×1350). Kies in Grok het staande formaat.
3. Gebruik **B altijd als edit van A**, nooit als nieuw beeld. Anders verspringt de kamer.
4. Is een beeld bijna goed? Edit het dan liever dan opnieuw te genereren.
5. Upload per moment de 4 bestanden. De bestandsnaam maakt niet uit, zeg gewoon welk moment het is.

Prompts staan in het Engels: Grok volgt die preciezer. Plak telkens het **stijlblok** achter de prompt.

### Stijlblok (achter elke beeldprompt plakken)

```
Photorealistic, shot on a 35mm full-frame camera, natural available light, shallow depth of field, realistic skin texture, believable everyday Belgian setting in Bruges, muted warm colour grade, vertical 4:5 composition, no text, no captions, no logos, no watermark.
```

---

## Stap 0. Referentieblad Sam

Voeg het huidige getekende Sam-beeld (`sam0A.jpg`) toe als bijlage:

```
Create a photorealistic character reference of this man as a real person: a 29-year-old Belgian man, slim athletic build, short dark brown hair slightly messy on top, short trimmed dark beard, friendly face, olive green crew-neck t-shirt, dark blue slim jeans with the hems rolled up once. Three views side by side on a plain light grey studio background: front, three-quarter, profile. Neutral expression, even soft studio light.
```

Bewaar het beste resultaat als `sam-ref.jpg` en stuur het mij ook door.

---

## Moment 1 · 07:40 · Waterschade (aanvoerslang wasmachine)

**A** (bijlage: sam-ref.jpg)
```
Saturday morning in a small rented apartment in Bruges. The man from the reference stands in the hallway in white socks, holding a mug of coffee, looking towards an open bathroom door with a puzzled expression. Through the doorway a running front-loading washing machine is visible; its water inlet hose at the back has come loose and a thin spray of water is starting to escape, a small puddle forming on the bathroom tiles. Warm morning light from a window with a view of a Bruges church tower. Wooden floor in the hallway, still dry.
```

**B** (edit van A)
```
Keep the room, framing, lighting and the man identical. Now the hallway floor is covered in a thin layer of water reflecting the light, the loose hose sprays freely, the man has put the mug down and holds both hands on his head in panic. In the doorway at the right stands an angry neighbour in his sixties, bald, grey V-neck sweater, pointing up at the man.
```

**Clip rust** (van A)
```
Static camera. The man blinks, takes a sip of coffee and tilts his head, listening. Steam rises from the mug. In the background the washing machine drum turns and the small spray from the hose flickers. Subtle, calm, no cuts.
```

**Clip impact** (van A)
```
Static camera. The hose at the back of the washing machine suddenly bursts loose and water sprays hard across the bathroom, rushing out over the hallway floor towards the man's socks. He startles and puts the mug down. No cuts, no new people.
```

---

## Moment 2 · 12:30 · Padel (bal over de wand)

**A**
```
An indoor-outdoor padel club near Bruges at midday. The man from the reference, in a dark sports t-shirt and shorts, stands near the back glass wall of the court, racket raised high, grinning, about to smash a yellow padel ball very hard upwards. Just behind and above the glass wall, clearly visible, is a busy café terrace with people at tables, including a woman in her forties with glasses sipping a drink.
```

**B** (edit van A)
```
Keep the court, terrace, framing and light identical. The man now stands frozen with the racket lowered and a shocked face. On the terrace the woman holds her hand to her face, her glasses broken in two on the table, other guests turning towards her. No blood.
```

**Clip rust**: `Static camera. The man bounces the ball twice on his racket, grins and looks up at the glass wall. People on the terrace chat and drink. Calm, no cuts.`

**Clip impact**: `Static camera. The man smashes the ball hard; it flies high over the glass wall and hits the woman on the terrace in the face, her glasses fall onto the table. She reacts in pain, guests stand up. The man freezes. No blood, no cuts.`

---

## Moment 3 · 14:00 · Café (laptop van de werkgever)

**A**
```
A cosy café in the historic centre of Bruges. The man from the reference, now wearing a navy overshirt over his t-shirt, works on a plain silver laptop without any logo at a small wooden table, a glass of beer next to it. Right behind him a waiter carries a large tray full of drinks, walking fast and looking the other way, about to pass very close to the table.
```

**B** (edit van A)
```
Keep the café, framing and light identical. The laptop now lies open on the floor next to the table, beer spilled over the keyboard, the screen black. The waiter crouches with an apologetic face, the man stands up with his hands spread in disbelief.
```

**Clip rust**: `Static camera. The man types on the laptop and takes a sip of beer. Behind him the waiter approaches with the full tray. Calm café atmosphere, no cuts.`

**Clip impact**: `Static camera. The waiter trips on the table leg, the tray tilts, beer spills and the laptop slides off the table onto the floor. The man jumps up. No cuts.`

---

## Moment 4 · 18:00 · Kelder (e-bike gestolen)

**A**
```
The basement storage corridor of a Belgian apartment building, fluorescent light, rows of wooden storage lockers. The man from the reference, in a light jacket with a backpack, has just come down the stairs and looks at his own locker door, which stands slightly ajar. A broken padlock hangs on the door latch, clearly visible but small in the frame.
```

**B** (edit van A)
```
Keep the corridor, framing and light identical. The locker door is now wide open: the storage is empty except for a cut bike lock on the floor where an e-bike stood. The man stands inside the doorway with both hands on his head.
```

**Clip rust**: `Static camera. The fluorescent light flickers slightly. The man walks two steps closer and slows down, frowning at the ajar door. No cuts.`

**Clip impact**: `Static camera. The man pulls the locker door open and sees the empty space where his e-bike was. He steps back in shock. No cuts.`

---

## Moment 5 · 21:30 · Bezoek (losse mat)

**A**
```
Evening in the same rented Bruges apartment, warm lamp light. Friends sit on the sofa with drinks, laughing. The man from the reference stands in the living room. In the foreground a woman around 28 with long auburn hair, jeans and a striped top walks into the hallway towards the bathroom. On the smooth wooden hallway floor lies a small loose rug with one corner curled up, right in her path.
```

**B** (edit van A)
```
Keep the room, framing and light identical. The woman now sits on the hallway floor holding her ankle in pain, the rug shoved aside and crumpled. The friends on the sofa stand up, the man rushes towards her with a worried face. No blood.
```

**Clip rust**: `Static camera. Friends laugh and clink glasses, the woman gets up and walks towards the hallway. Warm, relaxed atmosphere, no cuts.`

**Clip impact**: `Static camera. The woman steps on the loose rug, it slides away under her foot and she falls, landing on the floor and grabbing her ankle. Everyone turns. No cuts.`

---

## Checklist per beeld

- Is het **risico** in A zichtbaar maar niet schreeuwerig? (De speler moet het zelf vinden.)
- Is B **hetzelfde kader** als A?
- Geen tekst, logo's of merknamen (ook niet op de laptop of fiets)
- Sam heeft overal hetzelfde gezicht
