# opensource-bds_data-ai-weekend-sp-2026-07
Conteúdos da apresentação "Docker Compose e Testcontainers podem ser ótimas opções para a rápida criação de ambientes de Desenvolvimento e Testes".

## Tecnologias, tópicos e soluções abordadas

- Testcontainers: https://testcontainers.com/
- Docker Compose: https://docs.docker.com/compose/
- Grafana GROT Academy: https://learn.grafana.com/
- OpenTelemetry: https://opentelemetry.io/
- Grafana k6: https://k6.io/
- Bogus for .NET: https://github.com/bchavez/Bogus
- Faker.js: https://fakerjs.dev/

## Exemplos
- .NET 10 + OpenTelemetry + Grafana: https://github.com/renatogroffe/aspnetcore10-opentelemetry-grafana-tempo-loki-prometheus-postgres-testcontainers_contagemacessos
- k6 + MySQL + Azure DevOps: https://github.com/renatogroffe/k6-buildextensions-mysql-loadtests-azdevops-pipelines
- MCP Server do MongoDB: https://github.com/renatogroffe/mongodb-mcp-vscode-githubcopilot
- Function App para geração de dados fake com Bogus: https://github.com/renatogroffe/azurefunctions-dotnet10-mcp-fakedata

## MCP Servers úteis ao se trabalhar com Bancos de Dados

| Descrição | Comando / URL de Ativação | Link |
|-----------|---------------------------|------|
| MCP Oficial do Microsoft Learn | `https://learn.microsoft.com/api/mcp` | https://github.com/microsoftdocs/mcp |
| MCP de geração de dados fake | `docker run -i --rm renatogroffe/dotnet10-consoleapp-mcp-fakedata` | Aplicação: https://github.com/renatogroffe/dotnet10-consoleapp-mcp-fakedata<br/><br/>Workflow do GitHub Actions para testes com k6: https://github.com/renatogroffe/k6-mcps-tests-docker-github-actions |
| MCP Oficial do draw.io | `https://mcp.draw.io/mcp` | https://github.com/jgraph/drawio-mcp |
| MCP Oficial do Excalidraw | `https://mcp.excalidraw.com` | https://github.com/excalidraw/excalidraw-mcp |
| Extensão Oficial do Postgres (inclui MCP Server) | - | https://marketplace.visualstudio.com/items?itemName=ms-ossdata.vscode-pgsql |
| Extensão Oficial do SQL Server (inclui MCP Server) | - | https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql |
| Extensão Oficial do MongoDB | - | https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode |
| Extensão Oficial do Mermaid (inclui MCP Server) | - | https://marketplace.visualstudio.com/items?itemName=MermaidChart.vscode-mermaid-chart |
