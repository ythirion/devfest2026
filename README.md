# Le bon chasseur, le mauvais chasseur, et le bon test

[![Publish Slides](https://github.com/ythirion/devfest2026/actions/workflows/slides.yml/badge.svg)](https://github.com/ythirion/devfest2026/actions/workflows/slides.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> "Le mauvais test, il assert un truc, il passe au vert. Le bon test, il assert un truc, il passe au vert… mais c'est un bon test."

![Le bon chasseur, le mauvais chasseur, et le bon test](public/cover.webp)

Vu de loin, les deux tests se ressemblent : verts, rapides, présents dans la CI depuis toujours. Vu de près, un seul des deux protège vraiment quelque chose.

## Origine
Slides du talk présenté au [Devfest Dijon 2026](https://devfest.developers-group-dijon.fr/), version courte de l'atelier [Le bon chasseur, le mauvais chasseur, et le bon test](https://github.com/ythirion/le-bon-chasseur-le-mauvais-chasseur-et-le-bon-test) (code, énoncés et solutions).

## Les histoires
Les chasseurs du Bouchonnois font appel à nous pour faire évoluer leur système. La CI est verte, le coverage affiche de bons chiffres... mais plus personne n'ose toucher au code.

1. **Le bon test ne ment pas** : la chasse aux mutants
2. **Le bon test, on le lit** : Test Data Builders, Object Mothers et assertions métier
3. **Le bon test couvre ce que tu n'as pas pensé à tester** : le Property-Based Testing
4. **Le bon test protège l'architecture** : les tests d'architecture avec `ArchUnitNET`

## Slides
En ligne : **https://ythirion.github.io/devfest2026/**

```bash
npm install
npm run dev     # http://localhost:3030
npm run build   # build statique dans dist/
npm run export  # export en PDF
```
