# 🛍️ Produtos API

API REST simples para gerenciar produtos usando Java + Spring Boot 🚀

---

## 🎯 Funcionalidades

- ➕ Criar produto  
- 🔍 Buscar produto por ID  
- ✏️ Atualizar produto  
- 🗑️ Deletar produto  
- 🔎 Buscar produtos por nome

---

## 🛠️ Tecnologias

- ☕ Java 17+  
- 🌱 Spring Boot  
- 📦 Spring Data JPA

---

## 📚 Endpoints

| Método | Endpoint           | Descrição                  |
|--------|--------------------|----------------------------|
| POST   | `/produtos`        | Criar um novo produto      |
| GET    | `/produtos/{id}`   | Obter produto por ID       |
| PUT    | `/produtos/{id}`   | Atualizar produto por ID   |
| DELETE | `/produtos/{id}`   | Deletar produto por ID     |
| GET    | `/produtos?nome=`  | Buscar produtos pelo nome  |

---

## 📦 Modelo Produto

```json
{
  "id": "string",
  "nome": "string",
  "descricao": "string",
  "preco": 0.0
}
```

---

## 🚀 Como rodar

1. Clone o repositório  
2. Importe no IDE (IntelliJ, Eclipse)  
3. Execute a classe principal com `@SpringBootApplication`  
4. Teste os endpoints com Postman, Insomnia ou outro cliente REST  

---

## 👨‍💻 Autor

Vinicius Carmo  
[LinkedIn](https://www.linkedin.com/in/seu-usuario)
