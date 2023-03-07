<h1 align="center">Inventory Microservice</h1>
Este microservice é responsável pelo gerenciamento do estoque de produtos do Shopping Online. Ele permite a verificação do estoque de produtos, retornando verdadeiro quando um produto tem no estoque.

O microservice foi implementado seguindo o padrão RESTful e utiliza o protocolo HTTP para comunicação. Ele pode ser acessado por endpoints que respondem aos verbos HTTP GET, para realizar a operação de busca no estoque.

Para usar o microservice, basta enviar requisições HTTP para os endpoints correspondentes, passando os parâmetros necessários, conforme descrito na documentação da API. Com isso, é possível consultar e atualizar informações de produtos de forma simples e eficiente.

## Endpoints Disponíveis

`GET /inventory`: retorna se há o produto

## Tecnologias Utilizadas
O microservice de produtos foi implementado utilizando as seguintes tecnologias:

<ul>
<li>Java</li>
<li>MySQL</li>
<li>Spring Framework</li>
<li>Spring Boot</li>
<li>RESTful API</li>
<li>Protocolo HTTP</li>
</ul>

## Como Executar
Para executar o microservice de inventário, é necessário ter o Java 17 e gerenciador de pacotes Maven instalados na máquina. Em seguida, basta clonar o repositório, abrir o projeto em uma IDE de sua escolha e executar os seguintes comandos para iniciar o serviço:

```bash
mvn package
```
```bash
mvn spring-boot:run
```

## Documentação da API
Para mais informações sobre como usar o microservice e seus endpoints disponíveis, consulte a documentação da API, que pode ser acessada em [openapi.yaml](openapi.yaml) após a inicialização do serviço.