# Multitenancy

## Modelo

Cada barbearia é um tenant representado por `barber_shops`.

## Regras

- Toda entidade operacional deve ter `barber_shop_id`.
- Usuários acessam unidades via `shop_members`.
- Donos e gerentes têm permissões administrativas.
- Barbeiros acessam agenda e dados relacionados à operação.

## Multiunidade

Redes podem ter múltiplas barbearias associadas ao mesmo dono ou grupo.

