# FAQ App

Aplicativo Perguntas Frequentes (FAQ) desenvolvido com **React**, **Vite** e **Tailwind CSS**, com uma interface moderna, responsiva e suporte a tema escuro.

> Este projeto está sendo utilizado como parte dos meus estudos em **React** e **Tailwind CSS**, explorando conceitos como componentes reutilizáveis, estado local, responsividade e modo escuro com persistência.

## Live demo

https://faq-app-ruddy.vercel.app

## Funcionalidades

- ✅ Lista dinâmica de perguntas e respostas
- ✅ Expansão individual de cada pergunta
- ✅ Botão para "Expandir/Recolher Todas"
- ✅ Alternância entre tema claro e escuro com **persistência no localStorage**
- ✅ Rolagem suave para o item clicado
- ✅ Interface responsiva e acessível
- ✅ Estilo moderno com gradientes e transições visuais

## Tecnologias Utilizadas

- React
- Vite
- Tailwind CSS
- Boxicons
- Google Fonts

## Instalação e uso

Clone o repositório e instale as dependências:

git clone https://github.com/Juan-s-moreira/Faq-App.git
cd Faq-App
npm install
npm run dev

## Estrutura dos Componentes

src/
├── components/
│ ├── FAQItem.jsx # Componente de cada pergunta
│ └── FAQList.jsx # Lista de perguntas com controles
├── data/
│ └── faqData.js # Perguntas e respostas em formato JSON
├── App.jsx # Layout principal e DarkMode
├── main.jsx # Entrada da aplicação
└── index.css # Tailwind + customizações

## Modo Escuro

O modo escuro é ativado com o botão 🌙 no topo da página e salva a preferência do usuário no localStorage, sendo persistente entre visitas.

## Contribuições

Contribuições são muito bem-vindas!

Sinta-se livre para abrir uma issue ou enviar um pull request com sugestões de melhoria.
