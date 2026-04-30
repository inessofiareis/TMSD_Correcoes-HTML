# 🏥 Tecnologias Multimédia em Saúde Digital — Fichas HTML

> Repositório com as correções das fichas práticas de HTML da unidade curricular **Tecnologias Multimédia em Saúde Digital**, lecionada na **Escola Superior de Saúde — P.Porto**.

---

## 📁 Estrutura do Repositório

```
📦 tmsd-fichas-html
 ┣ 📂 ficha2-cartao-visita/
 ┃ ┣ 📄 index.html
 ┃ ┣ 📂 images/
 ┃ ┣ 📂 styles/
 ┃ ┣ 📂 scripts/
 ┃ ┗ 📂 fonts/
 ┣ 📂 ficha3-care-now/
 ┃ ┣ 📄 index.html
 ┃ ┣ 📂 images/
 ┃ ┣ 📂 styles/
 ┃ ┗ 📂 scripts/
 ┣ 📂 ficha4-saara/
 ┃ ┣ 📄 index.html
 ┃ ┣ 📂 imagens/
 ┃ ┗ 📂 media/
 ┣ 📂 ficha5-literacia-saude-digital/
 ┃ ┣ 📄 index.html
 ┃ ┣ 📂 paginas/
 ┃ ┃ ┗ 📄 recursos.html
 ┃ ┣ 📂 imagens/
 ┃ ┗ 📂 media/
 ┣ 📂 ficha7-debug-html/
 ┃ ┗ 📄 index.html
 ┗ 📄 README.md
```

---

## 📋 Fichas

### Ficha 2 — Organização de Ficheiros e Primeiros Passos em HTML

**Tema:** Cartão de visita online pessoal

**O que foi desenvolvido:**
- Estrutura organizada de pastas e ficheiros para um projeto web (`/images`, `/styles`, `/scripts`, `/fonts`)
- Página `index.html` com conteúdo pessoal básico

**Elementos HTML aplicados:**
| Elemento | Utilização |
|----------|-----------|
| `<h1>` | Título com o nome |
| `<p>` | Parágrafo descritivo com `<strong>`, `<em>`, `<mark>` |
| `<img>` | Imagem com atributos `alt` e `title` |
| `<ul>` | Lista não ordenada com 3 interesses pessoais |
| `<a>` | Link externo para um site favorito |
| `<hr>` | Linha horizontal a separar secções |
| `<!-- -->` | Comentário a descrever o propósito da página |

---

### Ficha 3 — CareNow

**Tema:** Página promocional de um serviço de saúde digital da clínica CareNow

**O que foi desenvolvido:**
- Página web completa para um serviço de saúde à escolha (ex.: Teleconsulta de Nutrição, Saúde Mental, Fisioterapia online, etc.)
- Estrutura profissional com apresentação, tabela de planos e formulário de marcação

**Elementos HTML aplicados:**
| Elemento | Utilização |
|----------|-----------|
| `<h1>`, `<p>` | Secção de apresentação do serviço |
| `<strong>`, `<em>` | Destaque de palavras-chave |
| `<img>` | Imagem do serviço com `alt` e `title` |
| `<ul>` / `<ol>` | Lista com 3 benefícios/funcionalidades |
| `<a>` | Link externo (SNS/DGS/OMS) e link interno para o formulário |
| `<table>` | Tabela de planos com `<thead>`, `<tbody>`, `<tfoot>`, `colspan`/`rowspan` |
| `<form>` | Formulário de pedido de marcação |
| `<input>` | Campos: texto, email, data, radio, submit |
| `<select>` | Menu de horário preferido |
| `<textarea>` | Campo para observações/sintomas |
| `<label>` | Labels corretamente associadas (acessibilidade) |
| `<fieldset>` + `<legend>` | Agrupamento do formulário *(bónus)* |

---

### Ficha 4 — Saara

**Tema:** Página web informativa sobre episódios de poeiras do Saara e cuidados de saúde

**O que foi desenvolvido:**
- Página completa com HTML semântico sobre o impacto das poeiras do Saara na saúde
- Integração de multimédia local e conteúdo externo incorporado

**Elementos HTML aplicados:**
| Elemento | Utilização |
|----------|-----------|
| `<!DOCTYPE html>` | Declaração do tipo de documento |
| `<html lang="pt">` | Definição do idioma |
| `<meta charset>`, `<meta viewport>`, `<meta description>` | Metadados no `<head>` |
| `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>` | Estrutura semântica completa |
| `<h1>`, `<h2>` | Hierarquia de títulos |
| `<strong>`, `<em>` | Destaque de termos como *partículas*, *saúde respiratória* |
| `<figure>`, `<img>`, `<figcaption>` | Imagem com legenda |
| `<div class="caixa">` | Caixa informativa com recomendações de saúde |
| `<ul>` | Lista com pelo menos 4 recomendações de saúde |
| `<audio>` / `<video>` | Elemento multimédia local com `controls` e `<source>` |
| `<iframe>` | Vídeo externo do YouTube incorporado |
| Entidade HTML | Ex.: `&amp;` no texto da página |
| `<a href="#topo">` | Link de retorno ao topo no rodapé |

---

### Ficha 5 — Ficha de Consolidação HTML — Literacia em Saúde Digital

**Tema:** Mini-site "Guia de Literacia em Saúde Digital"

**O que foi desenvolvido:**
- Mini-site funcional com duas páginas HTML (`index.html` e `paginas/recursos.html`)
- Aplicação integrada de todos os conteúdos HTML estudados ao longo das aulas

**Elementos HTML aplicados:**

**`index.html`**
| Elemento | Utilização |
|----------|-----------|
| `<head>` completo | `charset`, `viewport`, `<title>`, `meta description` |
| Estrutura semântica | `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>` |
| `<nav>` | 4 links internos (`#sobre`, `#recursos`, `#media`, `#contacto`) + 1 link externo em nova aba |
| Secção `#sobre` | `<h2>`, parágrafos com `<strong>`, `<em>` e entidade HTML |
| Secção `#recursos` | Lista `<ul>` com 4 recursos, lista `<ol>` com 3 passos, `<figure>` com imagem e `<figcaption>` |
| Tabela | "Tipos de recursos digitais em saúde" com `<th>`, mínimo 3 colunas e 3 linhas |
| Secção `#media` | `<audio>` ou `<video>` local + `<iframe>` com vídeo do YouTube |
| `<aside>` | Título, parágrafo e 3 links úteis (MDN, W3C, SNS24, OMS) |
| Secção `#contacto` | `<form>` com `<fieldset>`, `<legend>`, `<label>`, campos `required`, `<textarea>`, botão de envio |
| `<footer>` | Copyright, ano e link "Voltar ao topo" |
| `class`, `<div>`, comentários HTML | Pelo menos 2 classes, 1 `<div>` de agrupamento, 1 comentário |

**`paginas/recursos.html`**
| Requisito | Descrição |
|-----------|-----------|
| Estrutura HTML completa | `<!DOCTYPE>`, `<html>`, `<head>`, `<body>` |
| Conteúdo | `<h1>`, parágrafo, lista com 3 recursos, imagem |
| Navegação | Link para voltar ao `index.html` e link direto para `index.html#contacto` |
| Caminhos relativos | Comentário HTML com os 4 caminhos relativos corretos |

**Caminhos relativos (Parte 11):**
```html
<!-- 
  1. De index.html para recursos.html   → paginas/recursos.html
  2. De recursos.html para index.html   → ../index.html
  3. De recursos.html para recurso1.jpg → ../imagens/recurso1.jpg
  4. De index.html para video.mp4       → media/video.mp4
-->
```

**Correção de código (Parte 12):** Ficheiro `correcao.html` com as seguintes correções aplicadas:
- Adição de `lang="pt"` na tag `<html>`
- Fecho correto do `<head>` e `</html>`
- Aspas nos valores dos atributos (`charset`, `src`, `alt`, `href`, `target`)
- Entidade HTML `&lt;` para o símbolo `<` no parágrafo
- Atributo `title` na imagem para acessibilidade

---

### Ficha 7 — Debug HTML

**Tema:** Reestruturação semântica de uma página sobre desinformação em saúde online

**O que foi desenvolvido:**
- Reorganização e correção de um ficheiro HTML mal estruturado
- Foco em semântica, hierarquia de títulos e acessibilidade

**Correções aplicadas:**
| Problema | Solução |
|----------|---------|
| Falta de `<main>` | Conteúdo principal envolvido em `<main>` |
| Navegação mal posicionada | `<nav>` separado do conteúdo principal |
| Conteúdo complementar sem `<aside>` | Links úteis e fontes movidos para `<aside>` |
| Múltiplos `<h1>` | Apenas um `<h1>` principal; subtítulos convertidos em `<h2>` |
| Secções sem agrupamento | Conteúdo dividido em `<section>` temáticas |
| Links sem `id` de destino | Âncoras internas adicionadas com `id` às secções |
| Formulário incompleto | Campos com `<label>` corretamente associadas, `required` e botão de envio |

---

## 🛠️ Tecnologias Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

---

## 📚 Conteúdos Abordados

- ✅ Estrutura base de um documento HTML5
- ✅ Elementos do `<head>` (meta tags, title, charset, viewport)
- ✅ Texto, formatação e entidades HTML
- ✅ Links internos e externos
- ✅ Imagens e figuras (`<figure>`, `<figcaption>`)
- ✅ Listas ordenadas e não ordenadas
- ✅ Tabelas (`<thead>`, `<tbody>`, `<tfoot>`, `colspan`, `rowspan`)
- ✅ IDs, classes e seletores
- ✅ Estrutura semântica (`<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`)
- ✅ Multimédia (`<audio>`, `<video>`, `<iframe>`)
- ✅ Formulários (`<form>`, `<input>`, `<label>`, `<select>`, `<textarea>`, `<fieldset>`)
- ✅ Caminhos relativos
- ✅ Debug e correção de HTML

---

## 🎓 Informação Académica

| Campo | Informação |
|-------|-----------|
| **Unidade Curricular** | Tecnologias Multimédia em Saúde Digital |
| **Instituição** | Escola Superior de Saúde — Politécnico do Porto (P.Porto) |
| **Ano Letivo** | 2025/2026 |

---

*Este repositório destina-se exclusivamente a fins académicos.*
