# Equilíbrio em Pontos — protótipo de webdocumento educativo

Protótipo de baixa fidelidade do produto educacional do projeto de pesquisa
**"Equilíbrio em Pontos: desenvolvimento e validação com usuários de um material
educacional digital sobre autocuidado da ansiedade e da saúde mental baseado na
Medicina Tradicional Chinesa"** — Mestrado Profissional em Educação, Gestão e
Difusão em Biociências (MP-EGeD/UFRJ).

> ⚠ **Este é um protótipo para teste de formato.** O conteúdo é ilustrativo e
> será substituído pelo resultado da revisão de literatura do projeto.

## Estrutura

| Página | Conteúdo |
|---|---|
| `index.html` | Apresentação: o que o material é e o que não é |
| `ansiedade.html` | Módulo 1 — Entenda a ansiedade |
| `mtc.html` | Módulo 2 — Conheça a MTC (como racionalidade médica) |
| `pratica.html` | Módulo 3 — Ficha de prática padronizada (exemplo ilustrativo) |
| `seguranca.html` | Módulo 4 — Cuidados, limites, mitos e encaminhamento |
| `css/style.css` | Estilo responsivo + regras de impressão (PDF) |

## Características

- HTML/CSS estático, sem JavaScript — sem login, banco de dados ou rastreamento;
- responsivo (celular e computador), mobile-first;
- acessibilidade: contraste alto, foco visível, link "pular para o conteúdo",
  texto alternativo nas ilustrações, marcação semântica;
- versão PDF: basta abrir a página e usar **Ctrl+P** (as regras de impressão já
  preparam o layout para exportação).

## Como visualizar localmente

Abra `index.html` no navegador, ou sirva a pasta com qualquer servidor estático,
por exemplo:

```bash
python -m http.server 8080
```

e acesse `http://localhost:8080`.

## Publicação

Hospedado via GitHub Pages a partir da branch `main`.

---

Este material não substitui avaliação, diagnóstico ou tratamento profissional.
Em situação de crise: **CVV 188** (24h, gratuito).
