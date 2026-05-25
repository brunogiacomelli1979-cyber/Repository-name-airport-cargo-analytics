# Definição dos KPIs

Este documento descreve os principais indicadores utilizados no projeto **Airport Cargo Operations Analytics**.

Os KPIs foram definidos para medir performance operacional, conformidade regulatória, qualidade da informação, armazenagem adequada e responsabilidade dos atrasos.

```text
## 1. Total de Voos

Quantidade total de voos analisados no período.

**Objetivo:** medir o volume operacional processado pelo terminal.

---

## 2. Total de Cargas / AWBs

Quantidade total de cargas ou conhecimentos aéreos considerados na análise.

**Objetivo:** medir o volume documental e operacional da importação aérea.

---

## 3. Total de Volumes

Soma total dos volumes recebidos.

**Objetivo:** medir a carga física movimentada pela operação.

---

## 4. Peso Total Movimentado

Soma do peso recebido em quilogramas.

**Objetivo:** medir a representatividade operacional da carga movimentada.

---

## 5. Tempo até Recebimento no Sistema do Depositário

Tempo entre a chegada da aeronave e o registro/recebimento no sistema interno do depositário.

**Fórmula:**

Data/hora de recebimento no sistema do depositário - Data/hora de chegada da aeronave

Objetivo: medir a eficiência da etapa inicial de recebimento e registro interno.

---

6. Tempo entre Recebimento no Depositário e Encerramento no Siscomex/Mantra

Tempo entre o recebimento no sistema do depositário e o encerramento oficial no Siscomex/Mantra.

Fórmula:

Data/hora de encerramento no Siscomex/Mantra - Data/hora de recebimento no sistema do depositário

Objetivo: identificar gargalos de conferência, conciliação, inconsistências, retrabalho, correção de informações ou pendências antes do encerramento.

---

7. Tempo Total até Encerramento no Siscomex/Mantra

Tempo entre a chegada da aeronave e o encerramento no Siscomex/Mantra.

Fórmula:

Data/hora de encerramento no Siscomex/Mantra - Data/hora de chegada da aeronave

Objetivo: medir o tempo total até o encerramento oficial, considerando impacto operacional e conformidade regulatória.

---

8. Percentual de Encerramentos Dentro do Prazo Regulatório

Percentual de voos encerrados dentro do prazo regulatório adotado no projeto.

Fórmula:

Voos dentro do prazo / Total de voos

Objetivo: acompanhar conformidade regulatória no encerramento no Siscomex/Mantra.

---

9. Percentual de Voos com Inconsistências

Percentual de voos que apresentaram ao menos uma inconsistência operacional, documental ou de manifesto.

Fórmula:

Voos com inconsistência / Total de voos

Objetivo: medir a incidência de problemas que podem impactar conferência, encerramento e liberação.

---

10. Taxa de Erro de Manifesto

Percentual de cargas com erro ou ausência de informação declarada pela companhia aérea.

Exemplos:

Divergência de peso
Divergência de volumes
Natureza da carga não informada
AWB divergente
Erro de digitação
Descrição incompleta

Fórmula:

Cargas com erro de manifesto / Total de cargas

Objetivo: avaliar a qualidade das informações declaradas e seu impacto nos tempos operacionais.

---

11. Taxa de Retrabalho Operacional

Percentual de cargas ou voos que exigiram retrabalho.

Exemplos:

Recontagem
Repesagem
Retorno para conferência
Correção de identificação
Tratamento de DSIC

Fórmula:

Cargas com retrabalho / Total de cargas

Objetivo: medir o impacto de inconsistências e falhas no fluxo operacional.

---

12. Tempo Médio de Retrabalho

Tempo médio gasto em atividades de retrabalho.

Fórmula:

Soma do tempo de retrabalho / Total de ocorrências de retrabalho

Objetivo: medir o impacto operacional das atividades adicionais de conferência, recontagem ou repesagem.

---

13. Cargo Dwell Time Total

Tempo total de permanência da carga no terminal.

Fórmula:

Data/hora de entrega ou retirada - Data/hora de chegada/recebimento da carga

Objetivo: medir o ciclo completo da carga dentro do terminal.

---

14. Cargo Dwell Time Operacional Limpo

Tempo de permanência da carga considerando apenas etapas sob influência operacional do depositário.

Objetivo: diferenciar o desempenho operacional interno de atrasos externos, regulatórios ou documentais.

---

15. Percentual de Atrasos por Grupo Responsável

Distribuição percentual dos atrasos conforme o grupo responsável ou influenciador.

Grupos possíveis:

Aeroporto / fiel depositário
Companhia aérea
Receita Federal
Órgão anuente
Importador / despachante
Transportadora / cliente
Causa mista
Não identificado

Objetivo: evitar atribuição incorreta de responsabilidade pelos atrasos.

---

16. Percentual de Atrasos Controláveis pelo Aeroporto

Percentual de atrasos classificados como controláveis pelo fiel depositário.

Classificações possíveis:

Controlável pelo aeroporto
Parcialmente controlável
Não controlável pelo aeroporto

Objetivo: separar gargalos internos de fatores externos.

---

17. Taxa de Conformidade de Armazenagem

Percentual de cargas armazenadas em área compatível com sua natureza declarada.

Fórmula:

Cargas armazenadas corretamente / Total de cargas armazenadas

Exemplos de comparação:

Natureza declarada → Área esperada
Área esperada → Área real de armazenagem

Objetivo: avaliar se a carga foi direcionada corretamente para área geral, refrigerada, DGR, valiosa, avariada ou pendente.
```
Observação

Os indicadores devem ser analisados em conjunto. O tempo total da carga no terminal não deve ser interpretado automaticamente como responsabilidade do aeroporto, pois pode incluir etapas externas, regulatórias, documentais e dependências de outros agentes.
