# Metodologia

Este projeto segue o processo de análise de dados apresentado no **Google Data Analytics Professional Certificate**:

Ask → Prepare → Process → Analyze → Share → Act

A metodologia foi adaptada para um contexto de BI operacional aplicado à logística aeroportuária de cargas de importação.

## 1. Ask

Definir o problema de negócio e as perguntas que o projeto deve responder.

Neste projeto, a pergunta principal é:

Como medir a performance da logística aeroportuária de cargas de importação, separando gargalos internos, atrasos externos, inconsistências operacionais e conformidade regulatória?

Principais pontos analisados:

Tempo até o encerramento no Siscomex/Mantra
Gargalos entre recebimento no sistema do depositário e encerramento no Siscomex/Mantra
Inconsistências de manifesto e divergências operacionais
Retrabalhos de conferência, recontagem ou repesagem
Conformidade da armazenagem conforme natureza declarada da carga
Responsabilidade e controlabilidade dos atrasos

## 2. Prepare

Definir quais dados são necessários para responder às perguntas do projeto.

Os dados serão simulados e organizados em tabelas relacionadas a:

Voos
Cargas/AWBs
Manifesto
Operações
Inconsistências
Liberação
Entrega

Todos os dados serão fictícios e utilizados apenas para fins educacionais e de portfólio.

## 3. Process

Preparar, limpar e transformar os dados para análise.

Principais atividades:

Padronização de datas e horários
Tratamento de campos nulos ou inconsistentes
Classificação de tipos de carga
Identificação de erros de manifesto
Cálculo de tempos operacionais
Classificação de atrasos por responsabilidade
Classificação de controlabilidade dos gargalos

Ferramentas previstas:

Excel
Power Query
SQL

## 4. Analyze

Criar indicadores e análises para identificar padrões, gargalos e riscos operacionais.

Principais análises:

Tempo total até encerramento no Siscomex/Mantra
Tempo entre recebimento no depositário e encerramento no Siscomex/Mantra
Percentual de encerramentos dentro do prazo regulatório
Taxa de erro de manifesto
Taxa de retrabalho operacional
Taxa de conformidade de armazenagem
Cargo dwell time total
Cargo dwell time operacional limpo
Percentual de atrasos por grupo responsável
Percentual de atrasos controláveis pelo aeroporto

## 5. Share

Apresentar os resultados de forma clara e útil para tomada de decisão.

Entregas previstas:

Dashboard em Power BI
Consultas SQL documentadas
Prints das principais páginas do relatório
Documentação dos KPIs
README atualizado com visão geral, metodologia, ferramentas e principais resultados

## 6. Act

Transformar a análise em recomendações operacionais.

Exemplos de recomendações esperadas:

Priorizar voos com maior risco de atraso no encerramento
Monitorar erros de manifesto por companhia aérea ou origem
Reduzir retrabalhos por divergência de peso, volume ou identificação
Acompanhar cargas com maior risco de armazenagem inadequada
Separar atrasos controláveis pelo aeroporto de atrasos externos
Monitorar etapas regulatórias e anuências que impactam o dwell time
Observação

A metodologia será revisada ao longo do desenvolvimento do projeto, conforme a base simulada, consultas SQL e dashboard forem construídos.
