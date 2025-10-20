# Documentação da API

## Endpoints Disponíveis

- `GET /buscar?q={consulta}` - Buscar respostas
- `POST /perguntas` - Submeter nova pergunta  
- `GET /perguntas/{id}` - Obter pergunta específica
- `POST /respostas/{id}` - Submeter resposta
- `GET /usuarios/{id}` - Obter perfil do usuário

## Limites de Taxa

- 300 requisições por hora para usuários anônimos
- 10.000 requisições por hora para usuários autenticados

## Formato de Resposta

Todas as respostas seguem formato JSON padrão com tratamento adequado de erros.