---
title: Análise de Qualidade - Pontua
description: Relatório Fase 1 - Avaliação de Software segundo ISO/IEC 25040:2011 e ISO/IEC 25010:2011
---

# 📊 Análise de Qualidade do Software Pontua

## 1. Propósito da Avaliação e Uso Pretendido
O presente relatório tem como propósito avaliar a qualidade do **Pontua**, software educacional desenvolvido pela **Crianex**, que implementa a metodologia **PBL (Problem-Based Learning)** para cursos de Medicina e áreas afins.  

A avaliação será utilizada para:  
- Apoiar **decisões de adoção institucional** em diferentes universidades.  
- Fornecer subsídios para **priorização de melhorias técnicas** pela equipe de desenvolvimento.  
- Demonstrar o alinhamento do software com **padrões internacionais de qualidade** (ISO/IEC 25010:2011).  
- Contribuir para a **melhoria contínua da experiência do usuário**, tanto para professores quanto para estudantes.  

Dessa forma, os resultados aqui apresentados terão uso **estratégico** (decisões de médio e longo prazo) e **operacional** (ajustes imediatos de funcionalidades e implantação).

---

## 2. Requisitante e Partes Interessadas
- **Requisitante Principal:** Curso de Medicina da **Universidade UniRV** (Campus Luziânia), primeiro ambiente de aplicação do Pontua.  
- **Partes Interessadas (Stakeholders):**
  - **Alunos:** Demandam clareza, transparência e feedback rápido em avaliações.  
  - **Professores:** Necessitam de eficiência na gestão de notas, relatórios de turmas e facilidade no lançamento de atividades.  
  - **Coordenadores:** Buscam padronização institucional e dashboards que apoiem decisões acadêmicas.  
  - **Equipe Crianex (Desenvolvedora):** Requer feedback estruturado para melhorar a confiabilidade, escalabilidade e portabilidade do software.  
  - **Instituições de Ensino:** Pretendem reduzir custos administrativos, padronizar processos avaliativos e garantir conformidade legal (LGPD).  

A análise contempla como cada grupo se beneficia e como pode ser impactado pelas decisões tomadas a partir desta avaliação.

---

## 3. Tipo de Produto e Descrição Estruturada
O Pontua é um **software como serviço (SaaS)**, acessível via navegador e responsivo em dispositivos móveis. Sua proposta é centralizar avaliações acadêmicas e simplificar a adoção da metodologia **PBL** em contextos universitários.  

### Descrição Estruturada
- **Natureza do Produto:** Plataforma web educacional em nuvem.  
- **Interfaces Principais:** Área do aluno, área do professor, dashboards administrativos.  
- **Dependências Externas:** Autenticação via provedores (Google), banco de dados em nuvem, conformidade LGPD.  
- **Serviços Oferecidos:** Gestão de turmas, avaliações entre pares, relatórios de desempenho, indicadores de presença e feedback contínuo.  

Este enquadramento permite identificar quais aspectos podem ser medidos agora e quais requerem evolução futura.

---

## 4. Modelo de Qualidade
A avaliação será guiada pela **ISO/IEC 25010:2011**, que define o modelo de qualidade para sistemas e softwares.  

### Características Selecionadas:
- **Adequação Funcional (Functional Suitability)**  
  - **Subcaracterística: Completude Funcional**  
  Verifica se o Pontua cobre integralmente as funções necessárias para a condução do PBL, sem lacunas que comprometam o processo educacional.  

- **Portabilidade (Portability)**  
  - **Subcaracterística: Substituibilidade**  
  Avalia a capacidade do Pontua de substituir sistemas anteriores (ex.: planilhas ou softwares distintos), sem grandes impactos ou custos para a instituição.  

Essas escolhas foram realizadas por refletirem as maiores preocupações dos stakeholders: **garantir que o sistema entregue tudo que promete** e que **possa ser adotado facilmente em substituição a práticas existentes**.

---

## 5. Seleção e Priorização de Características
A seleção foi feita com base em três critérios: **impacto para os usuários finais, risco associado à não conformidade e relevância estratégica para a instituição**.  

- **Adequação Funcional / Completude Funcional** → alta prioridade por afetar diretamente o aprendizado dos estudantes e a rotina dos professores.  
- **Portabilidade / Substituibilidade** → prioridade estratégica por influenciar a decisão de adoção em larga escala por outras instituições.  

Dessa forma, optamos por um recorte de **2 características (com 1 subcaracterística cada)**, atendendo aos critérios de profundidade sem dispersão de foco.

---

## 6. Escopo, Profundidade e Objetos da Avaliação
- **Escopo Atual:** Avaliação da versão do Pontua utilizada no curso de Medicina da UniRV.  
- **Profundidade:**  
  - Completude Funcional → será analisada a cobertura do ciclo avaliativo PBL.  
  - Substituibilidade → será analisada a facilidade de transição do uso de planilhas para o Pontua.  
- **Fora de Escopo:**  
  - Questões de desempenho em larga escala.  
  - Internacionalização e suporte multilíngue.  
  - Funcionalidades em estágio de prototipagem.  

---

## 7. ODS Relacionados
O Pontua se conecta com diferentes **Objetivos de Desenvolvimento Sustentável (ODS)**:  
- **ODS 4 – Educação de Qualidade** → promove avaliações transparentes e aprendizado equitativo.  
- **ODS 9 – Indústria, Inovação e Infraestrutura** → representa inovação tecnológica no setor educacional.  
- **ODS 10 – Redução das Desigualdades** → padroniza critérios avaliativos, diminuindo disparidades.  
- **ODS 16 – Paz, Justiça e Instituições Eficazes** → fortalece a confiança institucional por meio da transparência nos processos.  

---

## 8. Organização do Relatório
O relatório seguirá a sequência definida pela **ISO/IEC 25040:2011**:  
1. **Fase 1:** Estabelecimento dos requisitos de avaliação (documento atual).  
2. **Fase 2:** Especificação da avaliação (métricas e critérios).  
3. **Fase 3:** Projeto da avaliação (plano e cronograma).  
4. **Fase 4:** Execução da avaliação (coleta de dados e análise).  
5. **Fase 5:** Conclusão e recomendações finais.  

---

## 9. Uso de IA
Foi utilizado **ChatGPT** como ferramenta de apoio para:  
- Estruturar critérios e seções do relatório.  
- Melhorar a clareza textual.  
- Auxiliar na adequação aos requisitos da norma.  

A equipe realizou **revisão crítica humana** para ajustar terminologias, garantir adequação ao contexto e validar coerência acadêmica.  

---

## 10. GitPage da Equipe
A equipe publicará este projeto em uma **GitPage**, construída com **AstroBuild**, garantindo:  
- Estrutura clara e rastreável das fases.  
- Links para documentação, releases e entregas da disciplina.  
- Navegabilidade adequada para avaliadores externos.  
- Acessibilidade e padronização de estilo.  

---

## 👥 Integrantes
- Daniel Paz dos Passos - 222021862
- Gabriel Fenelon Rocha Gonçalves - 211061743
- Guilherme Gusmão Nepomuceno - 232021516
- Letícia Assunção Aires Moreira - 190128712
- Otávio Oliveira de Maya Viana - 211029503
- Vítor Marconi Trancoso Albuquerque - 222006202
