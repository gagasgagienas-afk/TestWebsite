# VERA Analysis — svetainės archyvas

Šis paketas yra savarankiškas statinis svetainės leidinys, paruoštas iš viešai pasiekiamo projekto puslapio.

## Paleidimas kompiuteryje

Rekomenduojama naudoti vietinį HTTP serverį. Terminale, šiame kataloge, paleiskite:

```bash
python3 -m http.server 8080
```

Tuomet naršyklėje atidarykite `http://localhost:8080`.

## Įkėlimas į hostingą

Įkelkite visus šio katalogo failus į savo statinio hostingo paslaugą arba serverio viešą katalogą. Pagrindinis failas yra `index.html`. Paketą galima naudoti su Netlify, Vercel, GitHub Pages, Cloudflare Pages arba įprastu Apache/Nginx serveriu.

Jei naudojate Netlify, `netlify.toml` faile jau nurodyta, kad publikavimo katalogas yra šis katalogas, o visos maršrutų užklausos nukreipiamos į `index.html`.

## Svarbios pastabos

Archyve lokalizuoti HTML, CSS, JavaScript ir viešai naudojami paveikslėliai. Originalus Manus projekto šaltinio kodas, redagavimo istorija, serverio funkcijos ir nevieši nustatymai į paketą neįtraukti.

Jei svetainę keisite, redaguokite `index.html`, `assets/index.css` ir `assets/index.js`. Prieš viešą publikavimą rekomenduojama patikrinti autorių teises, patentų nuorodas, analitikos nustatymus ir visą svetainės turinį.
