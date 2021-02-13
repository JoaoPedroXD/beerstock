## Digital Innovation: Expert class - Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.

Nesta live coding, vamos aprender a testar, unitariamente, uma API REST para o gerenciamento de estoques de cerveja. Vamos desenvolver testes unitários para validar o nosso sistema de gerenciamento de estoques de cerveja, e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito. Além disso, vamos também mostrar como desenvolver funcionalidades da nossa API através da prática do TDD.

Durante a sessão, serão abordados os seguintes tópicos:

-[x] Baixar um projeto através do Git para desenolver nossos testes unitários. 
-[x] Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.
-[x] Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
-[x] Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest. 
-[x] Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas.
-[x] TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suite de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

-[x] Java 14 ou versões superiores.
-[x] Maven 3.6.3 ou versões superiores.
-[x] Intellj IDEA Community Edition ou sua IDE favorita.
-[x] Controle de versão GIT instalado na sua máquina.
-[x] Muita vontade de aprender e compartilhar conhecimento :)

Abaixo, seguem links bem bacanas, sobre tópicos mencionados durante a aula:

-[x] [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
-[x] [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
-[x] [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
-[x] [Site oficial do Spring](https://spring.io/)
-[x] [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
-[x] [Site oficial Mockito](https://site.mockito.org/)
-[x] [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
-[x] [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
-[x] [Referência para o padrão arquitetural REST](https://restfulapi.net/)
-[x] [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

[Neste link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), seguem os slides apresentados como o roteiro utilizado para o desenvolvimento do projeto da nossa sessão.



