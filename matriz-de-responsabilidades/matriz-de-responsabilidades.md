# Matriz de Responsabilidades ou Matriz RACI — Governança da Fábrica de Software

## Objetivo

Manter a matriz RACI **versionada**, **auditável** e **fácil de ler**. Este diretório é a fonte de verdade para papéis e responsabilidades.

## Convenções

- **R** (Responsible): executa a tarefa.
- **A** (Accountable): aprova / é o dono final.
- **C** (Consulted): deve ser consultado antes da entrega.
- **I** (Informed): deve ser comunicado após mudanças.

**Prioridade:** Alta, Média, Baixa.  
**Escopo:** manter atividades claras, mensuráveis e sem sobreposição.

## Matriz

| Prioridade | Atividade                                                                    | Arquiteto de Software | Coordenador Técnico | Desenvolvedor |
| ---------- | ---------------------------------------------------------------------------- | --------------------- | ------------------- | ------------- |
| Alta       | Definição da Arquitetura de Referência (Boilerplate)                         | R                     | A                   | C             |
| Médio      | Modelagem C4/UML                                                             | R                     | A                   | I             |
| Médio      | Sugestões via RFCs e Design Docs                                             | R                     | R                   | R             |
| Alta       | Criação da Matriz de Tecnologias Homologadas                                 | R                     | A                   | C             |
| Média      | Definição de design de código (Ports And Adapters, DDD, Clean Arch, etc..)   | C                     | R                   | C             |
| Média      | Definição de fitness function de validação de design de código               | C                     | R                   | I             |
| Média      | Code Review                                                                  | C                     | A                   | A             |
| Alta       | Implementação Backend                                                        | C                     | A                   | R             |
| Alta       | Implementação de Frontend                                                    | C                     | A                   | R             |
| Médio      | Integração com Mensageria                                                    | C                     | A                   | R             |
| Médio      | Testes Unitários (Backend)                                                   | C                     | A                   | R             |
| Médio      | Testes Unitários (Frontend)                                                  | C                     | A                   | R             |
| Médio      | Ajustes de performance (Backend)                                             | C                     | A                   | R             |
| Médio      | Ajustes de performance (Frontend)                                            | C                     | A                   | R             |
| Médio      | QA - Testes Funcionais                                                       | I                     | R                   | C             |
| Médio      | Testes de Regressão                                                          | C                     | R                   | I             |
| Médio      | Testes de Segurança                                                          | R                     | A                   | I             |
| Médio      | Validação de requisitos                                                      | C                     | R                   | R             |
| Alta       | Definição de Pipelines CI/CD                                                 | R                     | A                   | I             |
| Alta       | Implantação de Observabilidade                                               | R                     | A                   | I             |
| Alta       | Gestão de Ambientes (dev/stg/prd)                                            | R                     | A                   | R             |
| Alta       | Gestão de Incidentes                                                         | I                     | A                   | R             |
| Médio      | Gestão de Requisitos e Priorização                                           | C                     | R                   | R             |
| Alta       | Comunicação com Stakeholders                                                 | I                     | R                   | R             |
| Alta       | Aprovação de Entregas                                                        | I                     | R                   | C             |
| Alta       | Definição de Políticas de Segurança                                          | R                     | R                   | I             |
| Médio      | Consultoria em Arquitetura Segura                                            | R                     | A                   | C             |
| Médio      | Implementação de Auditoria de Logs e Eventos                                 | R                     | A                   | C             |
