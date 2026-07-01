# Banco

## Postgres

O banco usa Postgres no Supabase.

## Convenções

- IDs em UUID.
- Datas com timezone quando representam evento real.
- `created_at` e `updated_at` em tabelas operacionais.
- Soft delete com `is_active` quando houver histórico.

## Estrutura Inicial

- Cadastro de usuários e perfis.
- Cadastro de barbearias.
- Vínculo de membros.
- Cadastro de barbeiros e serviços.
- Agenda, bloqueios e solicitações.
- Pagamentos e caixa.

