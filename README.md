<h1>Workshop Spring Boot JPA</h1>
    <p>Este projeto demonstra a implementação de um sistema utilizando <strong>Spring Boot</strong> e <strong>JPA</strong> (Java Persistence API), incluindo mapeamento de entidades, criação de repositórios e injeção de dependências.</p>
    
  <h2>Estrutura do Projeto</h2>
    <ul>
        <li><strong>src/main/java/com/educandoweb/course</strong>: Código-fonte principal do projeto.</li>
        <li><strong>entities</strong>: Classes de modelo, como <code>Category</code>, <code>Order</code>, <code>Product</code>, <code>User</code>.</li>
        <li><strong>repositories</strong>: Interfaces do Spring Data JPA para acesso aos dados.</li>
        <li><strong>services</strong>: Classes responsáveis pela lógica de negócios.</li>
        <li><strong>resources</strong>: Controladores REST que expõem as APIs.</li>
        <li><strong>config</strong>: Classe de configuração para testes com dados mockados.</li>
    </ul>
    
  <h2>Dependências</h2>
    <p>As principais dependências do projeto estão listadas no <code>pom.xml</code>, incluindo:</p>
    <ul>
        <li>Spring Boot Starter Web</li>
        <li>Spring Boot Starter Data JPA</li>
        <li>H2 Database</li>
        <li>Spring Boot Starter Test</li>
    </ul>
    
   <h2>Como Executar</h2>
    <ol>
        <li>Clone o repositório: <code>git clone https://github.com/ms-gustavo/workshop-springboot-jpa.git</code></li>
        <li>Entre no diretório do projeto.</li>
        <li>Execute o projeto com: <code>./mvnw spring-boot:run</code> (Linux/Mac) ou <code>mvnw.cmd spring-boot:run</code> (Windows).</li>
        <li>A API estará disponível em <a href="http://localhost:8080">http://localhost:8080</a>.</li>
    </ol>
    
  <h2>Endpoints</h2>
    <p>Exemplo de alguns endpoints disponíveis:</p>
    <ul>
        <li><code>GET /users</code>: Retorna todos os usuários.</li>
        <li><code>GET /products</code>: Retorna todos os produtos.</li>
        <li><code>GET /orders</code>: Retorna todos os pedidos.</li>
    </ul>
    
   <h2>Banco de Dados</h2>
    <p>O projeto utiliza o banco de dados <strong>H2</strong> para testes. A interface de gerenciamento pode ser acessada em:</p>
    <p><a href="http://localhost:8080/h2-console">http://localhost:8080/h2-console</a></p>
    <p>As credenciais padrão podem ser encontradas no <code>application.properties</code>.</p>
    
   <h2>Licença</h2>
    <p>Este projeto é de código aberto e pode ser utilizado livremente.</p>
