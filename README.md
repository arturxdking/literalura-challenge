# Praticando Spring Boot: Challenge LiterAlura
**Objetivo:** Desenvolver um Catálogo de Livros que ofereça interação textual (via console) com os usuários, proporcionando no mínimo 5 opções de interação. Os livros serão buscados através de uma API específica.

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

## Como rodar o projeto

1. Clone este repositório

   ``````
   https://github.com/arturxdking/literalura-challenge.git
   ``````

2. Entre no diretório principal

   ``` 
   cd literalura
   ```

3. Configure o seu banco de dados no arquivo ***application.properties***:

   ```
   spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

4. Execute a aplicação na classe principal ***LiteraluraApplication***
