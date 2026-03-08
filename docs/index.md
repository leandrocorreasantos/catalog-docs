# Catalog SaaS Documentation

Bem-vindo à documentação oficial do **Catalog SaaS**, uma plataforma multi-tenant para criação e gerenciamento de catálogos de produtos.

## Visão Geral

O Catalog SaaS permite que pequenas lojas criem seus catálogos online com:
- **Catálogo público** para clientes (desenvolvido com HTMX)
- **Painel do lojista** para gestão (Next.js)
- **Painel administrativo** para suporte (Next.js)
- **Sistema multi-tenant** com isolamento de dados
- **Lista de espera** "avise-me quando chegar"
- **Monitoramento** com Grafana e Loki

## 📚 Seções da Documentação

| Seção | Descrição |
|---|---|
| [**Arquitetura**](architecture/overview.md) | Visão geral do sistema, modelos de domínio e decisões arquiteturais |
| [**Guias**](guides/developer-onboarding.md) | Tutoriais para desenvolvimento, deploy e configuração |
| [**Decisões**](decisions/) | Decisões de Arquitetura (ADRs) |


## Começando

Para configurar o ambiente local:

```bash
# Clone o repositório de infraestrutura
git clone https://github.com/sua-org/catalog-infra.git
cd catalog-infra

# Execute o script de setup
./scripts/setup-dev.sh
```

📊 Status do Projeto

| Componente |	Tecnologia |	Status |
|---|---|---|
| Backend API |	Go + Gin |	✅ Em desenvolvimento |
| Catálogo |	HTMX + Nginx |	✅ Em desenvolvimento |
| Painel Lojista |	Next.js |	🚧 Planejado |
| Painel Admin | 	Next.js |	🚧 Planejado |
| Banco de Dados |	PostgreSQL |	✅ Configurado |
| Cache |	Redis |	✅ Configurado |
| Logs |	Loki + Grafana |	✅ Configurado |
