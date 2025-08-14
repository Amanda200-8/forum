Resumo do Projeto
Para essa atividade, criei um sistema de gerenciamento de vagas de emprego usando o framework Spring Boot, que segue o padrão de arquitetura MVC (Model-View-Controller).

O objetivo principal foi conectar a aplicação a um banco de dados MySQL chamado databasepi e criar um CRUD completo (Cadastrar, Listar, Atualizar e Excluir) para uma entidade Produto.

Como o projeto funciona:

Modelo (Model): A entidade Produto representa os dados que são salvos no banco de dados, como ID, nome, descrição e preço.

Controle (Controller): O ProdutoController é responsável por receber as requisições do usuário. Ele processa a lógica da aplicação, como salvar, buscar ou excluir produtos.

Visualização (View): As páginas HTML (produtos.html e form.html) foram criadas usando a biblioteca Thymeleaf. Elas são o frontend da aplicação, onde o usuário interage, visualiza a lista de produtos, e preenche os formulários.

Conexão com o Banco de Dados: A persistência dos dados foi feita usando o Spring Data JPA, que simplifica muito a comunicação com o MySQL, eliminando a necessidade de escrever queries manualmente.

Estilização: O design da interface foi feito com CSS puro, garantindo que as páginas sejam fáceis de usar e visualmente agradáveis.

No final, subi todo o projeto para um repositório no GitHub para que a atividade pudesse ser avaliada.

