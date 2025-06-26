🛍️ Produtos API
API REST simples para gerenciar produtos usando Java + Spring Boot 🚀

🎯 Funcionalidades
➕ Criar produto

🔍 Buscar produto por ID

✏️ Atualizar produto

🗑️ Deletar produto

🔎 Buscar produtos por nome

🛠️ Tecnologias
☕ Java 17+

🌱 Spring Boot

📦 Spring Data JPA

📚 Endpoints
Método	Endpoint	Descrição
POST	/produtos	Criar um novo produto
GET	/produtos/{id}	Obter produto por ID
PUT	/produtos/{id}	Atualizar produto por ID
DELETE	/produtos/{id}	Deletar produto por ID
GET	/produtos?nome=	Buscar produtos pelo nome

📦 Modelo Produto
json
Copiar
Editar
{
  "id": "string",
  "nome": "string",
  "descricao": "string",
  "preco": 0.0
}
🚀 Como rodar
Clone o repositório

Importe no IDE (IntelliJ, Eclipse)

Execute a classe principal com @SpringBootApplication

Teste os endpoints com Postman, Insomnia ou outro cliente REST

👨‍💻 Autor
Vinicius Carmo
LinkedIn
