# Links App

Este é um aplicativo de gerenciamento de links desenvolvido com React Native e Expo no Minicurso de React Native da RocketSeat. Ele permite que os usuários adicionem, visualizem e removam links categorizados.

## Funcionalidades

- **Adicionar Link**: Permite adicionar um novo link com nome, URL e categoria.
- **Visualizar Links**: Exibe uma lista de links filtrados por categoria.
- **Remover Link**: Permite remover um link existente.

## Instalação

1. Instalar o Node.js

Para rodar o React Native com Expo, precisamos do Node.js.

Acesse o site oficial: https://nodejs.org/pt

Baixe e instale a versão LTS (Long Term Support).

Após a instalação, verifique se está instalado corretamente rodando no terminal

```
node --version
npm --version
```

Isso deve exibir as versões do Node.js e do npm.

2. Instalar o Expo CLI

Expo CLI é a ferramenta para gerenciar projetos Expo.

No terminal, execute:

```ssh
npm install -g expo-cli
```

Para verificar se a instalação foi bem-sucedida:

```ssh
expo --version
```

Isso deve exibir a versão do Expo CLI.

3. Clone o repositório:

```sh
git clone https://github.com/HermannDouglas/links.git
```

2. Navegue até o diretório do projeto:

```sh
cd links
```

3. Instale as dependências:

```sh
npm install
```

## Executando o Projeto

Para iniciar o aplicativo, execute:

```sh
npx expo start
```

Isso abrirá o Expo Developer Tools no seu navegador. A partir daí, você pode executar o aplicativo em um emulador Android/iOS ou em um dispositivo físico usando o aplicativo Expo Go.

## Estrutura de Código

### index.tsx

Este arquivo contém a tela principal do aplicativo, onde os links são listados e filtrados por categoria. Ele utiliza componentes como Link, Option e Categories.

### add-link.tsx

Este arquivo contém a tela de adição de novos links. Ele permite que o usuário insira o nome, URL e categoria do link.

### link-storage.ts

Este arquivo gerencia o armazenamento dos links usando AsyncStorage. Ele fornece funções para obter, salvar e remover links.

## Dependências

- react
- react-native
- expo
- @react-native-async-storage/async-storage
- @expo/vector-icons
- expo-router
