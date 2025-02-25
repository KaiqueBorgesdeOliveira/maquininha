# Maquininha de Cartão - PagueSe

🚧 **Projeto em Construção** 🚧

Bem-vindo ao repositório da **Maquininha de Cartão - PagueSe**! Este projeto está em desenvolvimento e tem como objetivo criar um sistema de processamento de pagamentos.

## 📌 **Tecnologias Utilizadas**
- **Java 17**
- **Spring Boot**
- **Spring Security**
- **PostgreSQL**
- **Maven**
- **Postman** (para testes de API)

## 🚀 **Configuração do Ambiente**
Para rodar o projeto localmente, siga os passos:

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/pague-se-maquininha.git
   ```
2. Configure o banco de dados PostgreSQL e altere o `application.properties`, se necessário:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/postgres
   spring.datasource.username=postgres
   spring.datasource.password=admin
   spring.datasource.driver-class-name=org.postgresql.Driver
   ```
3. Execute o projeto usando o Maven:
   ```sh
   mvn spring-boot:run
   ```
4. Teste os endpoints via **Postman** ou outro cliente REST.

## 📡 **Endpoints Disponíveis**
- `GET /usuarios` - Lista todos os usuários.
- `GET /usuarios/{id}` - Busca um usuário pelo ID.
- `POST /usuarios` - Cria um novo usuário.
- `DELETE /usuarios/{id}` - Deleta um usuário pelo ID.

## 🔒 **Segurança e Autenticação**
Atualmente, a autenticação está configurada com **Spring Security**. O acesso pode exigir usuário e senha:
```
Usuário: admin
Senha: admin
```

## 🛠 **Próximos Passos**
- [ ] Melhorar a estrutura do banco de dados.
- [ ] Implementar autenticação JWT.
- [ ] Criar interface web para o sistema.

---
📌 **Atenção:** Este projeto está em desenvolvimento e pode sofrer alterações frequentes!

💡 Dúvidas ou sugestões? Fique à vontade para contribuir! 😃

