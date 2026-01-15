# AZ-400-Jan-2026

# Preencher a avaliacão do curso!!
https://www.metricsthatmatter.com/student/evaluation.asp?k=79335&i=91827
## Meus dados de contato
- [Perfil do Linkedin](https://www.linkedin.com/in/renatodealmeidamartins/)
- Email: renatoalmeidamartins@gmail.com
## Links do material/labs
- [Repo antigo do curso, cujos labs temos agora](https://github.com/MicrosoftLearning/AZ400-DesigningandImplementingMicrosoftDevOpsSolutions)
- [Repo novo do curso, ainda sem os labs associados](https://github.com/MicrosoftLearning/mslearn-devops)
- [Acesso ao laboratorio](https://esi.learnondemand.net/), você precisará de uma chave do treinamento, que será passada no chat da turma
- [Material do curso no MS-Learn](https://learn.microsoft.com/pt-br/credentials/certifications/exams/az-400/?tab=tab-learning-paths)

## Ideia para preparacao para o exame
Pode-se usar uma ferramenta de IA qualquer (ChatGPT, Gemini, Copilot) com um prompt parecido com o abaixo:
```
Estou me preparando para o exame AZ-400. Quero que voce seja meu assistente de estudo, e crie questoes que se parecem com as
questoes do exame, em formato e conteudo. APos minha resposta, comente o que eu acertei e errei, apresentando links para
estudo adicional. Aqui esta o guia de estudo do exame https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-400 e
as questoes tendem a ter formatos de multipla escolha, ou as vezes baseado em cenario, conforme descrito com mais detalhes aqui https://learn.microsoft.com/en-us/credentials/certifications/exams/az-400/
Nao apresenta as respostas ate que eu informe a minha escolha. Vamos comecar?
```
## Links por "caminho de aprendizagem" 
### Caminho de aprendizagem 1 - Desenvolvimento para DevOps Empresarial
- Infos sobre devops (livros e apresentações)
  - [Livro projeto fenix](https://www.amazon.com.br/Projeto-F%C3%AAnix-Comemorativa-Romance-Neg%C3%B3cio/dp/8550814067/)
  - [Livro Manual de Devops](https://www.amazon.com.br/Manual-DevOps-confiabilidade-organiza%C3%A7%C3%B5es-tecnol%C3%B3gicas/dp/8550802697)
  - [Livro Projeto unicórnio, o "outro lado da cerca" do projeto fenix](https://www.amazon.com.br/Projeto-Unic%C3%B3rnio-Romance-Desenvolvedores-Disrup%C3%A7%C3%A3o/dp/6555203447)
  - [Livro Accelerate](https://www.amazon.com.br/Accelerate-Software-Performing-Technology-Organizations-ebook/dp/B09JWS32W1)
  - [Relatório state of devops, de 2024, é publicado anualmente, pesquisando por anos mais recentes é fácil encontrar](https://dora.dev/research/2024/dora-report/)
  - [Video que, em essencia, "lança" o termo DevOps, na Velocity Conference de 2009](https://www.youtube.com/watch?v=LdOe18KhtT4)
  - [Não há lugar como produção](https://imwrightshardcode.com/2010/12/theres-no-place-like-production/)
  - Postmortems sem culpa
    - [Cultura de postmortem na Google](https://sre.google/sre-book/postmortem-culture/)
    - [Como conduzir um post-mortem sem culpa, pela Atlassian](https://www.atlassian.com/incident-management/postmortem/blameless)
  - [Manifesto ágil](https://agilemanifesto.org/)
  - [Livro "Measure what matters", trata de métricas - OKRs - objective key results](https://www.amazon.com.br/Measure-What-Matters-Foundation-English-ebook/dp/B078FZ9SYB/)
  - Procurar pelo livro "Stop starting, start finishing". Excelente sobre diminuição do work in progress. Não está disponível na Amazon hoje em dia.
  - Modelo de preços e licenciamento. Atenção que projetos de open-source tem certa gratuidade. Além disso, licenças de Visual Studio podem trazer agregadas licenças de GitHub ou Azure DevOps
    - [Azure DevOps](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/)
    - [GitHub](https://github.com/pricing)
- [Epics, iniciativas e user stories](https://www.atlassian.com/agile/project-management/epics-stories-themes)
- Estratégias de branching
  - [GitFlow - uma estratégia muito popular de branching](https://nvie.com/posts/a-successful-git-branching-model/)
  - [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)
  - [Extensão para lidar com gitflow](https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html)
  - [Estratégia de forking](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)
    
- Proteção de branches
  - [No GitHub](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches)
  - [No AzureDevops](https://learn.microsoft.com/en-us/azure/devops/repos/git/branch-policies?view=azure-devops&tabs=browser)
- [Git hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- Otimizando repositorios
  - [Large file storeage - LFS](https://git-lfs.com/)
  - [Uso de depth no git clone](https://git-scm.com/docs/git-clone)
  - [Scalar - otimiza no geral a clonagem de repos](https://git-scm.com/docs/scalar)
- Registro de alterações 
  - [Uso avançado de git log](https://www.atlassian.com/git/tutorials/git-log)
  - [Git log](https://git-scm.com/docs/git-log)
  - [Github-changelog-generator](https://github.com/github-changelog-generator/github-changelog-generator)
- [Limpeza de repos com git-repo-cleaner](https://rtyley.github.io/bfg-repo-cleaner/)
- [CLI do Github](https://cli.github.com/manual/)
- [git tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging)
- [Libro clean code, interessantissimo discutindo como código bem escrito pode dispensar documentação extensa)](https://www.amazon.com.br/C%C3%B3digo-limpo-Robert-C-Martin/dp/8576082675)
### Caminho de aprendizagem 2 - Implementar a CI com o Azure Pipelines e o GitHub Actions
- [Referência de tarefas disponíveis em Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/?view=azure-pipelines)
- [Hierarquia (stage -> job -> step) de um pipeline](https://learn.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/pipeline?view=azure-pipelines)
- [Info com software instalado em cada tipo de agente no Azure pipelines - note que ao clicar nos links detalhados, ele vai pra documentação de GitHub actions, que ao final é a mesma coisa](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=windows-images%2Cyaml)
- [Job baseado em container, com este se tem um controle mais findo das versões dos componentes instalados do que em um baseado em agente, dado que você o define via Dockerfile](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops&tabs=windows)
- [Job de deplyment](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs?view=azure-devops)
- [Tipos de autenticação em agentes self-hosted](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/agent-authentication-options?view=azure-devops)
- [Permissões em Azure pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/policies/permissions?view=azure-devops)
- [Custo e configuracão de jobs paralelos](https://learn.microsoft.com/en-us/azure/devops/pipelines/licensing/concurrent-jobs?view=azure-devops&tabs=self-hosted)
- Definindo requisitos especiais para pipelines e como combiná-los com recursos oferecidos pelo agente
  - [Demandas do pipeline](https://learn.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/pool-demands?view=azure-pipelines)
  - [Capacidades oferecidas pelo agente](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops&tabs=yaml%2Cbrowser#capabilities)
- [Task de ADO para publicar resultados de teste](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/publish-code-coverage-results-v2?view=azure-pipelines)
- [Uma das tasks de publicar resultado de teste em GitHub actions - publica em coveralls.io](https://github.com/coverallsapp/github-action?tab=readme-ov-file)
- [Criando ações para GitHub Actions](https://docs.github.com/en/actions/how-tos/create-and-publish-actions)
- [Eventos que podem ser usados como triggers de workflows](https://docs.github.com/en/actions/reference/workflows-and-actions/events-that-trigger-workflows)
- [Forma de autenticar GitHub com Azure, recomenda-se o uso de OIDC no lugar de segredos de service principals](https://learn.microsoft.com/en-us/azure/developer/github/connect-from-azure-openid-connect)
- [Multi-stage build em Docker](https://docs.docker.com/build/building/multi-stage/)
- [Comandos disponíveis num Dockerfile](https://docs.docker.com/reference/dockerfile/)
### Caminho de aprendizagem 3 - Projetar e implementar uma estratégia de lançamento
- Alguns conceitos de GitOps
  - [Definição de gitops pela Atlassian](https://www.atlassian.com/git/tutorials/gitops)
  - [Uma das soluções que suportam GitOps em Kubernetes, argoCD](https://argo-cd.readthedocs.io/en/stable/)
- Testes de disponibilidade
  - [Multi-step web test não existe desde o fim de 2024](https://azure.microsoft.com/en-us/updates?id=retirement-notice-transition-to-custom-availability-tests-in-application-insights)
  - [Azure app testing, sucessor do Azure load testing](https://learn.microsoft.com/en-us/azure/app-testing/overview-what-is-azure-app-testing)
- [Eventos de ciclo de vida de um release](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs?view=azure-devops#descriptions-of-lifecycle-hooks)
- [Lista de integrações suportadas nativamente no Azure Devops](https://learn.microsoft.com/en-us/azure/devops/service-hooks/overview?view=azure-devops)
- [Lista de variaveis pre-definidas de release](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/variables?view=azure-devops&tabs=batch)
- [Lista de variáveis pre-definidas como um todo (para além de pipelines de release)](https://learn.microsoft.com/en-us/azure/devops/pipelines/build/variables?view=azure-devops&tabs=yaml#pipeline-variables)

### Caminho de aprendizagem 4 - implementar uma implantação contínua segura usando o Azure Pipelines
- [12-factor app, uma boa referência para produção de aplicações "modernas" ](https://12factor.net/)
- [Deployment slots em app services](https://learn.microsoft.com/en-us/azure/app-service/deploy-staging-slots?tabs=portal)
- [Métodos de roteamento disponíveis em perfis do traffic manager](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods)
- Feature flags
  - [Conceito](https://learn.microsoft.com/en-us/dotnet/architecture/cloud-native/feature-flags)
  - [Azure App Configuration, serviço que possibilita o uso de feature flag, entre outras coisas](https://learn.microsoft.com/en-us/azure/azure-app-configuration/overview)
  - [Detalhes do App Configuration para feature flags](https://learn.microsoft.com/en-us/azure/azure-app-configuration/concept-feature-management)
- [Análise automatizada de canary no Netflix](https://netflixtechblog.com/automated-canary-analysis-at-netflix-with-kayenta-3260bc7acc69)
- [Roles disponíveis no GitHub variam em função do tipo de conta que se tem](docs.github.com/en/enterprise-cloud@latest/get-started/learning-about-github/types-of-github-accounts#enterprise-managed-users)
- [Identidades federadas são suportadas no Azure DevOps](https://devblogs.microsoft.com/devops/workload-identity-federation-for-azure-deployments-is-now-generally-available/)
- [Identidades federadas no GitHub](https://docs.github.com/en/actions/how-tos/secure-your-work/security-harden-deployments/oidc-in-azure)
- [Serviços que suportam managed identities](https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/managed-identities-status)
- [Tarefa DownloadSecureFile em Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/download-secure-file-v1?view=azure-pipelines&tabs=windows)
- [Consumindo segredos de Azure Key Vault em Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/azure-key-vault?view=azure-devops&tabs=managedidentity%2Cyaml)
### Caminho de aprendizagem 5 - Gerenciar a infraestrutura como código usando o Azure e o DSC
- [Suporte para export de recursos em Terraform no Portal](https://techcommunity.microsoft.com/blog/azuretoolsblog/announcing-public-preview-of-terraform-export-from-the-azure-portal/4409889)
- [Uso de segredos em templates ARM](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/key-vault-parameter?tabs=azure-cli)
- [Extensão Bicep para VS Code](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/visual-studio-code?tabs=azure-cli)
- [Runbooks sairam do Technet gallery e foram para repo GitHub](https://techcommunity.microsoft.com/blog/azuregovernanceandmanagementblog/azure-automation-runbooks-moving-to-github/2039337)
- [Repo com runbooks](https://github.com/azureautomation/runbooks/tree/master/Utility)
- [Codigo do Azure Automation pode (e deve) estar em controle de vers~ao](https://learn.microsoft.com/en-us/azure/automation/source-control-integration)
- [Uso de Workflows de powershell em Azure Automation](https://learn.microsoft.com/en-us/system-center/sma/overview-powershell-workflows?view=sc-sma-2025)
- [Runbook workers hibridos](https://learn.microsoft.com/en-us/azure/automation/automation-hybrid-runbook-worker)
- [Modulo de Workflow em powershell](https://learn.microsoft.com/en-us/powershell/module/psworkflow/?view=powershell-5.1)
- [PowerShell DSC](https://learn.microsoft.com/en-us/powershell/scripting/dsc/overview?view=powershell-7.5)
- [Modeos de deployment de um ARM template - incremental e complete](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-modes)

### Caminho de aprendizagem 6 - implementar a segurança e validar bases de código para conformidade
- [Arquitetura zero trust, conforme definidopelo NIST](https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf)
- [Exploits of a mom, tirinha do XKCD exemplificando de forma divertida um ataque de SQL injection](https://xkcd.com/327/)
- [Ferramenta de modelagem de ameaças publicada pelo OWASP](https://owasp.org/www-project-threat-dragon/)
- [OWASP também pubilca o top 10, ilustrando os principais ataques a aplicações](https://owasp.org/www-project-top-ten/)
- [Threat modeling tool, ferramenta de modelagem de ameaças publicada pela MS](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool)
- [CodeQL, linguagem de análise semântica de código no GitHub para detecção de vulnerabilidades no código](https://codeql.github.com/)
- [Recursos para aprendizado de codeQL](https://github.com/advanced-security/awesome-codeql?tab=readme-ov-file)
- [Dependabot do GitHub, te ajuda a identificar vulnerabilidades nos seus pacotes](https://docs.github.com/en/code-security/how-tos/secure-your-supply-chain/secure-your-dependencies/configuring-dependabot-security-updates)
- [Microsoft Defender for Cloud tem vários planos, que protegem variados tipos de recursos](https://azure.microsoft.com/en-us/pricing/details/defender-for-cloud/)
- [Linguagem de definicao de politicas no Azure](https://learn.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure-basics)
- [Bloqueios de recursos no Azure - resource lock, com dois "sabores": DoNotDelete, ReadOnly](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json)
- [GitHub Advanced security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security)
### Caminho de aprendizagem 7 - Projetar e implementar uma estratégia de gerenciamento de dependência
- [Semantic versioning](https://semver.org/lang/pt-BR/)
- [Permissões em feeds do Azure artifacts](https://learn.microsoft.com/en-us/azure/devops/artifacts/feeds/feed-permissions?view=azure-devops)
- [GitHub packages](https://docs.github.com/en/packages/quickstart)
### Caminho de aprendizagem 8 - AZ-400: Implementar comentários contínuos (continuous feedback)
- [Livros de SRE, gratuitos, no Google.](https://sre.google/books/)
- [Repositorio com queries em KQL](https://github.com/microsoft/AzureMonitorCommunity)
- [Resource Graph Explorer, serviço que te deixa consultar dados de toda a sua estrutura de Azure, utilizando KQL](https://learn.microsoft.com/en-us/azure/governance/resource-graph/overview)
- [Uso de dashboards no Azure](https://learn.microsoft.com/en-us/azure/azure-portal/azure-portal-dashboards)
- [GitHub publicando mensagens no Teams, via app](https://teams.github.com/)
- [Azure DevOps publicando no Teams](https://learn.microsoft.com/en-us/azure/devops/service-hooks/services/teams?view=azure-devops)
- [Conector do Azure para criação de eventos em serviços de ITSM - suportados são: ServiceNoe, Provance, Cherwell, SCSM](https://marketplace.microsoft.com/en-us/product/azure-services/microsoft.itsmconnector?tab=Overview)
- [Smart detection no application insights está sendo removido, privilegiando a configuração por alertas](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-smart-detections-migration)
