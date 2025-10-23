# Recomeço — Plataforma de Apoio a Mulheres

Projeto front-end desenvolvido por **Iana Cunha dos Santos** para a disciplina de Desenvolvimento Web — Entrega II.  
Tema: **Recomeço** — Aurora da Fênix.  
Objetivo: Criar uma interface visual profissional, responsiva e acessível para uma ONG fictícia que apoia mulheres em situação de vulnerabilidade.

---

## 🌐 Visão Geral

A plataforma **Recomeço** oferece acolhimento, capacitação e suporte emocional, jurídico e profissional para mulheres que desejam reescrever suas histórias.  
O site apresenta a missão da ONG, seus projetos ativos, depoimentos reais, formulário de voluntariado e canal de contato.

---

## 🧩 Estrutura do Projeto
recomecco/ ├── index.html               # Página inicial ├── sobre.html               # Informações sobre a ONG ├── projetos.html            # Lista de projetos ativos ├── voluntarias.html         # Formulário de inscrição para voluntárias ├── contato.html             # Formulário de contato ├── depoimentos.html         # Histórias inspiradoras de recomeço ├── README.md                # Documentação do projeto ├── css/ │   ├── variaveis.css        # Design system: cores, fontes, espaçamentos │   ├── layout.css           # Grid, responsividade e estrutura geral │   ├── componentes.css      # Botões, cards, formulários, modais, badges │   └── style.css            # Estilos específicos por página ├── js/ │   └── menu.js              # Menu interativo (dropdown + mobile) └── imagens/ ├── logo.png             # Logotipo da ONG ├── hero.jpg             # Imagem principal da home ├── projeto-1.jpg        # Imagens dos projetos ├── voluntaria-1.jpg     # Imagem de voluntária └── depoimento-1.jpg     # Imagem de depoimento
---

## 🎨 Sistema de Design

- Paleta de cores com 8 tons (primárias, secundárias e neutras)
- Tipografia hierárquica com 5 tamanhos de fonte
- Espaçamento modular: 8px, 16px, 24px, 32px, 48px, 64px
- Gradientes personalizados e acessibilidade visual

---

## 📐 Layout e Responsividade

- Grid de 12 colunas com breakpoints para:
  - 1200px
  - 992px
  - 768px
  - 576px
- Flexbox para alinhamento interno de componentes
- Layout adaptado para desktop, tablet e mobile

---

## 🧠 Componentes Interativos

- Menu principal com dropdown e hambúrguer responsivo
- Cards com imagem, texto e badges de status
- Botões com estados visuais (`hover`, `focus`, `disabled`)
- Formulários com validação visual e feedback
- Modais e alertas simples
- Sistema de badges para categorização de projetos

---

## 🚀 Como Executar

1. Clone ou baixe o repositório:
   ```bash
   git clone https://github.com/ianika-code/recomecco.git

