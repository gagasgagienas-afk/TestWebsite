# VERA Analysis — statinis svetainės archyvas

Šis katalogas yra paruoštas iš viešai pasiekiamo projekto puslapio. Jame yra lokalizuotas HTML, JavaScript, CSS ir viešai naudotos vaizdinės medžiagos kopijos.

## Paleidimas kompiuteryje

Rekomenduojama paleisti per vietinį HTTP serverį, nes kai kurie naršyklės režimai riboja `file://` failų veikimą:

```bash
python3 -m http.server 8080
```

Tada atidarykite <http://localhost:8080>.

## Diegimas

Įkelkite viso šio katalogo turinį į savo statinio hostingo paslaugą, pavyzdžiui, Netlify, Vercel, GitHub Pages, Cloudflare Pages arba į savo serverio viešą katalogą. Pagrindinis failas yra `index.html`; `404.html` skirtas hostingo paslaugoms, kurios palaiko atsarginį 404 puslapį.

## Pastaba

Tai yra sugeneruotas statinis leidinys iš viešo diegimo. Originalus Manus projekto šaltinio kodas, redagavimo istorija, serverio funkcijos ir nevieši projekto nustatymai į šį archyvą neįtraukti.
