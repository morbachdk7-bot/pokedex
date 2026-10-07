# 🔴 Pokédex

Uma aplicação web inspirada na **Pokédex**, desenvolvida com **HTML, CSS e JavaScript**, que permite pesquisar e navegar pelos Pokémon utilizando dados fornecidos pela **PokéAPI**.

## 📌 Sobre o projeto

O projeto tem como objetivo praticar conceitos de desenvolvimento web e consumo de **API REST**, utilizando JavaScript para realizar requisições e atualizar dinamicamente as informações exibidas na interface.

A aplicação consulta a PokéAPI através de requisições `fetch()` e apresenta o nome, número e imagem animada do Pokémon encontrado.

## ✨ Funcionalidades

- 🔎 Pesquisa de Pokémon por nome ou número;
- ◀️ Navegação para o Pokémon anterior;
- ▶️ Navegação para o próximo Pokémon;
- 🖼️ Exibição da imagem do Pokémon;
- 🔢 Exibição do número do Pokémon;
- 🏷️ Exibição do nome do Pokémon;
- ⚠️ Mensagem de "Not found" quando o Pokémon não é encontrado;
- ⏳ Indicador de carregamento durante a busca.

A pesquisa é realizada através de um formulário e o resultado é renderizado dinamicamente na página.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Utilização |
|---|---|
| **HTML5** | Estrutura da aplicação |
| **CSS3** | Layout, estilização e responsividade |
| **JavaScript** | Lógica e interação |
| **PokéAPI** | Fonte dos dados dos Pokémon |
| **Google Fonts** | Tipografia |

O projeto utiliza a fonte **Oxanium** através do Google Fonts, além de um layout baseado visualmente em uma Pokédex.

## 🌐 API utilizada

O projeto utiliza a:

**PokéAPI**

A API fornece os dados dos Pokémon utilizados pela aplicação.

Endpoint utilizado:

```text
https://pokeapi.co/api/v2/pokemon/{pokemon}
```

A requisição é feita através do método `fetch()` do JavaScript.

## 🔍 Como funciona

Ao iniciar a aplicação, o Pokémon de número **1** é carregado automaticamente.

O usuário pode pesquisar um Pokémon através do campo de busca:

```text
Nome: pikachu
Número: 25
```

Ao enviar o formulário, o valor digitado é convertido para letras minúsculas e utilizado para realizar a consulta na API.

Também é possível utilizar os botões de navegação para avançar ou voltar entre os Pokémon.

## ❌ Pokémon não encontrado

Quando a API não retorna dados válidos, a imagem é ocultada e a aplicação exibe a mensagem:

```text
Not found
```



## 🎨 Interface

A interface utiliza um fundo com gradiente azul e branco, uma imagem de Pokédex e elementos posicionados sobre ela para representar os dados do Pokémon.

O campo de pesquisa possui bordas, sombras e estilização própria para manter a aparência semelhante à interface de uma Pokédex.

## 📂 Estrutura do projeto

```text
pokedex/
│
├── index.html
├── style.css
├── script.js
│
└── images/
    └── ...
```

> Os nomes e arquivos da pasta `images` podem variar de acordo com os recursos utilizados no projeto.

## ⚙️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/pokedex.git
```

### 2. Acesse a pasta

```bash
cd pokedex
```

### 3. Execute o projeto

Abra o arquivo:

```text
index.html
```

Também é possível utilizar a extensão **Live Server** no Visual Studio Code.

> Como a aplicação utiliza a PokéAPI, é necessário ter acesso à internet para realizar as consultas.

## 📚 Objetivo de aprendizagem

Este projeto foi desenvolvido para praticar:

- Manipulação do DOM;
- Eventos em JavaScript;
- Funções assíncronas;
- `async/await`;
- Requisições HTTP com `fetch()`;
- Consumo de API REST;
- Tratamento de resultados;
- Atualização dinâmica de elementos HTML;
- Estilização com CSS.

## 🚀 Possíveis melhorias

Algumas funcionalidades podem ser adicionadas futuramente:

- 📊 Exibição dos atributos do Pokémon;
- 🧬 Tipo(s) do Pokémon;
- ⚡ Habilidades;
- 📏 Altura e peso;
- ❤️ Sistema de favoritos;
- 📱 Melhor adaptação para dispositivos móveis;
- 🔊 Sons;
- 🌙 Modo escuro;
- 🎨 Diferentes temas para cada tipo de Pokémon.

## 👨‍💻 Autor

**Rafael Morbach**

Projeto desenvolvido para fins de estudo e prática em desenvolvimento web.
