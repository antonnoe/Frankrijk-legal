# CLAUDE.md

Repo: Frankrijk-legal

## Wat dit is

Frankrijk-Legal: hub voor de Nederlandse gemeenschap in Frankrijk met een zoekwijzer naar de privacyverklaring en voorwaarden van Franse bedrijven (index.html) en een gids over de Assurance Décennale (decennale.html).

## Live adres

Niet in de repo vastgelegd. De README.md zegt alleen: gehost op GitHub en Vercel.

## Opbouw

- index.html: de Wegwijzer, filteren op naam of categorie, links naar privacy en algemene voorwaarden, snelkoppelingen naar Infofrankrijk.com en Nederlanders.fr.
- decennale.html: de Dieptegids met checklist (voortgang in localStorage), garantiecalculator voor de vervaldatum en links naar Légifrance.
- README.md, LICENSE.

## Techniek

Losse statische HTML-bestanden met Tailwind via cdn.tailwindcss.com en Google Fonts (Poppins, Mulish). Geen package.json, geen build, geen api.

## Externe diensten en namen van omgevingsvariabelen

Tailwind-CDN, Google Fonts, externe links naar Légifrance en de sites van de genoemde bedrijven. Geen omgevingsvariabelen.

## Hoe het live gaat

Volgens README.md: Vercel met automatische deploy via GitHub. Er staat geen vercel.json in de repo.

## Regels en besluiten

Bron: README.md, onderdeel Design Richtlijnen (strikt).
- Primaire kleur #800000, accentkleur #fff9e6.
- Koppen (H1 tot en met H3) in Poppins, lopende tekst in Mulish.
- Regelafstand minimaal 1.8em.
- Knoppen met kastanjebruine achtergrond en witte tekst.

Laatst nagelopen: 5 november 2026
