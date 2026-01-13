# AZ-400-Jan-2026

## Links do material/labs
- [Repo antigo do curso, cujos labs temos agora](https://github.com/MicrosoftLearning/AZ400-DesigningandImplementingMicrosoftDevOpsSolutions)
- [Repo novo do curso, ainda sem os labs associados](https://github.com/MicrosoftLearning/mslearn-devops)
- [Acesso ao laboratorio](https://esi.learnondemand.net/), você precisará de uma chave do treinamento, que será passada no chat da turma
- [Material do curso no MS-Learn](https://learn.microsoft.com/pt-br/credentials/certifications/exams/az-400/?tab=tab-learning-paths)

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
