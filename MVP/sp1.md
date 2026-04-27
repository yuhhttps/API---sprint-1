# 📌 MVP - Aldo Pereira Solutions.

## 🎯 Objetivo do MVP:
O MVP (Produto Mínimo Viável) tem como propósito validar a capacidade de análise e visualização de dados de comércio exterior no estado de São Paulo, com foco inicial em regiões específicas.

- Problema que resolve: Atualmente, informações sobre importação e exportação estão dispersas e pouco acessíveis para análise prática, dificultando a identificação de padrões logísticos, oportunidades de mercado e tomada de decisão estratégica.

- Hipótese a ser validada: Se os dados de comércio exterior forem organizados, filtrados e apresentados de forma visual e interativa (via Power BI), será possível identificar padrões relevantes de importação e exportação, facilitando análises estratégicas.

- Valor entregue ao usuário final: O MVP entrega um painel interativo com dados filtrados de comércio exterior (2022 e 2023) das regiões administrativas de São José do Rio Preto e Santos, permitindo:

-> Visualização clara dos fluxos de importação e exportação

-> Identificação de principais produtos (NCM)

-> Análise de valores (FOB e frete)

-> Compreensão dos modais de transporte utilizados

-> Visualização geográfica dos municípios

---

## 📝 Descrição da Solução
Nesta sprint, foi desenvolvida uma base inicial de análise de dados de comércio exterior, utilizando Python (Google Colab) para tratamento de dados e Power BI para visualização.

✔ Funcionalidades principais: 
**Criação de tabelas de:*
- Exportação (2021 a 2026);
- Importação (2021 a 2026);
- Regiões administrativas;

**Filtro de dados no Power BI para:**
- Regiões: São José do Rio Preto e Santos;
- Período: 2022 e 2023.

**Visualização das seguintes informações:**
- Código NCM (produto);
- Valor FOB (US$);
- Valor de frete;
- País de origem/destino;
- Via de transporte;
- Mapa com municípios das regiões.


⚠ Limitações conhecidas:
- Análise restrita a apenas 2 regiões administrativas;
- Dados filtrados apenas para 2 anos (2022 e 2023);
- Interface limitada ao Power BI (não acessível externamente).


🎯 Escopo reduzido (MVP)

O foco foi validar:

- Estruturação dos dados;
- Capacidade de filtragem;
- Geração de insights básicos via visualização.


---

## 👥 Personas / Usuários-Alvo


👥 **Persona 1: Analista Institucional de Dados (CADI).**
- Descrição: Analista responsável pelo acompanhamento do desempenho dos municípios no comércio exterior.
- Necessidades: Analisar grandes volumes de dados de importação e exportação para identificar padrões, tendências e comparações entre municípios. No entanto, existem dificuldades devido à falta de organização e padronização dessas informações, além do alto tempo necessário para tratamento manual dos dados.
- Dores atendidas: A sprint 1 atende essa necessidade ao estruturar e apresentar os dados de forma visual e interativa, permitindo análises mais rápidas, comparações regionais eficientes e geração de insights estratégicos com menor esforço operacional.

    
👥 **Persona 2: Estudante/Pesquisador**
- Descrição: Usuário acadêmico que realiza estudos sobre logística e comércio exterior.
- Necessidades: O pesquisador necessita de dados confiáveis e estruturados para desenvolver análises e estudos sobre o comércio exterior. Porém, frequentemente enfrenta dificuldades na coleta, limpeza e organização dessas informações, o que consome tempo e limita a profundidade das análises.
- Dores atendidas: Contribuímos ao oferecer uma base de dados tratada e pronta para exploração, permitindo que o usuário foque na interpretação dos dados, identificação de padrões e desenvolvimento de estudos mais consistentes.


👥 **Persona 3: Analista de Logística**
- Descrição: Profissional responsável pelo planejamento e otimização de transporte e distribuição.
- Necessidades: O analista de logística busca entender quais vias de transporte são mais utilizadas, como os custos de frete impactam as operações e quais rotas são mais eficientes. Entretanto, a falta de dados integrados e de fácil visualização dificulta a análise logística completa.
- Dores atendidas: Atendemos essa necessidade ao disponibilizar dados sobre modais de transporte e custos associados, facilitando a identificação de padrões logísticos e contribuindo para a otimização das operações.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como Analista Institucional de Dados, quero visualizar os dados de importação e exportação por município e período para identificar padrões e comparar o desempenho entre regiões.         | Alta       | 5 pontos   |
| US2 | Como Estudante/Pesquisador, quero acessar dados organizados e filtráveis para realizar análises acadêmicas com maior rapidez e confiabilidade.         | Alta      | 4 pontos   |
| US3 | Como Analista de Logística, quero visualizar quais produtos foram exportados e suas respectivas quantidades, para analisar produtos em tendência e seu volume para planejamento.         | Média      | 4 pontos   |
| US4 | Como Analista Institucional de Dados, quero filtrar os dados por região administrativa e ano para realizar análises comparativas específicas.         | Média      | 3 pontos   |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Tabelas de importação e exportação, Desenvolvimento inicial do dashboard no Power BI, Filtro de dados para as regiões de São José do Rio Preto e Santos (2022 e 2023).                        | Concluído|
| 02     | (Continuidade do projeto seguindo correções e feedbakcs)                           | Em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize e analise dados de importação e exportação por município, região administrativa e período.  
- O sistema deve registrar os dados de comércio exterior estruturados em tabelas de importação, exportação e regiões administrativas, garantindo a consistência das informações.
- Métricas coletadas: tempo de resposta do dashboard,  e nível de interação com gráficos (cliques e seleções).  

---

## 📈 Métricas de Validação

**Número de usuários que testaram o MVP:** 2

Os testes foram realizados por membros da equipe, sendo Luiz Augusto (Scrum Master - SM) e Felipe Borges (Team Member - TM).

    
**Feedback qualitativo (positivo/negativo):**

De forma geral, os feedbacks foram positivos, destacando a organização dos dados, a clareza das visualizações e a facilidade de uso dos filtros no dashboard. Os avaliadores relataram que a ferramenta permite compreender rapidamente os padrões de importação e exportação, facilitando a análise comparativa entre regiões.

  
**Indicadores de negócio:**

- Redução do tempo de análise de dados;
- Aumento da eficiência na tomada de decisão;
- Melhoria na visualização e interpretação das informações;
- Apoio na identificação de oportunidades no comércio exterior;
- Redução de custos operacionais com análise manual de dados;
- Otimização de custos logísticos por meio da identificação de modais mais eficientes;
- Melhoria na alocação de recursos com base em dados confiáveis.
  
---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
