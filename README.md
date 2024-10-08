<a href="https://youtu.be/RCRCn4ZXY44">
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube" width="30" /> Assista no YouTube!
</a>






# AgroCareTech

**AgroCareTech** é um projeto desenvolvido em Java, utilizando Spring Boot, para a gestão de atividades agropecuárias, com integração ao banco de dados Oracle. Este sistema oferece funcionalidades de gerenciamento de animais, tratamentos e consultas.

## Tecnologias Utilizadas

- **Java 17**: Linguagem de programação utilizada para o desenvolvimento do sistema.
- **Spring Boot**: Framework para facilitar a criação de aplicações Java.
  - **Spring Data JPA**: Para integração e persistência com o banco de dados.
  - **Spring Security** (opcional): Para implementação de segurança e autenticação.
- **Banco de Dados Oracle**: Utilizado para armazenar os dados relacionados ao projeto.
- **Maven**: Gerenciador de dependências e automação de build.
- **Hibernate**: Framework ORM utilizado para mapeamento dos objetos Java no banco de dados.

## Requisitos

- **Java 17** ou superior
- **Maven 3.6+**
- **Oracle Database** (pode ser uma instância local ou em nuvem)
- **Git** (opcional, para versionamento)


## Como Executar o Projeto

### Passo 1: Clonar o Repositório

```bash
git clone https://github.com/codelize/devops_SPRINT.git
```

### Passo 2: Abrir essa pasta em uma IDE de sua preferência e que suporte JAVA

### Passo 3: Navegar para \src\main\java\br\com\fiap\plusoft\AgroCareTech\AgroCareTechApplication.java

### Passo 4: Executar o arquivo .java

### Passo 5: Se tudo der certo, a aplicação estará rodando em **`localhost:8080`**

### Endpoints para se testar:

A seguir, alguns dos principais endpoints da aplicação:

- **GET** `/users` - Retorna a lista de usuários cadastrados.
- **POST** `/users` - Cadastra um novo usuário.
- **POST** `/login` - Endpoint responsável por fazer o login do usuário.
- **POST** `/veterinario` - Cadastra um novo veterinário.

