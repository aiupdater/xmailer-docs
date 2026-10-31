# Dokumentace xMailer

Zdroj české dokumentace k aplikaci [febaEmail.app](https://github.com/aiupdater/febaEmail.app), publikované přes Mintlify na https://xmailer.mintlify.site.

## Struktura

| Cesta | Obsah |
| --- | --- |
| `docs.json` | Nastavení webu a navigace. |
| `index.mdx`, `quickstart.mdx` | Úvod a první kroky. |
| `guides/` | Návody pro obsluhu aplikace. |
| `admin/` | Instalace a provoz pro správce. |
| `.mintlify/product-brief.md` | Kontext pro autory a agenty; na webu se nezobrazuje. |

## Úpravy a náhled

Nainstalujte [Mintlify CLI](https://www.npmjs.com/package/mint) a v kořeni repozitáře spusťte náhled:

```bash
npm i -g mint
mint dev
```

Náhled běží na `http://localhost:3000`. Před odesláním změn spusťte kontroly:

```bash
mint validate
mint broken-links
```

Nová stránka se v navigaci objeví až po přidání do `docs.json`.

## Nasazení

Mintlify sleduje větev `main` tohoto repozitáře. Každý push na `main` se automaticky nasadí na živý web.
