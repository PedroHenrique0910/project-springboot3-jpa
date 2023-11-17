# Projeto Spring Boot - Sistema de Pedidos com Banco de Dados Local H2


# Sobre o projeto
Este projeto Spring Boot, desenvolvido em Java, propõe um sistema completo para a administração de pedidos. A estrutura do banco de dados utiliza um banco de dados local H2. O sistema engloba diversas funcionalidades essenciais para operações eficientes, desde o cadastro de categorias e produtos até o processamento de pedidos, incluindo a gestão de pagamentos.
Abaixo, segue a descrição da estrutura do banco de dados:

tb_category: Armazena as categorias dos produtos.

![1](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/ec9e70bb-3e2c-4088-b66e-f9647f723ceb)


tb_order: Contém informações sobre os pedidos, como o momento da realização (no formato ISO), o status do pedido e o cliente associado.

![2](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/2c44e28d-dd0f-4c03-924c-fb420d1690df)


tb_order_item: Mapeia os itens dos pedidos, abrangendo detalhes como preço, quantidade, e as relações com produtos e pedidos.

![3](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/82cab9a5-d02f-4093-bd01-0b90e4d3435f)


tb_payment: Registra dados relativos ao pagamento, incluindo o momento (no formato ISO) e a associação com um pedido específico.

![4](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/7e2d47b9-9d99-4403-8529-2447eb13cf35)


tb_product: Mantém informações dos produtos, como descrição, URL da imagem, nome e preço.

![5](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/3d74fced-1b23-43cf-8f39-a51a19545de1)


tb_product_category: Serve como tabela de junção, associando produtos às suas categorias correspondentes.

![6](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/f4255eca-86ea-4b7c-80a6-60c1d14c6708)


tb_user: Armazena detalhes dos usuários, incluindo nome, e-mail, telefone e senha.

![7](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/5b39a907-1a02-4b14-989e-9cde20f60f45)


## Layout web

![Layout](https://github.com/PedroHenrique0910/project-springboot3-jpa/assets/132857723/2d8ab507-08d3-47e6-9d40-31c944090767)


# Tecnologias e Ferramentas utilizadas
- Java
- Spring Boot
- JPA / Hibernate
- H2 Database
- Postman


# Como executar o projeto

Requisitos Prévios:
Certifique-se de ter as seguintes ferramentas instaladas em sua máquina: 
- Java (JDK 17 ou superior).
- Maven

Para executar este projeto localmente, siga os passos abaixo:

```bash
# clonar repositório
git clone https://github.com/PedroHenrique0910/project-springboot3-jpa.git

# Navegue até o diretório do projeto usando o comando `cd`. 

# executar o projeto
./mvnw spring-boot:run

# Após a conclusão do passo anterior, a aplicação estará disponível em: http://localhost:8080/h2-console

# Clique em "Connect" e acessará o banco de dados local.
```


# Autor

Pedro Henrique.

https://www.linkedin.com/in/pedrohf0910/
