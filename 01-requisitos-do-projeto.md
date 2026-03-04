1. Objetivo do Produto
Criar um currículo técnico online, interativo, integrado com dashboard, KPIs, backend, bancos de dados, automações e arquitetura de telecomunicações, demonstrando competências práticas de Administração, Engenharia de Software e Telecom.
2. Escopo Inicial (MVP)Frontend
Página HTML/CSS/JS com CV
Seções: Sobre, Formação, Experiência, Projetos, Telecom, Contato
KPI cards em tempo real integrados com API
Embed de dashboard Power BI
Backend
API REST (FastAPI ou Node)
Endpoints: /cv, /skills, /experience, /kpis, /projects
Documentação Swagger
Banco de Dados
SQL (PostgreSQL) → dados relacionais do CV
MongoDB → projetos e textos não estruturados
Seeds de dados
DevOps / Infra
Docker + Docker Compose
Deploy em GitHub Pages (frontend) + Render / Railway (API) ou AWS
Telecom (Demonstração Técnica)
Topologia SS7
Topologia simples FTTH/VoIP
Fluxo SIP INVITE–ACK–BYE
KPIs: ASR, ACD, Jitter, Latência, Perda
Dashboard (Power BI)
Projetos
Competências
KPIs Telecom
Evolução da carreira
3. Requisitos Funcionais (RF)
RF01: Exibir CV completo em página HTML
RF02: Mostrar KPIs vindos da API
RF03: Carregar dados do SQL via API
RF04: Carregar dados não estruturados do MongoDB
RF05: Exibir dashboard Power BI
RF06: Enviar formulário via endpoint /contact
RF07: Exibir arquitetura telecom
4. Requisitos Não Funcionais (RNF)
RNF01: Frontend responsivo
RNF02: Versionamento via GitHub
RNF03: Containerização com Docker
RNF04: API documentada com OpenAPI
RNF05: Tempo de resposta API < 300 ms local
RNF06: Código padronizado com boas práticas
5. Restrições
Projeto deve ser concluído até 08/03/2026
Todo o código deve ser público no GitHub
Power BI deve ser público via embed
6. Critérios de Sucesso
CV Online acessível por link
Dashboard funcionando
API retornando dados reais do CV
Arquitetura telecom exibida
Docker funcionando end-to-end