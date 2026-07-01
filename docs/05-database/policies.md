# Policies

## RLS

Todas as tabelas de negócio devem usar Row Level Security.

## Regras Base

- Cliente acessa apenas seus próprios dados.
- Membro da barbearia acessa dados da unidade.
- Dono e gerente gerenciam equipe, serviços e financeiro.
- Admin da plataforma pode auditar e operar suporte.

## Funções

- `is_platform_admin`.
- `is_shop_member`.
- `is_shop_owner_or_manager`.

