# Kontext dokumentace FEBA EmailApp

## Účel

Interní webová/PWA aplikace FEBA-MONT pro správu kontaktů, skupin, šablon, potvrzení odběru a nabídkových kampaní. Rozesílky používají databázové fronty, SMTP nebo podporované HTTP poskytovatele.

## Čtenáři

Obsluha aplikace a správce vlastní instalace. Toto rozdělení je předpoklad podle interního charakteru produktu a zadání dokumentace repozitáře; nejde o veřejnou službu s registrací zákazníků.

## Hlavní úkoly

1. Přidat a roztřídit kontakty.
2. Uložit, otestovat a aktivovat odesílací propojení.
3. Připravit rozesílku a správně rozlišit předání od doručení.
4. Pro správce: zprovoznit PHP/MySQL, migraci a crony bez vložených tajemství.

## Zdroje a hranice

Ověřeno 31. 10. 2026 podle PROJECT.md, UX-CONTRACT.md, klienta a PHP implementace. Porovnána vzdálená main na 6bbfcf6; proti místnímu HEAD mění statistické SQL a přehled stavu, nikoli popsané toky. MAILGUN_SETUP.md obsahuje historický postup první fáze; současné víceplatformní chování má přednost.

Dokumentace nesmí obsahovat klíče, přihlašovací údaje, adresy skutečných kontaktů ani tvrzení o otestované produkci. Ukázky používají pouze example.com. Dokumentační web má název xMailer (bez .app) a samostatný projekt/subdoménu xmailer na https://xmailer.mintlify.site. Aktuální obsah a nastavení byly 31. 10. 2026 přeneseny a publikovány; původní testovací projekt andreas-pulos byl následně smazán. Úvod je dostupný bez položky ve viditelné navigaci podle uživatelovy úpravy. Zdrojem Mintlify je od 31. 10. 2026 veřejný repozitář aiupdater/xmailer-docs (větev main, kořen); složka docs/ v repozitáři aplikace již neexistuje.
