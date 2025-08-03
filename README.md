# SEO Atelier - Content Repository

Repository dedicata ai contenuti del sito SEO Atelier.

## Struttura

```
content/
├── blog/
│   ├── seo-tecnico/          # Articoli SEO tecnico
│   ├── content-strategy/     # Strategia contenuti
│   ├── local-seo/           # SEO locale
│   ├── ai-automazione/      # AI e automazione
│   ├── performance-ux/      # Performance e UX
│   ├── strategie-avanzate/  # SEO avanzato
│   ├── case-studies/        # Case studies
│   └── news/               # News e aggiornamenti
└── media/
    └── images/             # Immagini articoli
```

## Formato Articoli

Ogni articolo deve essere un file `.md` con frontmatter:

```yaml
---
title: "Titolo dell'articolo"
description: "Descrizione per SEO (max 160 caratteri)"
date: "2025-01-15"
category: "seo-tecnico"
tags: ["core-web-vitals", "performance", "seo-2025"]
author: "SEO Atelier"
featured: false
image: "/media/images/nome-immagine.jpg"
---

Contenuto dell'articolo in Markdown...
```

## Categorie Disponibili

- `seo-tecnico` - SEO Tecnico
- `content-strategy` - Content Strategy  
- `local-seo` - Local SEO
- `ai-automazione` - AI & Automazione
- `performance-ux` - Performance & UX
- `strategie-avanzate` - Strategie Avanzate
- `case-studies` - Case Studies
- `news` - News & Aggiornamenti

## Tag Strategici

Usa max 5 tag per articolo tra:
- `seo-2025`, `google-algorithm`, `core-web-vitals`, `mobile-first`
- `keyword-research`, `content-optimization`, `local-seo`, `e-commerce-seo`
- `ai-seo`, `automation`, `performance`, `ux-design`

## Come Aggiungere un Articolo

1. Crea file `.md` nella categoria appropriata
2. Compila il frontmatter
3. Scrivi l'articolo in Markdown
4. Commit e push
5. Il sito si aggiorna automaticamente!