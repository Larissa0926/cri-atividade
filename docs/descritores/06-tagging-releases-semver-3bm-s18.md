# Tagging, releases e versionamento semântico (3BM — Semana 18)

## 1. Conceito e análise do descritor
O **Versionamento Semântico (SemVer)** utiliza o formato `MAJOR.MINOR.PATCH` (ex.: `1.0.0`) para indicar o impacto das mudanças: `MAJOR` para alterações incompatíveis, `MINOR` para novas funcionalidades compatíveis e `PATCH` para correções. Sincronizar as **tags locais** com o **repositório remoto** é essencial para que toda a equipe e os pipelines de deploy identifiquem exatamente o mesmo marco de versão.

## 2. Exemplo prático
Se um integrante cria a tag `v1.0.0` apenas no próprio computador e não envia para o GitHub, o restante do time e o sistema de deploy não enxergam a versão publicada, podendo gerar conflitos de numeração ou implantações de commits errados.

## 3. Aplicação neste repositório
Após a revisão e integração dos descritores na `main`, o grupo publica uma Release oficial sincronizada no GitHub (ex.: `v1.0.0`), garantindo rastreabilidade e marco claro de entrega.
