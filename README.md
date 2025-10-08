# Portfólio Pessoal Moderno

Este repositório contém o código-fonte de um portfólio pessoal moderno, projetado para desenvolvedores e profissionais de tecnologia exibirem sua experiência profissional, projetos e habilidades técnicas.

## 📖 Sumário

* [Sobre o Projeto](#-sobre-o-projeto)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Funcionalidades](#-funcionalidades)
* [Como Executar Localmente](#-como-executar-localmente)
* [Como Personalizar](#-como-personalizar)
* [Build e Deploy](#-build-e-deploy)

## 🌟 Sobre o Projeto

O objetivo deste projeto é fornecer um template limpo, responsivo e fácil de personalizar. A estrutura foi construída com tecnologias modernas para garantir uma ótima performance e uma experiência de usuário agradável. É a ferramenta perfeita para quem busca apresentar seu trabalho de forma profissional e atraente.

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias e ferramentas:

* **Framework:** [React](https://react.dev/)
* **Linguagem:** [TypeScript](https://www.typescriptlang.org/)
* **Build Tool:** [Vite](https://vitejs.dev/)
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/)
* **Ambiente de Execução:** [Node.js](https://nodejs.org/)

## ✨ Funcionalidades

A estrutura do portfólio é dividida nos seguintes componentes modulares:

* **Header:** Navegação principal e links de contato.
* **Hero:** Seção inicial de apresentação.
* **About:** Uma breve biografia sobre você.
* **Skills:** Exibição das suas habilidades e competências técnicas.
* **Experience:** Linha do tempo da sua experiência profissional.
* **Projects:** Galeria para destacar seus principais projetos.
* **Footer:** Rodapé com informações de copyright e links adicionais.

## 🏁 Como Executar Localmente

Siga os passos abaixo para configurar e executar o projeto em sua máquina local.

**Pré-requisitos:**
* **Node.js**: Certifique-se de ter o Node.js instalado.

**Passos:**

1.  **Clone o repositório:**
    ```sh
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **Instale as dependências:**
    ```sh
    npm install
    ```

3.  **Execute o servidor de desenvolvimento:**
    ```sh
    npm run dev
    ```

4.  Abra seu navegador e acesse `http://localhost:3000` para visualizar a aplicação.

## 🔧 Como Personalizar

Para adicionar suas próprias informações, você precisará editar os arquivos onde os dados do portfólio estão armazenados. A estrutura de dados para as seções principais está definida em `types.ts`.

* **Experiências (`ExperienceItem`):** Adicione ou modifique suas experiências profissionais, incluindo cargo, empresa, período e descrição.
* **Projetos (`Project`):** Insira os detalhes dos seus projetos, como título, descrição, tags, imagem e links para o repositório ou versão ao vivo.
* **Habilidades (`Skill`):** Liste suas habilidades técnicas, incluindo o nome e um ícone correspondente.

Procure nos componentes (dentro de `/components`) onde esses dados são importados e altere-os para refletir sua trajetória.

## 📦 Build e Deploy

Quando seu portfólio estiver pronto, você pode gerar a versão de produção otimizada.

1.  **Execute o script de build:**
    ```sh
    npm run build
    ```
    Este comando cria uma pasta `dist` com todos os arquivos estáticos da sua aplicação.

2.  **Deploy:**
    Faça o deploy do conteúdo da pasta `dist` em qualquer serviço de hospedagem de sites estáticos, como:
    * [Google Cloud](https://cloud.google.com/)
    * [Vercel](https://vercel.com/)
    * [Netlify](https://www.netlify.com/)
    * [GitHub Pages](https://pages.github.com/)

