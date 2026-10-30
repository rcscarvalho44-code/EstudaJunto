# Organização do time ágil — EstudaJunto

## Papéis do time

| Integrante | Matrícula | Papel | Atuação |
|---|---|---|---|
| Rogério Carvalho da Silva | 2612200 | Product Owner | Priorizar o Product Backlog e esclarecer o valor das entregas. |
| Eduardo Henrique de Sousa Silva | 2520231 | Scrum Master | Facilitar Scrum, apoiar na remoção de impedimentos e na melhoria do fluxo. |
| Sâmila Fortunato da Silva | 2520225 | Developer | Produzir e verificar entregas de documentação, prototipação, testes e desenvolvimento. |
| Gabriel de Castro dos Anjos | 2610966 | Developer | Produzir e verificar entregas de documentação, prototipação, testes e desenvolvimento. |
| Rayssa Ester Silva de Moraes | 2520496 | Developer | Produzir e verificar entregas de documentação, prototipação, testes e desenvolvimento. |

## Definition of Ready

Uma issue somente entra em **DOING** se todos estes itens estiverem verificados:

- [ ] Descrição clara do trabalho necessário.
- [ ] História de usuário com perfil, necessidade e benefício.
- [ ] Critérios de aceitação verificáveis.
- [ ] Prioridade MoSCoW registrada.
- [ ] Integrante responsável pela execução identificado.
- [ ] Dependências e impedimentos conhecidos identificados (ou indicação de que não há).

## Definition of Done

Uma entrega somente entra em **DONE** quando todos os critérios abaixo forem satisfeitos:

- [ ] Critérios de aceitação da issue atendidos.
- [ ] Trabalho revisado por outro integrante.
- [ ] Funcionalidade ou documento verificado conforme o tipo de entrega.
- [ ] Documentação atualizada quando necessário (ou registrado que não se aplica).
- [ ] Pull request vinculado à issue correspondente.
- [ ] Alterações integradas à branch `main`.

**Regra:** PR aberto não significa issue concluída. A entrada em DONE depende da integração à `main` e dos demais critérios acima.

## Matriz de stakeholders

| Stakeholder | Poder | Interesse | Quadrante/estratégia |
|---|---|---|---|
| Product Owner (Rogério) | Alto | Alto | Gerenciar de perto |
| Equipe de desenvolvimento | Médio | Alto | Manter informado |
| Professor-orientador do PI | Alto | Alto | Gerenciar de perto |
| Gestor do programa EstudaJunto | Alto | Alto | Gerenciar de perto |
| Professores supervisores | Alto | Alto | Gerenciar de perto |
| Alunos monitores | Baixo | Alto | Manter informado |
| Alunos com dificuldades | Baixo | Alto | Manter informado |
| Direção da instituição | Médio | Alto | Manter informado |

Classificações mantidas da atividade de Stakeholders da Aula 11. Poder médio segue o enquadramento adotado naquela entrega.

## Plano de comunicação

| Destinatários | Conteúdo | Meio/evento | Frequência | Responsável |
|---|---|---|---|---|
| PO e Developers | Prioridades e atividades da Sprint | Sprint Planning | A cada Sprint | Product Owner |
| PO e Developers | Progresso e impedimentos | Daily Scrum | Diária | Developers |
| Product Owner, equipe de desenvolvimento, professor-orientador, gestor do programa EstudaJunto e professores supervisores | Incremento e resultados | Sprint Review | A cada Sprint | Product Owner |
| Scrum Team | Dificuldades e melhorias internas | Sprint Retrospective | A cada Sprint | Scrum Master facilita; Developers participam |
| Alunos monitores e alunos com dificuldades | Funcionalidades destinadas aos estudantes | Reunião de apresentação | A cada entrega | Product Owner |
| Direção da instituição | Resultados e entregas | Relatório por e-mail | A cada entrega | Product Owner |

## Quadro e limite de WIP

O GitHub Projects vinculado ao repositório terá as colunas **TO-DO**, **DOING** e **DONE**, contendo as issues reais do backlog. O limite de trabalho em andamento é de **2 issues simultâneas em DOING**. O time possui cinco integrantes, sendo três Developers; limitar a execução simultânea a dois itens ajuda a reduzir dispersão e priorizar conclusões. Para mover de TO-DO para DOING, aplicar a DoR; para mover de DOING para DONE, aplicar a DoD. Impedimentos devem ser identificados na issue.

## Declaração de uso de IA

Ferramenta utilizada: **ChatGPT (OpenAI)**. Foi utilizada para apoiar a organização de documentação, propostas de templates, redação de histórias de usuário e critérios de aceitação, planejamento do backlog e instruções de uso do GitHub. O material foi elaborado a partir das atividades anteriores do EstudaJunto (Stakeholders, Mini Diagnóstico COBIT e protótipo Google Stitch) e das definições fornecidas pelo Product Owner nesta conversa, que aprovou escopo, papéis Scrum, DoR, DoD, templates, prioridades e WIP. Os registros de publicação, revisão e testes efetivamente realizados no GitHub deverão refletir o que ocorrer durante a execução; não são presumidos nesta declaração.
