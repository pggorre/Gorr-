# GORRÉ — Menu & huisstijl

Alles staat klaar. Je hoeft alleen nog **producten en collecties toe te voegen**.

## Wat is er toegevoegd / gewijzigd

| Bestand | Wat |
|---|---|
| `sections/gorre-header.liquid` | Nieuwe header: blauwe balk, logo links, mega-menu met alle 9 categorieën |
| `assets/gorre-brand.css` | Huisstijl: kleuren, lettertypes (Bebas Neue + Barlow), header- en menu-styling |
| `assets/gorre-logo.png` | Logo (wit + goud) voor de blauwe balk |
| `assets/gorre-logo-full.png` | Volledig logo mét slogan (voor footer/hero) |
| `assets/gorre-logo-mark.png` | Alleen het G-monogram (voor favicon / klein gebruik) |
| `assets/gorre-logo-original.png` | Origineel logo uit het plan |
| `config/settings_data.json` | Kleurenschema's: wit met navy + goud |
| `sections/header-group.json` | Menu-inhoud + gouden aankondigingsbalk |
| `layout/theme.liquid` | Lettertypes + huisstijl-CSS ingeladen |

**Kleuren:** Midnight Navy `#0C1829` · Brushed Gold `#B89050` · Ivory `#EDE8DF`
**Fonts:** Bebas Neue (koppen) · Barlow (tekst)

## Het menu — categorieën staan al ingevuld

Het menu verwijst naar collecties die jij nog aanmaakt. Maak in Shopify-admin
(**Producten → Collecties → Collectie maken**) collecties met deze *handles*:

- **Kleding** `kleding` → `heren`, `dames`, `kinderen`, `sportkleding`
- **Supplementen** `supplementen` → `proteine`, `pre-workout`, `vitamines`, `creatine`, `mineralen`, `repen`, `dranken`
- **Sport Accessoires** `sport-accessoires` → `shake-flessen`, `tassen`, `weerstandsbanden`, `lifting-straps`, `sport-handdoeken`
- **Digitaal & Coaching** `digitaal-coaching` → `trainingsschemas`, `ebook-discipline`, `coaching`, `sportapp`, `online-cursus`
- **Horloges** `horloges` → `sporthorloges`, `luxe-horloges`, `zwemhorloges`
- **Lifestyle** `lifestyle` → `notitieboek`, `posters`, `geurkaars`, `sleutelhangers`
- **Bundels** `bundels`
- **WAR30** → externe link: https://gorrista.github.io/gorristawar30
- **Premium** `premium` (bestsellers)

> De *handle* is het stukje in de URL (`/collections/`**`heren`**). Shopify maakt
> hem automatisch van de titel; controleer dat hij overeenkomt, of pas de menulink aan.

## Menu aanpassen zonder code

In de Shopify-thema-editor (**Online Store → Customize**) klik je bovenaan op de
**GORRÉ header**. Elke categorie is een blok dat je kunt bewerken:

- **Titel** — naam in het menu
- **Hoofdlink** — de collectie/pagina
- **Subcategorieën** — één per regel: `Label | /collections/handle`
- **Goud accent** — zet de categorie in het goud (zoals WAR30 & Premium)

## Logo wijzigen
Vervang `assets/gorre-logo.png` door een nieuwe versie (wit + goud werkt op de
blauwe balk). Hoogte stel je in via de header-instellingen (32–80 px).
