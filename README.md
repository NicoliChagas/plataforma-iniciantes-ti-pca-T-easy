# T‑Easy — Plataforma de Conhecimento para Iniciantes em TI (PCA)

**Link público:** [https://nicolichagas.github.io/plataforma-iniciantes-ti-pca-T-easy/](https://nicolichagas.github.io/plataforma-iniciantes-ti-pca-T-easy/)

Projeto acadêmico (PCA – Introdução às Aplicações Web - Atividade 2) com foco em **inclusão**, **acolhimento** e **aprendizagem guiada** para quem quer iniciar na TI — aqui não existem perguntas “idiotas”.
#Projeto em andamento, 50% concluído.
---

## Objetivo

Facilitar o primeiro contato com TI oferecendo:

* **Teste de área** para sugerir uma trilha (dev, infra, cloud, observabilidade, dados).
* **Trilhas de aprendizado** com passos simples e progressivos.
* **Espaço de perguntas** (Q&A) salvo localmente, com perguntas básicas já semeadas e respostas claras.
* **Badges e gráfico de progresso** para motivação inicial.

> Esta versão é um **protótipo funcional (v0.5)**, 100% front‑end (HTML/CSS/JS), ideal para demonstração em vídeo (1–5 min) e avaliação.

---

## Como rodar

Sem dependências. Basta abrir o `index.html` no navegador.

1. Baixe/clique duas vezes no `index.html` **ou** use o VS Code com a extensão **Live Server**.
2. Acesse as seções **Teste de Área**, **Trilhas**, **Perguntas**, **Progresso**.
3. O armazenamento usa **LocalStorage** (não há backend nesta versão).

Publicação: via **GitHub Pages** (Deploy from Branch → main → /root). Link acima.

---

## Tecnologias

* **HTML5**, **CSS (Tailwind via CDN)**, **JavaScript (ES6+)**
* **Chart.js** (gráfico de progresso)
* **LocalStorage** (persistência no navegador)

---

## Estrutura do projeto

```
/
└── index.html   # Arquivo único com markup, estilos (Tailwind CDN) e JS do protótipo
```
