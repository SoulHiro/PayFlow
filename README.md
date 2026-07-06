# PayFlow

Mini sistema de gestão de contas a pagar. Projeto pessoal com foco em demonstrar boas práticas de arquitetura frontend/backend com Next.js e TypeScript.

## Status

🚧 Em desenvolvimento — fase inicial de setup do ambiente e schema do banco de dados.

## Stack

Next.js, TypeScript, React, Tailwind CSS, Drizzle ORM, SQLite, Vitest, Sentry, Vercel

## Como rodar localmente

```bash
git clone https://github.com/SoulHiro/payflow.git
cd payflow
npm install
cp .env.example .env.local
npm run db:push
npm run db:seed
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000).

## Scripts

| Comando | Descrição |
|---|---|
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Build de produção |
| `npm run lint` | Roda o ESLint |
| `npm run test` | Roda os testes (Vitest) |
| `npm run db:generate` | Gera migrations do Drizzle |
| `npm run db:push` | Aplica o schema no banco local |
| `npm run db:seed` | Popula o banco com dados fake |

## Roadmap

- [ ] Schema do banco + seed de dados
- [ ] Tela de listagem com filtro e paginação
- [ ] Formulário de cadastro de nota com optimistic UI
- [ ] Endpoint de webhook simulando integração com ERP externo
- [ ] Testes unitários das regras de negócio
- [ ] Observabilidade com Sentry

## Licença

Projeto pessoal, sem fins comerciais.