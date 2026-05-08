# Fatbike Kuopio - staattinen sivusto

Moderni, nopea ja mobiiliystävällinen yhden sivun toteutus Fatbike Kuopion sähköfatbike-vuokraukselle.

## Paikallinen käynnistys

Sivusto on staattinen HTML/CSS-toteutus eikä vaadi build-vaihetta.

```bash
python3 -m http.server 8000
```

Avaa selaimessa: <http://localhost:8000>

## Muokattavat tiedostot

- `index.html` - sivun sisältö, SEO-metatiedot, schema.org JSON-LD ja rakenteet
- `styles.css` - visuaalinen tyyli, responsiivisuus ja komponentit
- `assets/fatbike-kuopio-illustration.svg` - kevyt SVG-kuvitus hero-osioon
- `assets/fatbike-kuopio-og.svg` - Open Graph -kuva

## Jatkokehityksen TODO

- Korvaa SVG-kuvitus oikealla optimoidulla kuvalla vuokrattavasta Rock Machine Vyöry e50R -pyörästä.
- Lisää tarkka Saaristokaupungin jakelualueen kartta tai tekstikuvaus.
- Lisää reittivinkkeihin oikeat GPX-lataukset ja turvallisuus-/kuntotiedot.
- Lisää mahdollinen analytiikka ja konversioseuranta WhatsApp-painikkeille.
