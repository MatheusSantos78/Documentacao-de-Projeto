Sistema de Moeda Estudantil

🌟 Visão Geral

O Sistema de Moeda Estudantil é uma plataforma desenvolvida para incentivar e reconhecer o mérito dos alunos. Professores distribuem uma moeda virtual que pode ser trocada por vantagens oferecidas por empresas parceiras.

✨ Funcionalidades

•
Envio de Moedas: Professores enviam moedas para alunos.

•
Resgate de Vantagens: Alunos trocam moedas por cupons de vantagens.

•
Validação de Cupom: Parceiros validam os cupons de resgate.

•
Consulta de Saldo/Extrato: Visualização do histórico de transações.

💻 Tecnologias

Componente
Tecnologia
Frontend
React, TypeScript, Vite
Backend
Node.js, TypeScript
Banco de Dados
PostgreSQL
ORM
Prisma


🚀 Como Rodar Localmente

Pré-requisitos

•
Node.js

•
pnpm (ou npm/yarn)

•
PostgreSQL (pode ser via Docker)

Configuração

1.
Clonar o Repositório: ```bash git clone https://github.com/viniciusmazzoli/Sistema-de-Moeda-Estudantil.git cd Sistema-de-Moeda-Estudantil ```

2.
Configurar o Banco de Dados:

•
Crie um banco de dados PostgreSQL.

•
Crie um arquivo .env no diretório backend-sistema-moeda com a variável DATABASE_URL.



3.
Instalar Dependências e Migrar o Banco de Dados: ```bash cd backend-sistema-moeda pnpm install pnpm prisma migrate dev --name init pnpm prisma generate ```

4.
Iniciar o Backend: ```bash pnpm dev ```

5.
Iniciar o Frontend: ```bash cd .. pnpm install pnpm dev ```

📝 Licença

Este projeto está sob a licença MIT.

📞 Contato

•
Desenvolvedores: [Seu Nome], [Nome do Colega 1], [Nome do Colega 2]

•
Repositório Original: https://github.com/viniciusmazzoli/Sistema-de-Moeda-Estudantil

