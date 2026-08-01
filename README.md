# PC Xpress Mercado Livre Analytics

Versao minima para deploy manual na Vercel.

## Arquivos

- `index.html`: dashboard estatico.
- `api/dashboard.js`: funcao serverless que consulta o Supabase usando env vars da Vercel.
- `assets/pcxpress-logo.webp`: logo da PC Xpress.
- `package.json` e `vercel.json`: configuracao minima da Vercel.

## Variaveis na Vercel

```env
SUPABASE_URL=https://SEU-PROJETO.supabase.co
SUPABASE_SERVICE_ROLE_KEY=SUA_SERVICE_ROLE_KEY
SUPABASE_SCHEMA=ml_dashboards
SUPABASE_ACCOUNT_NAME=PC Express
```

Nunca use `NEXT_PUBLIC_` na `SUPABASE_SERVICE_ROLE_KEY`.
