# Digitaal Dieet bonnetje

Openbare pagina die het deelbare bonnetje van de Digitaal Dieet studie tekent. Het experiment (op Pavlovia) maakt een link naar deze pagina, bijvoorbeeld:

```
https://<gebruikersnaam>.github.io/digitaal-dieet-bonnetje/#v=1&d=entertainment&l=hamster&t=entertainment.45,relatable.25,learning.15&s=38&h=18&a=72&p=TikTok&dt=20261104&lang=nl
```

Alles staat achter het `#`. Dat deel wordt door de browser niet naar de server gestuurd, en de pagina slaat niets op. In de link staan alleen profielwaarden (gerecht, eetstijl, top 3, skip%, uren, gemiddeld cijfer, app, datum, taal), geen naam, deelnemer-ID, school of leeftijd.

## Online zetten (GitHub Pages)

1. Maak op GitHub een nieuwe **openbare** repository, bijvoorbeeld `digitaal-dieet-bonnetje`.
2. Upload `index.html` (en dit `README.md`) naar de hoofdmap.
3. Ga naar **Settings > Pages**, kies bij *Source* "Deploy from a branch", branch `main`, map `/ (root)`, en klik **Save**.
4. Na een minuut of twee staat de pagina op `https://<gebruikersnaam>.github.io/digitaal-dieet-bonnetje/`.
5. Zet dat adres in `experiment-config.json` bij `experiment.bonnetjeUrl`.

Testen: open het adres met de voorbeeldlink hierboven erachter. Zonder geldige link toont de pagina een korte foutmelding.

## Inhoud

- `index.html`: alles in één bestand (tekeningen, teksten, deel- en downloadknop). Het lettertype Archivo (SIL Open Font License) wordt via Google Fonts en jsDelivr geladen.
- Delen werkt via het deelmenu van het apparaat (telefoon, tablet en de meeste laptopbrowsers); anders wordt het plaatje gedownload.
