# Kralenspel

Een interactief kralenspel voor kinderen van groep 3/4 om aftrekken met tientallen en eenheden te oefenen, gebaseerd op de montessori kralenstaafjes-methode. Gebouwd als één HTML-bestand zonder dependencies.

🔗 **Live spelen:** [colorcodednl.github.io/Kralenspel](https://colorcodednl.github.io/kralenspel/)

---

## Wat het doet

Een som zoals "85 − 16 = ?" verschijnt bovenaan. Het kind:

1. **Legt het startgetal neer** met gouden tienstaven en een gekleurde eenheden-staaf (1 t/m 9, montessori-kleurcodering).
2. **Trekt af** door kraaltjes weg te tikken — los, of in één keer een hele tienstaaf. Is een tiental nodig om te wisselen, dan tikt het kind gewoon een kraaltje binnen die staaf weg.
3. **Typt het antwoord** in met een cijferpad, nadat het bord klopt met de uitkomst.

Bij een fout krijgt het kind een korte, visuele hint (pijl + kort woord, en een knipperende ✕ op de staaf die niet klopt) in plaats van een lange tekstmelding — gemaakt met groep 3/4 in gedachten.

---

## Kenmerken

- Geen installatie — gewoon `index.html` openen in de browser
- Werkt op iPad, tablet en desktop
- Montessori-kleurcodering: 1=rood, 2=groen, 3=roze, 4=geel, 5=lichtblauw, 6=paars, 7=wit, 8=bruin, 9=donkerblauw, 10=goud
- Kraaltjes vervagen opaak in plaats van te verdwijnen, zodat het kind altijd kan terugtikken zonder dat de layout verspringt
- Confetti-animatie bij een goed antwoord
- Sommen van 20–99, willekeurig gegenereerd

---

## Gebruik

```bash
git clone https://github.com/ColorcodedNL/Kralenspel.git
open index.html
```

Of speel direct online via GitHub Pages: https://colorcodednl.github.io/Kralenspel/

---

## Techniek

- Puur HTML/CSS/JavaScript — geen frameworks, geen build-stap
- Alle logica in één bestand

---

## Licentie

MIT — gebruik en pas gerust aan.
