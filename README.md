# Challenge LiterAlura
Catálogo de Livros com interação via linha de comandos 

## Tecnologias
- **Java 17**
- **Maven**
- **Spring Boot**
- **Spring JPA**
- **Biblioteca Jackson**
- **PostgreSQL**
- **Gutendex API**



## Funcionalidades da Aplicação

1.  Buscar livro por título

2. Listar livros registrados

3. Listar autores registrados

4. Listar autores vivos em um determinado ano

5. Listar livros em um determinado idioma

## Utilizando o aplicativo

1. Baixar ou clonar o projeto do GitHub

   ``````
   https://github.com/marcosarielrj/literalura
   ``````

2. Crie um banco de dados Postgress com o nome:

   ``` 
   literalura_db
   ```

3. Configure o seu banco de dados no arquivo ***application.properties***:

   ```
   spring.datasource.url=jdbc:postgresql://localhost:5432/literalura_db
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

4. Execute a aplicação na classe LiteraluraApplication
