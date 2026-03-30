# User Stories (Histórias de Usuário)

Este documento traduz os requisitos técnicos em necessidades dos usuários, focando no valor entregue em cada funcionalidade.


## Épico 1: Gestão de Pacientes e Prontuários

*Relacionado a: RF01, RF02, RF03, RF04, RF05, RF06, RF07*

| ID       | User Story                                                                                                                                                                                  | Critérios de Aceitação                                                                                                |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------- |
| **US01** | **Como** recepcionista, **quero** gerenciar o cadastro de pacientes (criar, editar, consultar e remover) **para que** eu mantenha a base de pacientes atualizada e pronta para atendimento. | Campos obrigatórios: Nome, CPF, Telefone. Validar duplicidade de CPF. Permitir edição e exclusão com confirmação.     |
| **US02** | **Como** dentista, **quero** gerenciar prontuários dos pacientes **para que** eu tenha acesso ao histórico clínico completo e atualizado.                                                   | Prontuário vinculado ao paciente. Permitir criação, edição e consulta. Registrar data e responsável pelas alterações. |
| **US03** | **Como** dentista, **quero** gerenciar imagens no prontuário **para que** eu possa visualizar exames e registros visuais durante o atendimento.                                             | Upload de imagens (PNG/JPG). Associação ao prontuário correto. Permitir visualização e exclusão.                      |



## Épico 2: Agendamento e Calendário

*Relacionado a: RF08, RF09, RF10, RF11, RF12, RF27*

| ID       | User Story                                                                                                                                     | Critérios de Aceitação                                                                                                |
| :------- | :--------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------- |
| **US04** | **Como** recepcionista, **quero** gerenciar agendamentos de consultas **para que** a agenda da clínica seja organizada e eficiente.            | Criar, editar e cancelar agendamentos. Impedir conflitos de horário por profissional. Atualização imediata da agenda. |
| **US05** | **Como** administrador, **quero** gerenciar os horários de funcionamento **para que** os agendamentos respeitem a disponibilidade da clínica.  | Definir dias/horários. Bloquear agendamento fora do período. Permitir alterações futuras.                             |
| **US06** | **Como** administrador, **quero** gerenciar bloqueios de agenda **para que** horários indisponíveis não sejam utilizados.                      | Cadastro de bloqueios por período e motivo. Impedir agendamentos nesses horários. Exibição visual na agenda.          |
| **US07** | **Como** profissional da clínica, **quero** sincronizar a agenda com o Google Agenda **para que** eu acompanhe meus compromissos externamente. | Autenticação com conta Google. Sincronização de criação, edição e cancelamento de eventos. Registro de falhas.        |



## Épico 3: Administração e Serviços

*Relacionado a: RF13, RF14, RF15, RF16, RF17, RF18, RF19*

| ID       | User Story                                                                                                                        | Critérios de Aceitação                                                                                  |
| :------- | :-------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------ |
| **US08** | **Como** administrador, **quero** gerenciar tratamentos e serviços **para que** a clínica mantenha seu portfólio atualizado.      | Cadastro com nome, descrição e categoria. Permitir edição e exclusão. Validação de campos obrigatórios. |
| **US09** | **Como** administrador, **quero** gerenciar custos dos procedimentos **para que** eu possa analisar a rentabilidade dos serviços. | Associar custos a procedimentos. Categorizar (material, mão de obra, etc.). Permitir edição e remoção.  |
| **US10** | **Como** administrador, **quero** gerenciar equipamentos da clínica **para que** eu controle os recursos disponíveis.             | Cadastro com nome, descrição e localização. Permitir edição e exclusão com restrições.                  |



## Épico 4: Estrutura Organizacional

*Relacionado a: RF24, RF25*

| ID       | User Story                                                                                                                             | Critérios de Aceitação                                                         |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------- |
| **US11** | **Como** administrador, **quero** gerenciar clínicas e unidades **para que** eu organize o sistema em múltiplos locais de atendimento. | Cadastro de clínicas. Permitir edição e remoção. Suporte a múltiplas unidades. |
| **US12** | **Como** administrador, **quero** gerenciar localizações de trabalho **para que** eu organize salas e ambientes de atendimento.        | Associação com clínica. Uso em agendamentos. Permitir CRUD completo.           |




## Épico 5: Gestão Estratégica e Marketing

*Relacionado a: RF20, RF21, RF22, RF23, RF26*

| ID       | User Story                                                                                                                    | Critérios de Aceitação                                                              |
| :------- | :---------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------- |
| **US13** | **Como** administrador, **quero** visualizar um dashboard com indicadores **para que** eu acompanhe o desempenho da clínica.  | Exibir métricas operacionais. Atualização dinâmica. Visualização clara (gráficos).  |
| **US14** | **Como** responsável pelo marketing, **quero** gerenciar posts do blog **para que** eu publique conteúdos e atraia pacientes. | Criar, editar e excluir posts. Suporte a rascunho/publicação. Editor de texto rico. |
| **US15** | **Como** administrador, **quero** gerenciar links de redes sociais **para que** os pacientes acessem nossos canais digitais.  | Cadastro de URLs válidas. Permitir edição e exclusão.                               |



## Épico 6: Segurança, Acesso e Plataforma

*Relacionado a: RNF01, RNF03, RNF04, RNF07*

| ID       | User Story                                                                                                                                 | Critérios de Aceitação                                                           |
| :------- | :----------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| **US16** | **Como** usuário do sistema, **quero** acessar a plataforma em diferentes dispositivos **para que** eu tenha mobilidade no uso do sistema. | Interface responsiva (desktop, tablet e mobile).                                 |
| **US17** | **Como** administrador, **quero** gerenciar perfis de acesso **para que** cada usuário tenha permissões adequadas.                         | Controle por perfil (recepcionista, dentista, admin). Restrição por módulo/ação. |
