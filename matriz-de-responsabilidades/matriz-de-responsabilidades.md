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

| Prioridade | Atividade                                                                  | Arquiteto de Software | Coordenador Técnico | Desenvolvedor | Gestor da área 
| ---------- | -------------------------------------------------------------------------- | --------------------- | ------------------- | ------------- | ----------
| Alta       | Definição da Arquitetura de Referência (Boilerplate)                       | R                     | A                   | C             | I
| Médio      | Modelagem C4/UML                                                           | R                     | A                   | I             | I
| Médio      | Sugestões via RFCs e Design Docs                                           | R                     | A                   | R             | I
| Alta       | Criação da Matriz de Tecnologias Homologadas                               | R                     | A                   | C             | I
| Média      | Definição de design de código (Ports And Adapters, DDD, Clean Arch, etc..) | R                     | A                   | C             | I
| Média      | Definição de fitness function de validação de design de código             | R                     | A                   | I             | I
| Média      | Code Review                                                                | C                     | A                   | R             | I
| Alta       | Implementação Backend                                                      | C                     | A                   | R             | I
| Alta       | Implementação de Frontend                                                  | C                     | A                   | R             | I
| Médio      | Integração com Mensageria                                                  | C                     | A                   | R             | I
| Médio      | Testes Unitários (Backend)                                                 | C                     | A                   | R             | I
| Médio      | Testes Unitários (Frontend)                                                | C                     | A                   | R             | I
| Médio      | Ajustes de performance (Backend)                                           | C                     | A                   | R             | I
| Médio      | Ajustes de performance (Frontend)                                          | C                     | A                   | R             | I
| Médio      | QA - Testes Funcionais                                                     | I                     | A                   | C             | I
| Médio      | Testes de Regressão                                                        | C                     | A                   | I             | I
| Médio      | Testes de Segurança                                                        | R                     | A                   | I             | I
| Médio      | Validação de requisitos                                                    | C                     | A                   | R             | I
| Alta       | Definição de Pipelines CI/CD                                               | R                     | A                   | I             | I
| Alta       | Auxílio na implantação de Pipelines CI/CD                                  | R                     | A                   | R             | I
| Alta       | Implantação de Pipelines CI/CD                                             | C                     | A                   | R             | I
| Alta       | Operação de Pipelines CI/CD                                                | I                     | A                   | R             | I
| Alta       | Definição de ferramentas de Observabilidade (Tracing, Logs e métricas)     | R                     | A                   | C             | I
| Alta       | Auxilio na implantação de ferramentas de Observabilidade                   | R                     | A                   | R             | I
| Alta       | Implantação de ferramentas de Observabilidade (Tracing, Logs e métricas)   | C                     | A                   | R             | I
| Alta       | Operação de ferramentas de Observabilidade (Tracing, Logs e métricas)      | I                     | A                   | R             | I
| Alta       | Gestão de Ambientes (dev/stg/prd)                                          | C                     | A                   | R             | I
| Alta       | Gestão de Incidentes                                                       | I                     | A                   | R             | I
| Médio      | Gestão de Requisitos e Priorização                                         | C                     | A                   | R             | I
| Alta       | Comunicação com Stakeholders                                               | I                     | A                   | R             | I
| Alta       | Aprovação de Entregas                                                      | I                     | R                   | C             | A
| Alta       | Definição de Políticas de Segurança                                        | R                     | A                   | I             | I
| Médio      | Consultoria em Arquitetura Segura                                          | R                     | C                   | I             | A
| Médio      | Implementação de Auditoria de Logs e Eventos                               | C                     | A                   | R             | I
