# gastronomia
Investigação em culinária e território
---


#paulolopes.org — Ecossistema Digital & Soberania Tecnológica

## 1. Arquitetura do Domínio
- **Portal Principal (`paulolopes.org`):** Ponto de entrada, manifesto e índice central do espólio (desenhos, fotografia e portefólio multimédia).
- **Food Blog Auto-Etnográfico (`gastronomia.paulolopes.org`):** Alojado em GitHub Pages (estático em HTML/W3.CSS e Markdown), alimentado por manifestos automáticos em Chez Scheme. Secções: `oficio`, `receitas`, `produtos`, `locais`, `sobre`.
- **Blog Académico de Humanidades (`humanidades.paulolopes.org` ou subpasta):** Arquivo de ensaios e teoria crítica.

## 2. Estrutura de Pastas do Subdomínio de Gastronomia (GitHub)
/gastronomia-paulolopes/
├── index.html
├── style.css
├── generate_manifest.ss
├── manifest.json
├── manifest-all.json
└── md/
    ├── oficio/
    ├── receitas/
    ├── produtos/
    ├── locais/
    └── sobre/
        ├── integral.md
        ├── parte.md
        └── autor.md
