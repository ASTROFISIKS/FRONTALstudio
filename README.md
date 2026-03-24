# FRONTALstudio Website — Export Package
## Maart 2026

### /site/ — Production files (deploy these)
- **index.html** — Homepage. Desktop-metaphor met 4 mappen (STUDIO, CONTACT, MOOD_app.zip, ARCHIEF). Dubbelklik opent subpagina. Trilingue (EN/NL/FR auto-detect).
- **archief.html** — Archief. 56 album covers op pannable blauw canvas. 3D fall-animatie bij openen (7s, S-curve). Alle covers base64 embedded. Klik cover = fullscreen preview. Scroll = zoom. Finale layout door Paulo gepositioneerd.
- **studio.html** — Studio pagina. 13 B&W foto's base64 embedded. Trilingue intro tekst. Gear lists Studio 1 (Paulo) + Studio 2 (Michiel). Scroll-based layout.
- **contact.html** — NOG TE BOUWEN.

### /tools/ — Editor tools (niet deployen, voor aanpassingen)
- **archief-editor.html** — Drag covers, resize, rotate, layer. Export Layout knop → JSON. 56 covers + Paulo's finale posities.
- **studio-editor.html** — EDIT MODE knop. Klik tekstelement → tune font-size, opacity, kleur. Export All Styles → JSON.

### Design specs
- Kleuren: zwart #0a0a0a, blauw #3a4ff0, wit #f0f0f0
- Typografie: Nimbus Sans, fallback Helvetica Neue/Arial
- Grain texture overlay op alle pagina's
- Alle images base64 embedded (self-contained HTML, geen externe dependencies)
- Geen backend, geen build tools, geen npm. Pure HTML/CSS/JS.

### Archief catalogus (56 releases)
STIKSTOF (10): STIKSTOF, /02, Overlast, FBA, FBA Single, Moeras, Ambras, Driedubbeldik, Grondleggers, IKRAAAN-GGZ
Zwangere Guy (14): Verlof Vol.3, Brutaal, Wie Is Guy?, BRUTXXL, Baba Guy, Pourriture Noble (& Lander Ghyselinck), Dit Is Guy., Gorik Pt.2, Papucho, Leven Beter, Serieuze Mensen (ft Faberyayo), Equinox (ft Gala Dragot), Overtreders (& Faberyayo), PUTAIN Soundtrack
S10 ft. ZG: Achter Ramen
JAZZ BRAK (7): BRAK, Autofocus, Pro Slide (ft Roméo Elvis), 2024, Cataract (Chazz ft Jazz Brak), Ronde Cirkels, Sables Mouvantes (ft Absolem)
Brihang: Casco
Low G (4): Schijnheilig, Grootspraak, Troebel, Bestaansreden
Overige: COI-Coi-même, STAB-GOAT Cheese, MeyanDR EP, Domoor-Alles of Niets, Domoor-Weg van Teruggeweest, Riksa Ka Meetsysteem-Was het maar..., Meetsysteem & Victor De Roo, Rachel Sassi & Victor De Roo-Paysages Tristes, Berry-Fred Berry, Alex Deforce & Charlotte Jacobs-Zij, Prutser, RonnyHuana-Get Los III, RonnyHuana-Sorry, Vinci-De Basis, Liesa Vanderaa-Like Foxes Do, ZLDR-Broederlijk Helen, Veck-Gouden Wolken, Alex Deforce & Paulo Rietjens-Tussenbruggen, Stakattak-No Exit

### Gear Studio 1 (Paulo)
Monitoring: PMC 8-2, Neumann KH 120 II
Mics: STAM SA-87T, Lewitt LCT 1040, Neumann TLM 103, AKG C214
Hardware: SPL Tube Vitalizer, Neve 8801, GSSL 4000 (mod), Urei LA-10, Neve Portico II MBP, TL Audio VP1
Interface: Apollo X8, Apollo Twin, M-Audio
Instruments: Arturia Polybrute, Casio CZ3000, NI Maschine+, Roland TR-8S, Tama drumkit

### Gear Studio 2 (Michiel)
Monitoring: PMC 6-2, Yamaha NS-10M, Beyerdynamic DT 770 Pro (×3)
Mics: AEA R44 CXE, Neumann U87 vintage (modded '70s), Beyerdynamic M160 (×2), EV 635A, EV RE11, AKG D12E, Revox D19
Hardware: Chandler TG2, RS124, LTD-2, Thermionic Culture Swift EQ + Snow Petrel, AKG BX5, Cranesong HEDD Quantum
Interface: UAD Apollo X8, UAD Octo Satellite, Pro Tools Studio, Logic Pro
Instruments: Sequential Prophet-5 Rev 4, Moog Concertmate MG-1, Hohner Organa 30, Ace Tone FR6, Korg Mini Pops 120, Epiphone '56 Les Paul Goldtop, Hofner Bass '63, Fender Mustang '03, Sigma DM-15, Fender Vibrochamp '72

### Ruimtelijke context
Anspachlaan 77, 1000 Brussel (bij de Beurs). Studio 1 = Paulo's mix/recording room. Studio 2 = Michiel, apart deel achteraan (voormalige badkamer), bereikbaar via gang. Verbonden via audio/ethernet tielines (kunnen als booth/live room samenwerken). Chill room beneden met straatingang. Verdiep 2: Victor, Laurens, Stab, Peet.
