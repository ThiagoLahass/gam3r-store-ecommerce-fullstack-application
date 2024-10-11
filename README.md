# 🎮 **Gam3r Store** - Um ecommerce voltado para Gamers!

_Bem-vindo ao repositório do **Gam3r Store**, uma aplicação Fullstack de e-commerce feita para gamers de verdade! 🕹️_

<p align="center">
  <img src="/media/web-home.png" alt="Mockup da loja Gam3r Store" width="80%">
</p>

<p align="center">
  <a href="https://nestjs.com/">
    <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white" alt="NestJS">
  </a>
  <a href="https://www.postgresql.org/">
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  </a>
  <a href="https://www.prisma.io/">
    <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white" alt="Prisma">
  </a>
  <a href="https://reactjs.org/">
    <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React">
  </a>
  <a href="https://nextjs.org/">
    <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" alt="Next.js">
  </a>
  <a href="https://tailwindcss.com/">
    <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" alt="TailwindCSS">
  </a>
  <a href="https://reactnative.dev/">
    <img src="https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React Native">
  </a>
  <a href="https://expo.dev/">
    <img src="https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white" alt="Expo">
  </a>
</p>

---

## 📦 **Sobre o Projeto**
A **Gam3r Store** é uma loja online onde você pode comprar tudo relacionado a games, desde consoles até periféricos de última geração. Este projeto foi desenvolvido para o meu portfólio pessoal e abrange toda a stack: backend, frontend, core e mobile, com uma arquitetura pensada para ser modular e flexível.

Aqui está o que você vai encontrar neste projeto:

- 🚀 **Backend:** API robusta construída para gerenciar produtos, usuários e pedidos.
- 🎨 **Frontend:** Uma interface elegante e intuitiva desenvolvida para uma ótima experiência do usuário.
- 📱 **Mobile:** Experiência de compra mobile-first com o app Gam3r Store.
- 🛠️ **Core (em `packages/core`):** As regras de negócio e a lógica da aplicação estão separadas das tecnologias e ferramentas, garantindo flexibilidade e independência de frameworks.

---

## 🏗 **Monorepo com Turborepo**

Este projeto utiliza o **Turborepo** para gerenciar múltiplos pacotes e aplicações no mesmo repositório.

### **Apps e Pacotes:**

- **backend:** API construída com Node.js
- **frontend:** Aplicação web usando React
- **mobile:** Aplicação mobile usando React Native
- **@gam3r/core:** Pacote que contém as regras de negócio
- **@gam3r/eslint-config:** Configurações do eslint compartilhadas
- **@gam3r/typescript-config:** Arquivos de configuração do TypeScript

---

## 🚀 **Como rodar o projeto**

### Pré-requisitos:
- Node.js (v14+)
- Yarn ou NPM

### Passo a passo:
1. Clone o repositório:
```bash
git clone https://github.com/ThiagoLahass/gam3r-store-ecommerce-fullstack-application.git
```

2. Acesse o diretório do projeto e instale as dependências:
```bash
cd gam3r-store
yarn install
```

3. Rode a aplicação (use *TurboRepo* para monorepos):
```bash
yarn turbo run dev
```

### Build
Para construir todos os pacotes e aplicações:
```bash
yarn turbo run build
```

### Develop
Para rodar em ambiente de desenvolvimento:
```bash
yarn turbo run dev
```

## 🛠️ **Tecnologias utilizadas**

- **Backend:** [![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)](https://nestjs.com) [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org) [![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)](https://www.prisma.io)

- **Frontend:** [![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)](https://reactjs.org) [![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)](https://nextjs.org) [![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)

- **Mobile:** [![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)](https://reactnative.dev) [![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)](https://expo.dev)

- **Core:** Regras de negócio desacopladas, seguindo boas práticas de arquitetura
- **Monorepo:** Turborepo

## 📱 **Mockups e Design**
Para uma prévia da aplicação, confira os mockups no Figma, do projeto [Web](https://www.figma.com/design/0YkvCVWX1JNokdsHlufqyR/Gam3rStore?node-id=0-1&t=ByqB0jN0VRF4Sw6u-1) e também do projeto [Mobile](https://www.figma.com/design/2KkR2QqezLQn5FPa7gaoUB/Gam3rStore---Mobile?t=PMsmr7TGbliPr8T3-1) ou veja abaixo:


### **🛍️ Página Web sobre Informações do Produto**
<div style="display: flex; justify-content: center; margin: 5px 20px">
    <img src="./media/web-product-info.png" alt="Mockup Web Product Info da Gam3r Store">
</div>

### **🛒 Página Web do Carrinho do Usuário**
<div style="display: flex; justify-content: center; margin: 5px 20px">
    <img src="./media/web-cart.png" alt="Mockup Web Cart da Gam3r Store">
</div>

### **📱 Home e Carrinho, respectivamente, da aplicação Mobile**
<div style="display: flex; justify-content: space-around; align-items: center; width: 100%;">
    <img src="./media/mobile-home.png" alt="Mockup Mobile Home da Gam3r Store" style="width: 49%; margin: 10px;">
    <img src="./media/mobile-cart.png" alt="Mockup Mobile Cart da Gam3r Store" style="width: 49%; margin: 10px;">
</div>


## 🌟 **Agradecimento**
Se você leu até aqui, obrigado por dedicar seu tempo para conhecer o projeto *Gam3r Store*! 😄  
Se achou útil e gostou do conteúdo, ficaria muito feliz se você pudesse deixar uma ⭐ no repositório. Isso ajuda bastante! 🚀