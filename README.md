# Sobby Runner

Et løbespil for børn. Sobby er en lille grøn trold med hale og store ører, som skal undgå forhindringer.

## Sådan spiller du
Åbn `index.html` i en browser.

- **Hop:** pil op eller mellemrum (eller HOP-knappen på tablet/mobil)
- **Duk:** hold pil ned (eller DUK-knappen)
- **Pause:** P

Man har 3 hjerter. Spillet bliver sværere for hvert niveau (hurtigere, tættere forhindringer, fugle fra niveau 2, store sten fra niveau 3), og det fortsætter, indtil man har mistet alle hjerter.

Sobby bliver mere og mere rød i hovedet for hvert niveau, og smiler mindre og mindre. Han begynder at svede, når man er mindre end 100 point fra sin rekord, og får en rød superhelte-kappe på, når rekorden er slået. På tablet og mobil står knapperne ved siden af eller under spillet, så de ikke dækker Sobby.

**Testfase:** Hver ny version sætter rekorden til 500 (`testHighscore` og `GAME_VERSION` i `index.html`). Tæl `GAME_VERSION` op ved hver ny version; sæt `testHighscore` til `null` for at slå det fra.

**Test af rekord:** Tilføj `#rekord500` i slutningen af linket for at sætte rekorden til 500 (eller et andet tal). `#rekord0` nulstiller rekorden.

Indstillinger som fart og antal liv kan justeres i `CFG` øverst i scriptet i `index.html`.
