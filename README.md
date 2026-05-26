# 🏴‍☠️ One Piece Characters App

Fala! Esse aqui é um projetinho de estudo desenvolvido para praticar os conceitos básicos do **React Native** com **Expo**. O objetivo foi construir uma interface simples que consome dados reais da internet e exibe na tela do celular.

Nesse caso, usei a **Jikan API** (que pega dados do MyAnimeList) para listar os personagens de One Piece. 👒

## 🚀 Tecnologias e Ferramentas
- React Native
- Expo
- JavaScript
- [Jikan API v4](https://docs.api.jikan.moe/) (Fonte dos dados)

## 🧠 O que foi praticado?
Como é um projeto focado em aprendizado, o código explora os seguintes conceitos:
* **Gerenciamento de Estado:** Uso do hook `useState` para guardar a lista de personagens.
* **Ciclo de Vida e Requisições Assíncronas:** Uso do `useEffect` com `fetch` para buscar os dados na API assim que o app é aberto.
* **Listas Performáticas:** Uso do componente `FlatList` com a propriedade `keyExtractor` para renderizar os itens sem travar o app.
* **Imagens da Web:** Uso do componente `<Image>` para carregar as fotos dos personagens direto das URLs da API.
* **Estilização:** Flexbox e `StyleSheet` para criar os "cards" dos personagens.

## 💻 Como rodar o projeto

Se quiser testar na sua máquina, é super simples. Você só precisa ter o Node.js instalado.

1. Instale as dependências do projeto:
npm install

2. Inicie o servidor do Expo:
npx expo start

3. Escaneie o QR Code com o aplicativo Expo Go no seu celular, ou aperte a para abrir no emulador de Android / i para o emulador de iOS.

Feito com ☕ para praticar e evoluir nos estudos!
