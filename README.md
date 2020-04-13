<h3 align="center">
  Desafio: Conceitos do ReactJS
</h3>

## Sobre o desafio
Nesse desafio, foi criado uma aplicação React que permite listar, incluir e deletar dados dos repositórios criados na API feita no desafio anterior utilizando Node.js, segue link para o desafio anterior: *https://github.com/MFBarth/Desafio_Conceitos_NodeJs*.
 
**Observação**: Este desafio está utilizando o gerenciador de pacotes **yarn**, sendo assim para instalar todas as dependências é necessário dar o comando `yarn` no terminal, além disso é nescessário que a API (criado no desafio anterior) esteja sendo executado no caminho *http://localhost:3333*, para que a aplicação consiga listar, incluir e deleletar dados dos respositórios.

### Funcionalidades da Aplicação

Abaixo as funcionalidades que foram criadas para atender o desafio.

- **`Listar os repositórios da sua API`**: É possível listar o campo **title** de todos os repositórios que estão cadastrados na API.

- **`Adicionar um repositório a sua API`**: É possível adicionar um novo item na API através de um botão com o texto **Adicionar** e, após a criação, é possíve exibir o nome dele no frontend.

- **`Remover um repositório da sua API`**: Para cada item da lista, possui um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do frontend e da API.