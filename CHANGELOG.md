# Changelog

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

# Changelog

## [1.0.0] - 2026-02-28
### Adicionado
- Configuração de ambiente seguro com `.env` (python-dotenv).
- Integração com banco de dados **PostgreSQL**.
- Configuração de atomicidade de requisições (`ATOMIC_REQUESTS: True`).
- Estrutura inicial do app `core`.

### Segurança
- Remoção de credenciais expostas do histórico do Git através de reset de repositório.
- Configuração de `.gitignore` para proteção de arquivos sensíveis.

### Adicionado
- README inicial e planejamento do projeto.