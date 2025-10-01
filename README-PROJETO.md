# Backend - Supermercado Online (Strapi)

Este é o backend do sistema de e-commerce do supermercado, desenvolvido com Strapi CMS.

## Configuração

### 1. Instalação das dependências
```bash
cd backend
npm install
```

### 2. Configuração do banco de dados
O projeto está configurado para usar SQLite em desenvolvimento. Para produção, recomenda-se PostgreSQL.

### 3. Executar em desenvolvimento
```bash
npm run develop
```

O painel administrativo estará disponível em: http://localhost:1337/admin

### 4. Primeiro acesso
1. Acesse http://localhost:1337/admin
2. Crie sua conta de administrador
3. Configure as collections de Categoria e Produto
4. Adicione algumas categorias e produtos de exemplo

### 5. Collections criadas
- **Categorias**: Para organizar os produtos
- **Produtos**: Com todos os campos necessários (nome, preço, estoque, etc.)

### 6. Deploy em produção
Para deploy em serviços como Heroku, Railway ou Render:

```bash
npm run build
npm start
```

### Variáveis de ambiente
Crie um arquivo `.env` com:
```
HOST=0.0.0.0
PORT=1337
APP_KEYS=your-app-keys
API_TOKEN_SALT=your-api-token-salt
ADMIN_JWT_SECRET=your-admin-jwt-secret
TRANSFER_TOKEN_SALT=your-transfer-token-salt
JWT_SECRET=your-jwt-secret
```
