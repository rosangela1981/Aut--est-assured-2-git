Automação de Testes de API com RestAssured 🚀
Este projeto tem como objetivo demonstrar a implementação de testes automatizados de API utilizando Java e a biblioteca RestAssured. O foco é validar o comportamento do endpoint de reservas da API Restful-Booker.

🛠️ Tecnologias Utilizadas
Java: Linguagem de programação base.

RestAssured: Biblioteca para automação de testes de API REST com foco em simplicidade e legibilidade (estilo BDD).

JUnit 5: Framework de testes para execução e validação das asserções.

Maven (ou Gradle): Gerenciador de dependências.

📋 Cenário de Teste Implementado
O teste atual realiza a seguinte validação:

Endpoint: GET /booking/

Objetivo: Validar se a listagem de reservas está disponível.

Critérios de Aceite:
O status code de retorno deve ser 200 (OK).
O cabeçalho Accept deve ser configurado como */*.
Os detalhes da resposta devem ser exibidos no log para auditoria técnica.

💻 Estrutura do Código
A automação utiliza a sintaxe fluida do RestAssured (Given/When/Then):

Java
given() // Pré-condições (Headers, Params, Body)
.when()  // Ação (Verbo HTTP e Endpoint)
.then()  // Validações (Status Code, Body, Tempo de Resposta)
🚀 Como Executar
Certifique-se de ter o JDK 11+ e o Maven instalados.
Clone este repositório link do projeto: https://github.com/rosangela1981/Aut--est-assured-2-git.git 

No terminal, execute o comando:

Bash
mvn test
