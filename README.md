# Integração da POKE-API com Node.js: Página Web com HTML5, CSS3 e JavaScript

## Objetivo

Criar uma página web moderna que consome dados da POKE-API utilizando Node.js como backend, exibindo informações de Pokémons de forma dinâmica.

---

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **CSS3**: Estilização responsiva
- **JavaScript**: Manipulação de dados e interatividade
- **Node.js**: Backend para requisições à POKE-API

---

## Passos para Implementação

### 1. Estrutura do Projeto
|           |           |                    |          |
|-----------|-----------|--------------------|----------|
| **Pasta**       | **Arquivo**       | **Descrição**         |  **Tecnologia** |
| assets/css       |    global.css    | estilização geral da página         |  ![CSS](https://hermes.dio.me/files/assets/94199d6a-adb7-40fc-af67-1e536519da69.svg)   |
| assets/css       |    pokedex.css    | estilização da listagem dos pokemons         | ![CSS](https://hermes.dio.me/files/assets/94199d6a-adb7-40fc-af67-1e536519da69.svg) |
| assets/js       |    main.js    | funções de utilização da da Poke-api e manipulação de objetos html da página          |  ![JS](https://hermes.dio.me/files/assets/e4f4dfaf-3701-4cb5-b33e-bcd5e9936d44.svg) |
| assets/js       |    poke-api.js    | funções de integração com a Poké-API         |  ![JS](https://hermes.dio.me/files/assets/e4f4dfaf-3701-4cb5-b33e-bcd5e9936d44.svg)  |
| assets/js       |    pokemon-models.js    | definição do objeto Pokemon         |    ![JS](https://hermes.dio.me/files/assets/e4f4dfaf-3701-4cb5-b33e-bcd5e9936d44.svg)  |
|        |    index.html    | página html  principal         |  ![CSS](https://hermes.dio.me/files/assets/6bd4e028-7695-487d-ac25-e973be1c9f9d.svg)   |

### 2. Backend Node.js
Busca de dados na Poké-API e manipulação de objetos. Criamos nossa própria classe Pokemon (pokemon-models) e convertemos o resultado da Poke-API para nosso objeto, utilizando somente os dados necessários.
A manipulação dos objetos html está gerando dinamicamente a listagem, de acordo com os dados vinculados a API.

### 3. Página HTML5
Estrutura padrão de html 5, utilizamos a fonte Roboto e configurações para responsividade da página, assim nossa página terá visualização padronizada para diversos tamanhos de telas.
### 4. Estilização CSS3
Estilização da listagem para colorir e exibir com designer interessante os dados de cada Pokemon.
## Testando
1. Instale as dependências: do Node e NPM para criação de servidor virtual para exibição da página.
2. Inicie o servidor:
3. Acesse `http://localhost:3000` no navegador e veja a listagem dos Pokémons de forma.
4. Divirta-se!
---

## Referências
Projeto realizado como exercício da Formação JS da [DIO](https://www.dio.me/curso-javascript).
- [DIO](https://www.dio.me)
- [POKE-API](https://pokeapi.co/)
- [Node.js](https://nodejs.org/)
