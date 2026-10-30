# VJ Fastighetsservice – hemsideförslag (utkast)

**Syfte:** Ett första utkast till en enkel landningssida för VJ Fastighetsservice AB (Täby), att visa för Viktor/VJ för godkännande. Tas fram av SM Manager (Erik Mared). Ska ersätta nuvarande placeholder på vjservice.se.

## Filer
- `index.html` – hela sidan i en fil, inline CSS, inga externa beroenden, mobilanpassad.
- `forslag.md` – pitch: sektioner, föreslagen copy och vad som saknas.

## Placeholders (gulmarkerade på sidan)
- `[ATT FYLLA I]`: telefon, e-post, Instagram, Facebook, svarstid, omfattning av IT-tjänster, foto (team/utfört jobb), mottagare för kontaktformuläret (formuläret är inte kopplat – visar bara en alert).
- `[ANTAGANDE]`: upptagningsområde "Täby & norra Stockholm", RUT-avdrag för vissa tjänster, att både engångsjobb och löpande avtal erbjuds.

Verifierat (Bolagsverket): bolagsnamn, org.nr 559531-1241, säte Täby, verksamhet (trädgård, fönsterputs, snöröjning, IT-tjänster, flytthjälp m.m.).
Ingen statistik, recensioner eller kundcitat finns med – lägg bara till om de är verkliga.

## Förhandsgranska
Öppna `index.html` direkt i en webbläsare (dubbelklick), eller:
```
cd /workspace/projects/sm-manager/website/vj-fastighetsservice
python3 -m http.server 8000   # öppna http://localhost:8000
```
Testa mobilvy med webbläsarens utvecklarverktyg (responsivt läge).

## Inför publicering
1. Fyll i alla `[ATT FYLLA I]`, bekräfta/ta bort `[ANTAGANDE]`.
2. Ta bort HTML-kommentaren "UTKAST" och placeholder-markeringarna.
3. Koppla formuläret (t.ex. Formspree/Netlify Forms eller mailto).
4. Publicera på vjservice.se (statisk hosting räcker).
