# Olá, sou o Victor Silva Azevedo 👋

Profissional de TI com foco em **ITSM, automação e GLPI**: implantação, customização e desenvolvimento de plugins para o GLPI 11.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-victor--silva--azevedo-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-silva-azevedo/)
[![E-mail](https://img.shields.io/badge/E--mail-svictorazevedo%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:svictorazevedo@gmail.com)

## 🧠 Especialidades

- **GLPI**: implantação, customização e desenvolvimento de plugins (PHP, GLPI 11)
- **Gestão de serviços**: ITIL, ISO 20000, ISO 27001, ISO 38500, LGPD
- **Automação e IA**: workflows no n8n integrando GLPI, Microsoft Teams e Jira; assistentes de IA via MCP (Model Context Protocol)

## 🔌 Plugins para GLPI 11

| Plugin | O que faz | Versão |
|---|---|---|
| **Governança de RDM** | BI de monitoramento, aprovação e conformidade das Requisições de Mudança. | 1.4.1 |
| **Indisponibilidades** | Painel ao vivo, em linguagem simples, dos serviços fora do ar por mudanças em execução, com próximas manutenções e calendário histórico. | 1.1.0 |
| **MCP Manager** | Transforma o GLPI em servidor MCP: assistentes de IA diagnosticam logs e gerenciam regras, formulários e categorias, com escopo por token e auditoria. | 1.1.0 |

<sub>Código mantido em repositórios privados.</sub>

## ⚙️ Automações com n8n

Workflows em produção que integram o GLPI ao dia a dia da equipe e dos usuários:

- **Notificações de chamados no Microsoft Teams**: o GLPI dispara webhooks (abertura, acompanhamento, atribuição, solução e encerramento) e o n8n envia mensagens diretas a requerentes, observadores e técnicos.
- **Comunicação de mudanças (RDM)**: quando uma mudança com indisponibilidade é aprovada, o aviso é publicado automaticamente em canal do Teams e no calendário de manutenções.
- **Enriquecimento de dados no GLPI**: extração de informações da descrição das mudanças para preencher campos como o prazo de solução.
- **Integração GLPI → Jira**: encaminhamento de demandas do service desk para o backlog das equipes de desenvolvimento.
- **Monitoramento dos próprios workflows**: alertas imediatos de falhas no Teams.
- **IA conectada ao GLPI**: assistentes de IA operam o GLPI via MCP (plugin MCP Manager) e o próprio n8n.

![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![GLPI](https://img.shields.io/badge/GLPI_11-1F2A44)
![Microsoft Teams](https://img.shields.io/badge/Microsoft_Teams-6264A7?logo=microsoftteams&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks-555555)

## 🚧 Projetos em destaque

### 🔧 Reestruturação do GLPI no MPMT

Padronização de categorias, urgência e prioridade, aplicação de SLAs, integração com dashboards e criação de formulários inteligentes.
🔗 [portaldeservicos.mpmt.mp.br](https://portaldeservicos.mpmt.mp.br)
