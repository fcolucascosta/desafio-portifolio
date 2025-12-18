# 🚀 Portfólio Pessoal - Lucas Costa

> Desafio de desenvolvimento front-end proposto como projeto relâmpago pela Alpha Edtech.

---

## 💻 Sobre o Projeto

Este projeto consiste no desenvolvimento de um **Portfólio Pessoal Online** para exibir projetos e habilidades técnicas. O objetivo principal foi criar uma aplicação web utilizando **HTML5 Semântico** e **CSS3 Puro** (sem frameworks), com foco total em responsividade, acessibilidade e boas práticas de engenharia de software (manutenibilidade e escalabilidade).

A interface foi desenhada no Figma e codificada pensando na experiência do usuário desde dispositivos móveis pequenos (iPhone SE) até monitores Ultra-Wide (4K).

---

## 🔗 Links Importantes

- **📱 Deploy (Site no Ar):** [Acesse o Portfólio Aqui](https://fcolucascosta.github.io/desafio-portifolio/)
- **🎨 Protótipo Figma:** [Ver Design no Figma](https://www.figma.com/design/1qQWZG0dqaN3nICLOO9Spi/portifolio?node-id=0-1&p=f&t=qtDzGiGj7gKvWzho-0)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica (`header`, `nav`, `main`, `section`, `article`, `footer`).
- **CSS3:**
  - **CSS Variables:** Para consistência de cores e fácil manutenção.
  - **CSS Grid & Flexbox:** Para layouts bidimensionais e alinhamentos.
  - **Media Queries:** Responsividade avançada.
  - **Animações:** Transições suaves em hover e interações.
- **JavaScript (Vanilla):** Manipulação leve do DOM para navegação e atualização dinâmica de datas.
- **Git & GitHub:** Versionamento e hospedagem via GitHub Pages.

---

## ✨ Destaques e Funcionalidades

### 1. 🏗️ Arquitetura e Organização
O CSS foi estruturado utilizando **Variáveis (`:root`)**, permitindo a alteração do tema de cores de todo o site alterando apenas 4 linhas de código. O código é limpo e comentado para facilitar a leitura.

### 2. 📱 Responsividade
O layout se adapta a qualquer tela:
- **Mobile (iPhone SE/Small):** Ajustes finos de padding e tipografia para telas a partir de 320px.
- **Desktop:** Grid fluido com `auto-fit` e `minmax`.
- **Ultra-Wide (4K):** Tratamento especial com `clamp()` e escala de fontes para monitores acima de 2000px, evitando que o site fique "esticado" ou ilegível.

### 3. ♿ Acessibilidade
- Uso correto de tags semânticas para leitores de tela.
- Textos alternativos (`alt`) em todas as imagens.
- Contraste de cores verificado.
- Atributos `aria-label` em botões de ícones.

### 4. 🎨 UI/UX
- Efeitos de `hover` em cards e botões.
- Scroll suave entre as seções.
- Favicon personalizado.
- Seleção de texto personalizada (`::selection`) combinando com a identidade visual.

---

## 📂 Estrutura de Pastas

```text
/
├── assets/            # Imagens globais e ícones (SVG/PNG)
├── css/
│   └── styles.css     # Folha de estilos principal do Portfólio
│
│
├── projects/          # Projetos desenvolvidos no curso
│   ├── cep/           # Aplicação de Consumo de API (Clima/CEP)  
│   └── css/           # Aplicação de css responsivo
│       
├── index.html         # Página Principal (Portfólio)
└── README.md          # Documentação do projeto