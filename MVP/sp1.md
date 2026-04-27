# 📌 MVP - Aldo Pereira Solutions.

## 🎯 Objetivo do MVP:
O MVP (Produto Mínimo Viável) tem como propósito validar a capacidade de análise e visualização de dados de comércio exterior no estado de São Paulo e seus municípios.

- Problema que resolve: Atualmente, informações sobre exportação estão dispersas e pouco acessíveis para análise prática, dificultando a identificação de padrões logísticos, oportunidades de mercado e tomada de decisão estratégica.

- Hipótese a ser validada: Se os dados de comércio exterior forem organizados, filtrados e apresentados de forma visual e interativa (via Power BI), será possível identificar padrões relevantes de exportação, facilitando análises estratégicas.

- Valor entregue ao usuário final: O MVP entrega um painel interativo com dados filtrados de comércio exterior (2021 e 2022) dos municípios do estado de São Paulo, permitindo uma visualização clara dos fluxos de exportação, identificação de principais produtos (NCM), compreensão dos modais de transporte utilizados e visualização geográfica dos municípios.

---

## 📝 Descrição da Solução
Nesta sprint, foi desenvolvida uma base inicial de análise de dados de comércio exterior, utilizando Python (Google Colab) para tratamento de dados e Power BI para visualização.

**✔ Funcionalidades principais:** 

- Criação de tabelas de exportação de São Paulo e municípios (2021 a 2022);
- Dados COMEXSTAT tratados;
- Gráficos interativos;
- Interação com filtros.
- Visualização de: Código NCM (produto), Valor FOB (US$), País de destino, Pia de transporte, Modais e Mapa dos países.


**⚠ Limitações conhecidas:**
- Análise restrita a apenas para exportação;
- Dados filtrados apenas para 2 anos (2021 e 2022);
- Interface limitada ao Power BI (não acessível externamente).


🎯 Escopo reduzido (MVP)

- Estruturação dos dados;
- Capacidade de filtragem;
- Geração de insights básicos via visualização.


---

## 👥 Personas / Usuários-Alvo


👥 **Persona 1: Analista Institucional de Dados (CADI).**
- Descrição: Analista responsável pelo acompanhamento do desempenho dos municípios no comércio exterior.
- Necessidades: Analisar grandes volumes de dados de importação e exportação para identificar padrões, tendências e comparações entre municípios. No entanto, existem dificuldades devido à falta de organização e padronização dessas informações, além do alto tempo necessário para tratamento manual dos dados.
- Dores atendidas: Estruturação e apresentação dos dados de forma visual e interativa, permitindo análises mais rápidas, comparações regionais eficientes e estratégicos com menor esforço operacional.

    
👥 **Persona 2: Estudante/Pesquisador**
- Descrição: Usuário acadêmico que realiza estudos sobre logística e comércio exterior.
- Necessidades: O pesquisador necessita de dados confiáveis e estruturados para desenvolver análises e estudos sobre o comércio exterior. Porém, frequentemente enfrenta dificuldades na coleta, limpeza e organização dessas informações, o que consome tempo e limita a profundidade das análises.
- Dores atendidas: Base de dados tratada e pronta para exploração, permitindo que o usuário foque na interpretação dos dados, identificação de padrões e desenvolvimento de estudos mais consistentes.


👥 **Persona 3: Analista de Logística**
- Descrição: Profissional responsável pelo planejamento e otimização de transporte e distribuição.
- Necessidades: O analista de logística busca entender quais vias de transporte e modais são mais utilizadas. Entretanto, a falta de dados integrados e de fácil visualização dificulta a análise logística completa.
- Dores atendidas: Atendemos essa necessidade ao disponibilizar dados sobre modais de transporte e suas respectivas vias, facilitando a identificação de padrões logísticos e contribuindo para a otimização das operações.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade |
|-----|-----------------------------------------------------------------------------|------------|
| US1 | Como Analista Institucional de Dados, quero visualizar os dados de importação e exportação por município e período para identificar padrões e comparar o desempenho entre regiões.         | Alta       |
| US2 | Como Estudante/Pesquisador, quero acessar dados organizados e filtráveis para realizar análises acadêmicas com maior rapidez e confiabilidade.         | Alta      |
| US3 | Como Analista de Logística, quero visualizar quais produtos foram exportados e suas respectivas quantidades, para analisar produtos em tendência e seu volume para planejamento.         | Média      |
| US4 | Como Analista Institucional de Dados, quero filtrar os dados por região administrativa e ano para realizar análises comparativas específicas.         | Média      |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Tabelas de exportação, Desenvolvimento inicial do dashboard no Power BI, Filtro de dados para São Paulo.                        | Concluído|
| 02     | Expansão e continuidade do projeto seguindo correções e feedbakcs                           | Em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize e analise dados de exportação por município e período.  
- O sistema deve registrar os dados de comércio exterior estruturados em tabelas de exportação garantindo a consistência das informações.
- Métricas coletadas: tempo de resposta do dashboard, nível de interação com gráficos (cliques e seleções) e visualização.  

---

## 📈 Métricas de Validação

**Número de usuários que testaram o MVP:** 2

Os testes foram realizados por membros da equipe, sendo Luiz Augusto (Scrum Master - SM) e Felipe Borges (Team Member - TM).

    
**Feedback qualitativo (positivo/negativo):**

De forma geral, os feedbacks foram positivos, destacando a organização dos dados, a clareza das visualizações e a facilidade de uso dos filtros no dashboard. Os avaliadores relataram que a ferramenta permite compreender rapidamente os padrões de exportação, facilitando a análise comparativa entre municípios e países.

  
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


**- Prints de tela:**
  
<img width="1313" height="735" alt="WhatsApp Image 2026-04-26 at 22 30 17" src="https://github.com/user-attachments/assets/46797722-b671-417b-b349-595dcb99f839" />

<img width="1333" height="752" alt="WhatsApp Image 2026-04-26 at 22 30 18" src="https://github.com/user-attachments/assets/86115b80-358c-4dc0-9ea6-db9cf72e64b5" />

<img width="1600" height="620" alt="WhatsApp Image 2026-04-26 at 22 30 18 (2)" src="https://github.com/user-attachments/assets/5ce27124-a4cd-4a6d-b667-46f7f7a7c4a1" />

<img width="1600" height="682" alt="WhatsApp Image 2026-04-26 at 22 30 19" src="https://github.com/user-attachments/assets/5e84f65d-dd25-45a5-886b-2e0923d8695d" />

<img width="1389" height="388" alt="WhatsApp Image 2026-04-26 at 22 30 20 (1)" src="https://github.com/user-attachments/assets/72e03c91-188e-4e3f-85ac-91602c2f2b9b" />

<img width="1600" height="518" alt="WhatsApp Image 2026-04-26 at 22 30 20" src="https://github.com/user-attachments/assets/8f585a79-fd3f-4d24-b414-a6ffe9a9d1c9" />


    
**- Fluxos ou protótipos:**  

- Dados de exportação: [Dados de exportação.pbix.zip](https://github.com/user-attachments/files/27131820/Dados.de.exportacao.pbix.zip)

  
- Códigos:

(https://drive.google.com/drive/u/3/folders/19I9O8V90gx16whe9Dl3pl7t601oejvzJ)

(https://drive.google.com/drive/u/3/folders/1OVMyGKbBzg-0-vlNbANG84wm4vDldCJl)



**- Vídeo (MVP):**  

(https://youtu.be/92MwSK13sgo)
