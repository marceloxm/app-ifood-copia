# 🍔 App iFood (Clone da Interface Inicial)

Projeto desenvolvido em **React Native** com **Expo** como desafio prático da **[Digital Innovation One (DIO)](https://dio.me)**, simulando a tela principal de um aplicativo de delivery de comida.

## ✨ Principais Funcionalidades
- **Carrossel de Banners** e **Filtro de Categorias** (lanches, pizza, japonesa, etc.).
- **Listagem de Restaurantes** com nota, distância, tempo de entrega e frete.
- **Navegação** entre telas com React Navigation e gerenciamento de estado via **React Hooks** (`useState`, `useEffect`).
- **API Fake** utilizando `db.json` com JSON Server.

## 🛠️ Tecnologias
- **React Native** & **Expo** (`app.json`, `babel.config.js`)
- **React Navigation**
- **Yarn** / **npm** (`package.json`, `yarn.lock`)

## 📂 Estrutura do Repositório
```text
app-ifood-copia/
├── assets/           # Imagens e ícones
├── src/              # Código-fonte (telas, componentes, rotas)
├── app.json          # Configurações do Expo
├── db.json           # Base de dados simulada
├── package.json      # Dependências
└── README.md         # Documentação
```

## 🚀 Como Executar
1. Clone o repositório e acesse a pasta:
   ```bash
   git clone https://github.com
   cd app-ifood-copia
   ```
2. Instale as dependências:
   ```bash
   yarn install
   # ou npm install
   ```
3. Inicie o servidor da API local (se aplicável):
   ```bash
   npx json-server --watch db.json --host 0.0.0.0 --port 3000
   ```
4. Inicie o projeto Expo:
   ```bash
   yarn start
   ```
5. Abra no aplicativo **Expo Go** no seu smartphone ou em um emulador.

## 👨‍💻 Autor
Desenvolvido por **[marceloxm](https://github.com)**.
