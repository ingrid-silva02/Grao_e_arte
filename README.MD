# Grão & Arte - Torrefação e Café Especial ☕

> Landing page institucional desenvolvida para a marca fictícia **Grão & Arte**, focada em valorizar a cultura de cafés especiais, métodos de extração artesanais, divulgação de microlotes e o clube de assinatura de grãos selecionados.

---

## 📌 Visão Geral e Objetivo do Projeto

Este projeto consiste no desenvolvimento front-end de uma landing page institucional e responsiva para a **Grão & Arte - Torrefação e Café Especial**.

O objetivo da aplicação é apresentar a marca ao público-alvo (apreciadores de cafés especiais e assinantes de grãos selecionados)[cite: 1], disponibilizando:
* Exibição do catálogo de microlotes exclusivos em cards.
* Apresentação visual do processo artesanal de torra.
* Tabela comparativa dos planos do clube de assinatura mensal[cite: 1, 4].
* Seção de perguntas frequentes (FAQ) interativa[cite: 1, 4].
* Canal direto de contato via botão flutuante integrado à API do WhatsApp[cite: 1, 5].

O desenvolvimento foi realizado simulando um ambiente profissional, aplicando conceitos fundamentais de arquitetura CSS, semântica HTML, acessibilidade, responsividade e separação de responsabilidades[cite: 1].

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **HTML5 Semântico:** Estruturação utilizando tags apropriadas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<details>`, `<summary>`, `<footer>`) para SEO e acessibilidade[cite: 1, 4, 5].
* **CSS3 Modular & Variáveis (`:root`):** Configuração dos tokens do Design System (paleta de cores, fontes, sombras e bordas)[cite: 1, 6].
* **Metodologia BEM (Block Element Modifier):** Padronização rigorosa da nomenclatura de classes e seletores no HTML e CSS[cite: 1].
* **Escala Relativa (`rem` & `%`):** Configuração da escala base do elemento raiz (`html`), resgate do tamanho padrão no `body` e uso exclusivo de unidades relativas para tipografia, espaçamentos e bordas.
* **Unidades de Layout (`%`, `vh`, `vw`):** Construção de layouts fluidos e controle de seções em tela cheia[cite: 2, 4].
* **CSS Flexbox:** Alinhamento dinâmico e distribuição dos elementos do catálogo e planos[cite: 3, 4].
* **Google Fonts:** Importação das tipografias oficiais *Merriweather* e *Open Sans*[cite: 2, 6, 7].
* **Microinterações:** Pseudo-classes (`:hover`) com efeitos de elevação e transição em cards e navegação[cite: 5, 6].

---

## 📂 Organização da Arquitetura de Arquivos

O projeto segue estritamente a separação de responsabilidades, organizando o código em arquivos isolados[cite: 1]:

```text
grao-e-arte/
├── assets/
│   └── images/          # Imagens do projeto e ícones
├── css/
│   ├── base.css         # Reset, variáveis do Design System (:root) e escala de fontes
│   ├── components.css   # Estilos dos componentes (cards, botões, FAQ, header, footer)
│   └── layout.css       # Estrutura de seções, Flexbox e media queries (breakpoints)
├── index.html           # Estrutura HTML5 da landing page
└── README.md            # Documentação oficial do projeto