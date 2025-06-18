# n8n-evolution-redis-postgres

Este projeto utiliza Docker Compose para orquestrar uma instância do [n8n Evolution](https://n8n.io/), com suporte a persistência via PostgreSQL e cache com Redis.

## 📁 Estrutura

Certifique-se de que os seguintes arquivos estejam na **mesma pasta**:

- `docker-compose.yml`
- `.env`

## ⚙️ Pré-requisitos

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## 🚀 Subindo os serviços

1. Clone este repositório ou copie os arquivos para o diretório desejado.
2. Crie (ou edite) o arquivo `.env` com as variáveis de ambiente necessárias.
3. Execute o comando:

```bash
docker-compose up -d
