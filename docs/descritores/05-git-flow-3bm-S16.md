# Git Flow (3BM — Semana 16)

## 1. Conceito e análise do descritor
O **Git Flow** estrutura o desenvolvimento paralelo por meio de branches com papéis bem definidos: `main` (código estável em produção), `develop` (integração das próximas entregas), `feature/*` (novas funcionalidades), `release/*` (preparação de versão) e `hotfix/*` (correções urgentes). Essa separação evita que trabalho em andamento interfira no código estável e reduz conflitos entre equipes paralelas.

## 2. Exemplo prático
Enquanto a versão `1.1` está sendo estabilizada na branch `release/1.1` e um erro urgente de produção é corrigido em `hotfix/1.0.1`, outros desenvolvedores continuam criando novas tarefas em `feature/cadastro` sem gerar conflitos diretos na versão em publicação.

## 3. Aplicação neste repositório
Analisamos como o isolamento por branches previne conflitos e adaptamos o conceito criando branches específicas por tarefa antes de integrar na `main`, mantendo o fluxo enxuto para o escopo da equipe.
