Rick & Morty Characters List

Aplicativo desenvolvido para a disciplina Programação para Dispositivos Móveis I – 4º Semestre
Prof.: João
Atividade Prática: Consumo de API + FlatList + Hooks

📌 Objetivo

Criar um aplicativo mobile em React Native que consome a API pública da série Rick and Morty, renderizando uma lista de personagens com uso de:

useState

useEffect

FlatList

Boas práticas de componentes e layout

🚀 Funcionalidades Implementadas
✔ Consumo da API pública:

https://rickandmortyapi.com/api/character

✔ Renderização dos dados:

Cada personagem é exibido em um card, contendo:

🖼️ Imagem

🏷️ Nome

💀 Status (Alive / Dead / Unknown)

🧬 Espécie

🔢 ID

✔ Técnicas obrigatórias aplicadas:

Armazenamento dos dados com useState

Requisição via useEffect

Lista exibida com FlatList

keyExtractor utilizando o id

Layout com:

Card com borda e padding

Imagem destacada

Nome estilizado

Espaçamento entre itens

⭐ Funcionalidades Bônus (se implementou, deixar marcado)

Caso tenha incluído:

 Indicador de carregamento (ActivityIndicator)

 Tratamento e exibição de erro

 Botão "Recarregar lista"

 Busca por nome com TextInput

 Paginação simples

🛠️ Tecnologias Utilizadas

React Native (Expo)

JavaScript

API REST pública – Rick and Morty API

Hooks (useState, useEffect)

📂 Estrutura Simplificada do Projeto
📁 RickMortyApp
 ┣ 📁 src
 ┃ ┣ 📁 components
 ┃ ┗ 📁 screens
 ┣ App.js
 ┣ package.json
┗ README.md

▶️ Como Rodar o Projeto
1. Clonar o repositório
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git

2. Acessar a pasta
cd NOME-DO-REPOSITORIO

3. Instalar dependências
npm install

4. Executar o app
npm start


Ou, se preferir:

expo start

5. Abrir no dispositivo

No celular → App Expo Go

No emulador Android/iOS → digitar a ou i no terminal

