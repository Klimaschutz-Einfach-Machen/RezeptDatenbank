# Build Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/24d4e3cd-e952-4c87-898c-b0494fc8f3b8/deploy-status)](https://app.netlify.com/sites/rezepte-klimaschutz-einfach-machen/deploys)

# Rezeptdatenbank

Rezeptdatenbank des Projekts "Klimaschutz einfach machen" aus Bielefeld.

## Requirements

- hugo (0.145+) [hugo-website](https://gohugo.ip)
- Markdown-Edito

## Lokaler Test
Hugo-Server lokal starten: 

```shell
hugo server
```

Browser auf [Local](http://localhost:1313)

## Neue Rezepte

Rezepte befinden sich unter `content/posts`. Anlegen mittels `archetype`:
```shell
hugo new posts/<<RezeptName>>.md
```
