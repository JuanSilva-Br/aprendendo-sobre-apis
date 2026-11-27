# Aprendendo sobre APIs

Repositório do meu estudo individual de desenvolvimento de APIs com Node.js.
Em 4 semanas (2h por dia), o objetivo é sair do JavaScript básico e construir,
do zero, APIs em diferentes paradigmas, aplicando boas práticas de produção.

## O que estou construindo

| Módulo | Projeto | Foco |
|---|---|---|
| Fundamentos | Servidor HTTP nativo | Verbos, status codes, headers, serialização |
| REST | API de Biblioteca | CRUD, paginação, filtros, erros (RFC 7807/9457), OpenAPI/Swagger, JWT |
| JSON:API | Blog | Relacionamentos, `include`, sparse fieldsets, `errors[]` |
| SOAP | Cliente e servidor | XML, WSDL, adapter SOAP → REST |
| gRPC | Catálogo | Protocol Buffers, streaming, benchmark contra REST |
| Final | Gateway REST + microsserviço gRPC | Integração entre protocolos |

## Boas práticas incluídas

Testes unitários e de integração, validação de entrada, rate limiting, CORS,
`helmet`, logs estruturados e documentação das rotas.

## Stack

Node.js (LTS) · Express · Zod · Mongoose ou SQLite · Vitest + Supertest ·
`soap` · `@grpc/grpc-js`

## Estrutura do repositório

(Uma pasta por projeto, cada uma com seu próprio README explicando como rodar.)

## Status

🚧 Em andamento. Cada projeto será marcado como concluído ao ser publicado.

- [x] Dia 1: servidor HTTP com o módulo nativo
- [ ] REST
- [ ] JSON:API
- [ ] SOAP
- [ ] gRPC
- [ ] Projeto final
