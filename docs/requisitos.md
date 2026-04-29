# Documento de Requisitos — Sistema de Gestão para Clínica Odontológica

## 1. Introdução

Este documento descreve os requisitos do sistema de gestão para clínica odontológica, organizados em requisitos funcionais e não funcionais, visando apoiar o desenvolvimento, validação e manutenção do sistema.

---

## 2. Requisitos Funcionais (RF)

| ID   | Nome                             | Descrição                                                                |
| ---- | -------------------------------- | ------------------------------------------------------------------------ |
| RF01 | Cadastrar paciente               | O sistema deve permitir o cadastro de novos pacientes.                   |
| RF02 | Editar paciente                  | O sistema deve permitir a edição dos dados de pacientes cadastrados.     |
| RF03 | Remover paciente                 | O sistema deve permitir a exclusão de pacientes.                         |
| RF04 | Criar prontuário                 | O sistema deve permitir a criação/abertura de prontuário para pacientes. |
| RF05 | Atualizar prontuário             | O sistema deve permitir a atualização de informações do prontuário.      |
| RF06 | Remover prontuário               | O sistema deve permitir a exclusão de prontuários.                       |
| RF07 | Upload de imagens no prontuário  | O sistema deve permitir anexar imagens ao prontuário do paciente.        |
| RF08 | Criar agendamento                | O sistema deve permitir o agendamento de consultas.                      |
| RF09 | Editar agendamento               | O sistema deve permitir alterar agendamentos existentes.                 |
| RF10 | Cancelar agendamento             | O sistema deve permitir a exclusão/cancelamento de consultas.            |
| RF11 | Definir horário de funcionamento | O sistema deve permitir configurar horários de funcionamento da clínica. |
| RF12 | Bloquear horários                | O sistema deve permitir bloquear horários por indisponibilidade.         |
| RF13 | Cadastrar tratamento/serviço     | O sistema deve permitir cadastrar tratamentos/serviços.                  |
| RF14 | Editar tratamento/serviço        | O sistema deve permitir editar tratamentos/serviços cadastrados.         |
| RF15 | Remover tratamento/serviço       | O sistema deve permitir excluir tratamentos/serviços.                    |
| RF16 | Definir custos de procedimentos  | O sistema deve permitir associar custos (materiais, mão de obra, etc.).  |
| RF17 | Cadastrar equipamento            | O sistema deve permitir cadastrar equipamentos da clínica.               |
| RF18 | Editar equipamento               | O sistema deve permitir editar equipamentos cadastrados.                 |
| RF19 | Remover equipamento              | O sistema deve permitir excluir equipamentos.                            |
| RF20 | Dashboard                        | O sistema deve apresentar um painel com indicadores operacionais.        |
| RF21 | Cadastrar clínicas               | O sistema deve permitir o cadastro de múltiplas clínicas/unidades.       |
| RF22 | Cadastrar local de trabalho      | O sistema deve permitir cadastrar diferentes locais de atendimento.      |
| RF23 | Cadastrar redes sociais          | O sistema deve permitir registrar links de redes sociais.                |
| RF24 | Integração com Google Agenda     | O sistema deve integrar com Google Agenda para sincronização de eventos. |

---

## 3. Requisitos Não Funcionais (RNF)

| ID    | Categoria          | Descrição                                                                     |
| ----- | ------------------ | ----------------------------------------------------------------------------- |
| RNF01 | Usabilidade        | O sistema deve possuir interface intuitiva e de fácil utilização.             |
| RNF02 | Desempenho         | O sistema deve responder às requisições em até 2 segundos.                    |
| RNF03 | Segurança          | O sistema deve garantir proteção de dados conforme LGPD.                      |
| RNF04 | Segurança          | O sistema deve implementar autenticação e controle de acesso por perfil.      |
| RNF05 | Disponibilidade    | O sistema deve ter disponibilidade mínima de 99% mensal.                      |
| RNF06 | Escalabilidade     | O sistema deve suportar crescimento no número de usuários e dados.            |
| RNF07 | Compatibilidade    | O sistema deve ser responsivo (desktop, tablet e mobile).                     |
| RNF08 | Integridade        | O sistema deve garantir consistência e integridade dos dados.                 |
| RNF09 | Manutenibilidade   | O sistema deve possuir arquitetura modular para facilitar manutenção.         |
| RNF10 | Interoperabilidade | O sistema deve suportar integração com serviços externos (ex: Google Agenda). |
| RNF11 | Armazenamento      | O sistema deve suportar armazenamento seguro de arquivos (imagens).           |

---

## 4. Observações

Os requisitos podem evoluir conforme validação com stakeholders.

