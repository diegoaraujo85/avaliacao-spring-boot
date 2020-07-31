# Avaliação Java SVA

## Tecnologias presentes na prova:  

* Spring Boot  
* ThymeLeaf  
* Spring Data  
* BootStrap  

## Por onde começar

* Clone o projeto em seu computador
* Importe o projeto teste-sva no eclipse usando o maven
* Crie uma base de dados MYSQL com o nome demo
* Certifique-se de ter o plugin Spring Boot em seu eclipse
* Abra o arquivo Application.java, localizado em *src/main/java/br/com/tokiomarine/seguradora/avaliacao*
* Run -> Run as -> Spring Boot App
* Tanto a página web quanto o REST estão funcionando

## Exemplos

 ### REST
 * GET http://localhost:8081/estudantes/
 * GET http://localhost:8081/estudantes/1
 * POST http://localhost:8081/estudantes/
 * PUT http://localhost:8081/estudantes/
 * DELETE http://localhost:8081/estudantes/1

### WEB
  * Acesse http://localhost:8081/
  * Clique em Adicionar Estudante, adicione quantos quiser
  * Teste os botões de editar e deletar