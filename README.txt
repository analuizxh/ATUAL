Projeto Integrador MedObras - Corrigido

Para rodar o projeto:
1. Instale dependências:
   cd backend
   npm install

2. Configure o banco no arquivo .env: DATABASE_URL="mysql://medobras_ana:sua_senha_aqui@127.0.0.1:3306/medobras_bd"

JWT_SECRET=isso_eh_uma_chave_secreta_pode_ser_qualquer_coisa_123

3. Rode as migrations e gere o client Prisma:
   npx prisma generate
   npx prisma migrate dev --name init

4. Inicie o servidor:
   npm run dev

O frontend está na pasta frontend (abra login.html com Live Server).
