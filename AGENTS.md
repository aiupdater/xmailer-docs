# Pokyny pro agenty – dokumentace xMailer

- Web je postavený na [Mintlify](https://mintlify.com); stránky jsou MDX s YAML frontmatter, nastavení je v `docs.json`.
- Před větší úpravou si přečtěte `.mintlify/product-brief.md` (účel, čtenáři, hranice).
- Mintlify MCP pro úpravy obsahu: `https://mcp.mintlify.com`; dokumentace Mintlify: `https://www.mintlify.com/docs/mcp`.

## Zdroj pravdy

Dokumentace popisuje implementaci v repozitáři [aiupdater/febaEmail.app](https://github.com/aiupdater/febaEmail.app). Každé tvrzení o chování ověřte v jeho kódu (`*.php`, `*.js`) nebo v `PROJECT.md` a `UX-CONTRACT.md`. Nic nedomýšlejte; co nelze ověřit, nepište.

## Terminologie

- Název webu a produktu v dokumentaci: **xMailer**. Označení „FEBA EmailApp“ nepoužívejte. Názvy z kódu (`FEBA_*`, `X-FEBA-Cron-Token`) a firmu FEBA-MONT ponechte beze změny.
- Názvy prvků UI přebírejte přesně z `index.html` aplikace a pište je tučně: **Uložit emaily**, **Nastavení odesílání**.
- Rozlišujte „předání / přijetí poskytovatelem“ a „doručení“; jde o odlišné stavy.

## Styl

- Čeština, vykání, činný rod, krátké věty.
- Nadpisy velkým písmenem jen na začátku.
- Názvy souborů, příkazů, proměnných a cest v `kódu`.
- Každý blok kódu má jazyk.
- Interní odkazy kořenově relativní bez přípony: `/guides/delivery`.

## Hranice obsahu

- Žádné klíče, hesla, tokeny, skutečné adresy kontaktů ani tvrzení o otestované produkci.
- V ukázkách jen domény `example.com`.

## Před odevzdáním

Spusťte `mint validate` a `mint broken-links`. Push na `main` se automaticky nasadí na živý web.
