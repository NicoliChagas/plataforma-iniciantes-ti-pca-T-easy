# T-Easy — Plataforma de Conhecimento para Iniciantes em TI (PCA)

**Link público:**  
[https://nicolichagas.github.io/plataforma-iniciantes-ti-pca-T-easy/](https://nicolichagas.github.io/plataforma-iniciantes-ti-pca-T-easy/)

**Repositório:**  
[https://github.com/NicoliChagas/plataforma-iniciantes-ti-pca-T-easy](https://github.com/NicoliChagas/plataforma-iniciantes-ti-pca-T-easy)

Projeto desenvolvido para o PCA — Introdução às Aplicações Web, com foco em inclusão, acolhimento e acessibilidade ao conhecimento para pessoas que desejam ingressar na área de TI.  
O propósito principal é tornar a TI simples, acolhedora e sem julgamentos.  
Aqui, não existem perguntas idiotas — apenas pessoas aprendendo.

Este é o protótipo funcional (100% concluído) apresentado na etapa final do PCA.


## Objetivo do Projeto

Criar uma plataforma intuitiva e acolhedora para iniciantes, oferecendo:

### Teste de Área de Interesse
Um quiz que sugere automaticamente a área da TI mais alinhada ao perfil do usuário:

- Desenvolvimento (Front/Back)  
- Infraestrutura  
- Cloud & DevOps  
- Observabilidade  
- Dados & Análise  

### Trilhas de Aprendizado com Links Externos
Cada trilha contém passos progressivos, e cada item abre um link relevante, como:

- cursos gratuitos  
- documentações oficiais  
- materiais introdutórios  
- tutoriais práticos  

### Perguntas e Respostas (Q&A)
Espaço onde o usuário pode:

- enviar perguntas sem login  
- armazená-las localmente via LocalStorage  
- visualizar perguntas e respostas básicas pré-semeadas  

### Sistema de Badges + Gráfico de Progresso
- Ao iniciar trilhas, o usuário ganha badges visuais  
- O gráfico em formato *donut chart* exibe o progresso geral  

### Cultura Maker & Projetos Práticos
- Sessão com pequenos projetos para o aluno aprender “fazendo”


## Principais Diferenciais

- Interface moderna, escura e tecnológica com efeitos roxos e tons neon  
- Uso de LocalStorage para simular persistência real, sem backend  
- Trilhas clicáveis com materiais externos confiáveis  
- Sistema Q&A totalmente funcional  
- Design pensado para iniciantes: simples, objetivo e sem jargões técnicos  


## Como Rodar o Projeto Localmente

O projeto é 100% front-end e funciona diretamente no navegador.

### Opção 1 — Abrir direto
1. Baixe o repositório  
2. Clique duas vezes no arquivo `index.html`  
3. O site abrirá no navegador  

### Opção 2 — Usar VS Code (Live Server)
1. Abra a pasta no VS Code  
2. Clique com o botão direito no arquivo `index.html`  
3. Selecione **Open with Live Server**  

### Opção 3 — Acessar via GitHub Pages
A versão hospedada está disponível em:  
https://nicolichagas.github.io/plataforma-iniciantes-ti-pca-T-easy/


## Tecnologias Utilizadas

- HTML5  
- CSS + TailwindCSS (via CDN)  
- JavaScript ES6+  
- Chart.js (gráfico de progresso)  
- LocalStorage (persistência local)  
- GitHub Pages (deploy do projeto)  


## Estrutura do Projeto

```
/
└── index.html   # Arquivo único contendo HTML, JS e estilização via Tailwind CDN
```

