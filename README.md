![Polígono na cro azul acinzentado seguido de Food Eplorer escrito em branco e fundo preto](https://user-images.githubusercontent.com/81266915/216989553-ae44830c-e80c-4f2e-a841-8dea22f89f66.jpg)

<h1 align="center"> Food Explorer Backend - Karina Lumy </h1>

# Índice 

* [Título e Imagem de capa](#Título-e-Imagem-de-capa)
* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Instruções para a execução do projeto](#instruções-para-a-execução-do-projeto)

# Descrição do Projeto
  O Food Explorer é o projeto final do curso Explorer da Rocketseat.</br>
  Neste projeto foi criado um menu digital para compras online de um restaurante.</br>
  É possível acessá-lo como administrador ou como cliente como explicarei melhor abaixo.</br>
  Bom, no Food Explorer o administrador pode acrescentar, retirar, ou editar os pratos conforme a necessidade. É possível, alterar imagens, ingredientes, nome e valores.</br>
  Já o cliente depois de se cadastrar e fazer o login pode selecionar o prato, saber detalhes como ingredientes, favoritar pedidos, ir para página de pagamento, escolher a forma de pagamento (pix ou cartão) e finalizar o pedido.
  
# Status do projeto

# Acesso ao Projeto
* Para ver o projeto [clique aqui](https://foodexplorer-karinalumy.netlify.app/).</br>
* Para acessar como administrador:</br>
  email: admin@email.com</br>
  senha: 123456</br>
* Para acessar como cliente basta realizar um cadastro e logar.

# Funcionalidades e Demonstração da Aplicação
<h2 align="center">Acessando como cliente</h2>
Ao acessar o site o usuário cairá nessa página inicial contendo inputs para fazer o login:

![Página inicial de login](https://user-images.githubusercontent.com/81266915/217594319-9760d626-7616-4d13-acff-430d3a55c754.jpg)

Caso o usuário ainda não possua cadastro, basta clicar em "Criar uma conta" e ele será direcionado para essa página:
![Página para cadastro de usuário](https://user-images.githubusercontent.com/81266915/217594770-832c89ac-163d-4063-a6ae-a580c5a9fab7.jpg)

Depois de logado o cliente pode será direcionado para a página de Pratos Principais, Sobremesas e Bebidas:

![sabores-user](https://user-images.githubusercontent.com/81266915/217599715-563359d9-8692-47b5-9603-56581b76c7cc.png)
![pratos-principais](https://user-images.githubusercontent.com/81266915/217596267-07e81543-3e31-4491-aa86-34bd461bb727.jpg)
![sobremesas-users](https://user-images.githubusercontent.com/81266915/217599661-7a225a88-13e6-4a27-86eb-53025d1f78f3.png)
![bebidas-user](https://user-images.githubusercontent.com/81266915/217599975-23b5035b-2b8d-4d86-89f2-9ccff3f7cde2.png)

Nessa área o cliente pode favoritar pedidos, fazer busca de pratos, incluir pratos no carrinho de compras e ver os seus pedidos no botão no topo da página "Pedidos".

Também é possível ver quais ingredientes de cada prato clicando em cima do nome do prato:
![ingredientes](https://user-images.githubusercontent.com/81266915/217597489-ca86fddc-a355-4674-a960-e2faca01d27e.png)

Para finalizar, após escolher os pratos o cliente será direcionado para página de descrição dos pedidos, onde ele pode exclui algum caso queira e escolher a forma de pagamento, cartão de crédito ou QR Code PIX:


![pagamento](https://user-images.githubusercontent.com/81266915/217598143-a6319a0d-3b0d-4c2e-9964-fdb369c1bcc3.png)

<h2 align="center">Acessando como Administrador</h2>
Fazendo login como administrador é possível editar os pratos.</br>

![pratos-principais](https://user-images.githubusercontent.com/81266915/217600928-1d08a5c3-7b4c-4840-87ee-f00a2824ef17.png)

É possível retirar pratos clicando na lixeira ou apenas adicionar mais items ao cardápio clicando em adicionar novo prato.
O administrados também pode alterar nomes, descrição ou ingredientes clicando sobre o prato para ser redirecionado para a página de edição.

![mudar-pratos](https://user-images.githubusercontent.com/81266915/217601979-12c7816b-6ce4-4af2-8439-f3f51bf2fab4.png)

# Tecnologias utilizadas
O Frontend dessa aplicação foi hospedade no Netlify e o Backend no Render.</br>
E para essa aplicação foi utilizada:
* HTML
* JavaScript
* ReactJs
* Node.js
* Styled Components
* React Icons
* React Router Dom
* Vite
* SQLite
* Knex
* Axios

# Instruções para a execução do projeto
Clonar os dois repositórios, tanto este (Backend) quanto o frontedn que pode ser encontrado [aqui](https://github.com/karinalumy/food-explorer-frontend)
Entre na pasta do Backend e rode os seguintes comandos no terminal:

```
  # Para instalar as dependencias
  npm install
  
  # Para rodar a api
  npm run dev
```

Para o Frontend entre na pasta e de os seguintes comandos:

```
  # Para instalar as dependencias
  npm install
  
  # Para rodar a api
  npm run dev
  
  # A seguir no terminal você poderá ver o local onde a aplicação está sendo rodada. Copie e cole o endereço no seu navegador.
    ex: http://localhost:5173/ 
  
  # Login de administrador:
    email: admin@email.com
    senha: 123456
    
  # Login de usuário:
    email: karina@email.com
    login: 123456
```

