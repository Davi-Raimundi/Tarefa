# Consciência Negra — Site Estático

**Objetivo:** Projeto educacional com 3 páginas sobre Consciência Negra (História, Personalidades, Desafios & Ações). Feito com HTML, CSS e JavaScript puro.

---

## Links
- **Site publicado (GitHub Pages):** _[cole aqui a URL após publicar]_  
- **Repositório:** _[cole aqui o link do repositório GitHub]_

> Eu gerei todo o código e um arquivo pronto para envio. **Não publiquei no GitHub por você** — siga os passos *Publicação* abaixo.

---

## Conteúdo das páginas
- **index.html** — História e contexto (Zumbi dos Palmares, Lei 10.639/03, 20 de novembro).
- **personalidades.html** — Mini-biografias e filtro interativo por área (Artes, Ciência, Política, Esporte).
- **acoes.html** — Desafios atuais (racismo estrutural) e ações/organizações.

## Tecnologias
- HTML5 semântico, CSS3 (externo), JavaScript (modesto).
- Projetado para ser responsivo e acessível.

## Estrutura de pastas
```
/ (raiz)
  index.html
  personalidades.html
  acoes.html
  /css/styles.css
  /js/main.js
  /assets/images/*.svg
  /assets/icons/*.svg
  README.md
  google_doc_links.txt
```

## Acessibilidade (A11y) aplicadas
- Landmarks semânticos: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- Foco visível (`:focus`), skip link, aria-labels em controles, contraste pensado para modo escuro.
- `alt` descritivo em todas as imagens.

## Performance
- Imagens vetoriais (SVG) criadas localmente para reduzir peso.
- `loading="lazy"` nas imagens que estão abaixo da dobra.
- CSS e JS minimalistas.

## Como publicar no GitHub Pages (passo a passo)
1. Crie um repositório público no GitHub (ex.: `consiencia-negra-site`).
2. Clone localmente ou faça upload dos arquivos (certifique-se de que `index.html` está na raiz).
3. Commit e push para a branch `main`.
4. No GitHub → **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Aguarde alguns minutos e acesse `https://seu-usuario.github.io/nome-do-repo/`.
6. Insira o link do site e do repositório no `google_doc_links.txt` e depois cole no Documento Google.

## Créditos e licenças
- Imagens: todas as ilustrações SVG foram geradas como parte do projeto (licença MIT) — atribuição no README.
- Fontes: uso de fontes do sistema para simplicidade (sem dependência externa).
- Referências:
  - IBGE — dados e estudos sobre população.
  - Lei 10.639/03 — texto legislação.
  - UNESCO — materiais sobre educação inclusiva.

## Referências (sugestões)
- https://www.ibge.gov.br
- https://www.planalto.gov.br (texto da lei 10.639/2003)
- https://pt.unesco.org

---

## Checklist de entrega
- [x] 3 páginas com conteúdo e imagens com `alt`.
- [x] Navegação funcional.
- [x] Responsivo (mobile ≤480px).
- [x] A11y básica (landmarks, foco, contraste, aria-*).
- [x] Imagens otimizadas (`loading="lazy"`).
- [ ] Publicar no GitHub Pages — **faça você mesmo** seguindo o passo a passo acima.

--- 

Obrigado — se quiser, eu posso:
- Gerar um *commit-ready* script de terminal (bash) para facilitar o upload ao GitHub.
- Criar variação de tema claro/escuro mais avançada.
