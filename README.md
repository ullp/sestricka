# Sestřička

Webová aplikace pro pacienty a lékaře, která pomocí umělé inteligence zjednodušuje administrativu a komunikaci s ordinací.

> Projekt je ve fázi přípravy. Zdrojový kód aplikace zatím v tomto repozitáři není.

## Co aplikace nabídne

- **Shrnutí lékařských dokumentů** – pacient nahraje zprávu z nemocnice, výsledky laboratoře nebo snímek a lékař dostane krátké shrnutí s upozorněním na důležité hodnoty a seznamem změn od poslední zprávy.
- **Zápis do dokumentace z diktování** – lékař nadiktuje průběh vyšetření a systém z toho připraví záznam do dokumentace, doporučení a návrh zprávy.
- **Telefonní asistent** – pacient zavolá a jeho požadavek (například na recept) se zaeviduje a předá lékaři ke schválení, aniž by ordinace musela zvedat telefon.
- **Monitoring chronických pacientů** – pacient pravidelně zapisuje hodnoty (tlak, glykémie, PEF) a lékař dostane upozornění, pokud se trend dlouhodobě zhoršuje.
- **Připomínky a follow-up** – automatické připomínky léků, odběrů a kontrol s možností odpovědět přímo v aplikaci.

O léčbě vždy rozhoduje lékař. Výstupy umělé inteligence slouží pouze jako podpora a lékař je potvrzuje; nejde o diagnózu ani o automatické vystavení receptu.

## Plánované technologie

| Vrstva | Technologie |
| --- | --- |
| Webová aplikace | TypeScript + React (responzivní SPA, instalovatelná jako PWA) |
| Backend | Java, Spring Boot |
| Databáze | PostgreSQL |
| AI a telefonie | poskytovatelé s datovým centrem v EU |

## Stav projektu

- [ ] Návrh produktu a funkčních požadavků
- [ ] Kostra webové aplikace (frontend + backend)
- [ ] Backend a datový model
- [ ] Pilotní provoz v ordinacích

## Struktura repozitáře

| Soubor | Obsah |
| --- | --- |
| `index.html` | webová prezentace projektu na [sestricka.online](https://sestricka.online) |
| `README.md` | tento přehled projektu |
| `CNAME` | vlastní doména pro GitHub Pages |
| `.gitignore` | soubory, které se necommitují (IDE, build výstupy, lokální konfigurace) |

## Kontakt

Nabídky spolupráce a dotazy: _doplnit e-mail_

## Licence

Všechna práva vyhrazena. Obsah tohoto repozitáře nesmí být bez souhlasu autora dále šířen ani používán pro jiné účely.
