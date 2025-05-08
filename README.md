
# Clone da Netflix - Projeto de Aprendizado

Este é um projeto de aprendizado para a construção de um clone da Netflix utilizando React.js. O objetivo do projeto foi replicar a interface e as funcionalidades básicas da plataforma de streaming Netflix, utilizando dados reais de filmes por meio da API do [The Movie Database (TMDb)](https://www.themoviedb.org/).

## Funcionalidades

- **Exibição de lista de filmes**: A página carrega uma lista de filmes, categorizada por gênero, a partir da API TMDb.
- **Destaque de filme**: Um filme em destaque é exibido na parte superior da página, com informações como título, descrição e imagem.
- **Componentização**: O projeto é dividido em componentes React, com cada componente responsável por uma parte específica da UI.

## Tecnologias Utilizadas

- **React.js**: Biblioteca JavaScript para construção da interface de usuário.
- **TMDb API**: API que fornece dados de filmes, como título, sinopse, imagens e mais.
- **CSS**: Estilização da interface com o uso de folhas de estilo.

## Estrutura do Projeto

A estrutura de diretórios do projeto é a seguinte:

```
/src
  ├── /components           # Componentes reutilizáveis da interface
  ├── App.js                # Componente principal da aplicação
  ├── App.css               # Estilos para o componente principal
  ├── index.js              # Ponto de entrada da aplicação React
  ├── Tmdb.js               # Funções para interagir com a API TMDb
/public
  ├── index.html            # Arquivo HTML principal
/package.json               # Gerenciamento de dependências e scripts do projeto
/package-lock.json          # Bloqueio das versões das dependências
/.gitignore                 # Arquivo de configuração do Git
```

## Como Rodar o Projeto Localmente

1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/leonardo-spy/clone-netflix.git
   cd clonenetflix
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Execute o projeto:

   ```bash
   npm start
   ```

4. Acesse a aplicação no seu navegador em [http://localhost:3000](http://localhost:3000).

## Screenshots

![image](https://github.com/user-attachments/assets/6af4e2a1-54b6-46ab-8da8-40f3856362a8)

## Considerações Finais

Este projeto foi desenvolvido como parte de um aprendizado prático de React.js e pode ser expandido com diversas funcionalidades, como autenticação, adição de mais detalhes dos filmes, e personalização de usuário, para se aproximar ainda mais da funcionalidade do serviço Netflix.<br/>Baseado no Projeto do [Bonieky Lacerda](https://www.youtube.com/watch?v=tBweoUiMsDg).

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
