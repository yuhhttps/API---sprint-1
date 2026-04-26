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
- **Persona 1: Analista Institucional de Dados (CADI).**

- Descrição: Analista responsável pelo acompanhamento do desempenho dos municípios no comércio exterior.
- Necessidades: Analisar grandes volumes de dados de importação e exportação para identificar padrões, tendências e comparações entre municípios. No entanto, existem dificuldades devido à falta de organização e padronização dessas informações, além do alto tempo necessário para tratamento manual dos dados.
- Dores atendidas: A sprint 1 atende essa necessidade ao estruturar e apresentar os dados de forma visual e interativa, permitindo análises mais rápidas, comparações regionais eficientes e geração de insights estratégicos com menor esforço operacional.
    
- **Persona 2: Estudante/Pesquisador**
- Descrição: Usuário acadêmico que realiza estudos sobre logística e comércio exterior.
- Necessidades: O pesquisador necessita de dados confiáveis e estruturados para desenvolver análises e estudos sobre o comércio exterior. Porém, frequentemente enfrenta dificuldades na coleta, limpeza e organização dessas informações, o que consome tempo e limita a profundidade das análises.
- Dores atendidas: Contribuímos ao oferecer uma base de dados tratada e pronta para exploração, permitindo que o usuário foque na interpretação dos dados, identificação de padrões e desenvolvimento de estudos mais consistentes.

- **Persona 3: Analista de Logística**
- Descrição: Profissional responsável pelo planejamento e otimização de transporte e distribuição.
- Necessidades: O analista de logística busca entender quais vias de transporte são mais utilizadas, como os custos de frete impactam as operações e quais rotas são mais eficientes. Entretanto, a falta de dados integrados e de fácil visualização dificulta a análise logística completa.
- Dores atendidas: Atendemos essa necessidade ao disponibilizar dados sobre modais de transporte e custos associados, facilitando a identificação de padrões logísticos e contribuindo para a otimização das operações.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como Analista Institucional de Dados, quero visualizar os dados de importação e exportação por município e período para identificar padrões e comparar o desempenho entre regiões.         | Alta       | 5 pontos   |
| US2 | Como Estudante/Pesquisador, quero acessar dados organizados e filtráveis para realizar análises acadêmicas com maior rapidez e confiabilidade.         | Alta      | 5 pontos   |
| US3 | Como Analista de Logística, quero visualizar as vias de transporte utilizadas e os custos de frete para entender a eficiência logística e possíveis otimizações.         | Alta      | 5 pontos   |
| US4 | Como Analista Institucional de Dados, quero filtrar os dados por região administrativa e ano para realizar análises comparativas específicas.         | Alta      | 3 pontos   |
| US5 | Como Estudante/Pesquisador, quero visualizar gráficos da balança comercial para entender tendências ao longo do tempo.         | Média      | 3 pontos   |
| US6 | Como Analista de Logística, quero identificar os principais produtos (NCM) transportados para analisar o impacto na cadeia logística.         | Média      | 3 pontos   |
| US7 | Como Analista Institucional de Dados, quero visualizar os países de origem e destino das mercadorias para identificar mercados relevantes.         | Média      | 3 pontos   |
| US8 | Como Estudante/Pesquisador, quero visualizar um mapa com os municípios para compreender a distribuição geográfica dos dados.         | Média      | 2 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | [Funcionalidade X, Y]                        | Concluído|
| 02     | [Funcionalidade Z]                           | Em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário [ação principal]  
- O sistema deve registrar [evento importante]  
- Métricas coletadas: [exemplo: tempo de resposta, taxa de uso]  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio (exemplo: % de adesão, redução de custo, etc.)  

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
