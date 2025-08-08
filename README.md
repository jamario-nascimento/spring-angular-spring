## 🚀 **Crud Spring + Angular**

### **🎯 Objetivo do Projeto**

Este projeto é um laboratório de conhecimento, focado em aprimorar as habilidades em Java com Spring Boot. O objetivo é construir uma API RESTful de alta qualidade, aplicando as melhores práticas do mercado para criar um sistema robusto, seguro e escalável, pronto para integração com um frontend moderno.

### **✨ Funcionalidades e Características**

A API é o coração deste projeto e foi concebida com um design limpo e modular. Atualmente, ela fornece uma estrutura sólida para endpoints RESTful, mas já está preparada para o futuro, com planos para as seguintes funcionalidades:

* **Endpoints RESTful:** Uma API completa para operações CRUD (Create, Read, Update, Delete).
* **Segurança Robusta:** Implementação de autenticação e autorização via **Keycloak** para proteger os endpoints da API.
* **Documentação Profissional:** Utilização do **Swagger** para gerar uma documentação interativa e completa da API, facilitando a integração com qualquer frontend.
* **Padrões de Projeto:** Aplicação do padrão de design **Repository** para abstrair a camada de acesso a dados, garantindo um código mais limpo e fácil de manter.
* **Contêinerização com Docker:** Projeto configurado para ser executado em contêineres Docker, o que garante um ambiente de desenvolvimento e produção consistente e portátil.

### **🛠️ Tecnologias e Ferramentas**

O projeto foi construído sobre uma pilha de tecnologias modernas, refletindo as exigências do mercado:

**Backend:**
* **Java 21:** A versão mais recente do Java, utilizada para aproveitar as últimas novidades da linguagem.
* **Spring Boot 3.5.4:** O framework que simplifica o desenvolvimento de aplicações Java, focado em alta produtividade.
* **Spring Data JPA:** Facilita a comunicação com o banco de dados através do padrão JPA.
* **Lombok:** Reduz a verbosidade do código Java, gerando automaticamente getters, setters, e construtores.
* **Maven:** Gerenciamento de dependências e construção do projeto.

**Banco de Dados:**
* **H2 Database (em memória):** Utilizado para o desenvolvimento e testes, garantindo um ambiente rápido e leve.
* **Docker:** Para um ambiente consistente e produção.

**Ferramentas e Boas Práticas:**
* **Testes Unitários:** Para garantir a confiabilidade e a estabilidade do código.
* **Docker:** Para contêinerização e portabilidade.
* **Keycloak:** Para autenticação e autorização.
* **Swagger:** Para documentação da API.

### **⚙️ Como Executar o Projeto**

Para rodar o projeto localmente, siga os passos abaixo:

1.  **Pré-requisitos:** Certifique-se de ter o **JDK 21** e o **Maven** instalados.
2.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```
3.  **Execute a aplicação:**
    ```bash
    ./mvnw spring-boot:run
    ```

A aplicação estará rodando em `http://localhost:8080`.

### **👨‍💻 Próximos Passos**

Este projeto está em constante evolução. Os próximos passos incluem:

* Integrar o frontend desenvolvido em Angular.
* Implementar a autenticação e autorização via Keycloak.
* Configurar a documentação da API com Swagger.
* Adicionar mais testes para alcançar uma cobertura de código de alta qualidade.
* Configurar o projeto para usar Docker Compose para rodar a aplicação e o banco de dados de forma integrada.