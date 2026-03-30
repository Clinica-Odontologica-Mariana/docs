# 👥 User Stories (Histórias de Usuário)

Este documento traduz os requisitos técnicos em necessidades dos usuários, focando no valor entregue em cada funcionalidade.

## 🦷 Épico 1: Gestão de Pacientes e Prontuários
*Relacionado a: RF01, RF02, RF03, RF04, RF05, RF06, RF07*

| ID | User Story | Critérios de Aceitação |
| :--- | :--- | :--- |
| **US01** | **Como** recepcionista, **quero** cadastrar novos pacientes **para que** eu possa iniciar o fluxo de atendimento. | Campos obrigatórios: Nome, CPF, Telefone. Validar duplicidade de CPF. |
| **US02** | **Como** dentista, **quero** criar e atualizar prontuários **para que** eu tenha o histórico clínico completo de cada paciente. | O prontuário deve estar vinculado ao ID do paciente. Permitir edição de campos de texto livre. |
| **US03** | **Como** dentista, **quero** fazer upload de imagens no prontuário **para que** eu possa visualizar exames de imagem (Raio-X) durante a consulta. | Suporte para formatos PNG/JPG. |

---

## 📅 Épico 2: Agendamento e Calendário
*Relacionado a: RF08, RF09, RF10, RF11, RF12, RF27*

| ID | User Story | Critérios de Aceitação |
| :--- | :--- | :--- |
| **US04** | **Como** recepcionista, **quero** agendar consultas em horários disponíveis **para que** a agenda do consultório seja organizada. | Impedir agendamentos duplicados no mesmo horário/dentista. |
| **US05** | **Como** administrador, **quero** configurar o horário de funcionamento e bloquear datas **para que** pacientes não sejam agendados em feriados ou folgas. | Opção de bloqueio recorrente (ex: todo domingo). |
| **US06** | **Como** dentista, **quero** sincronizar a agenda do sistema com meu Google Agenda **para que** eu possa checar meus compromissos no celular. | Sincronização em tempo real (RNF10). |

---

## 💼 Épico 3: Administração e Serviços
*Relacionado a: RF13, RF14, RF15, RF16, RF17, RF18, RF19*

| ID | User Story | Critérios de Aceitação |
| :--- | :--- | :--- |
| **US07** | **Como** denstista, **quero** cadastrar tratamentos e seus respectivos custos **para que** o sistema calcule a rentabilidade dos procedimentos. | Incluir campos de custo fixo e variável (materiais). |
| **US08** | **Como** denstista, **quero** manter um inventário de equipamentos **para que** eu possa controlar o patrimônio da clínica. | Registro de nome, marca e data de aquisição. |

---

## 📊 Épico 4: Gestão Estratégica (BI) e Marketing
*Relacionado a: RF20, RF21, RF22, RF23, RF24, RF25, RF26*

| ID | User Story | Critérios de Aceitação |
| :--- | :--- | :--- |
| **US09** | **Como** administrador, **quero** visualizar um dashboard com indicadores operacionais **para que** eu acompanhe o desempenho financeiro e de atendimentos. | Gráficos de fácil leitura. Atualização rápida (RNF02). |
| **US10** | **Como** administrador, **quero** gerenciar múltiplas clínicas no mesmo sistema **para que** eu centralize a gestão da minha franquia. | Filtro por unidade/local de trabalho nas buscas. |
| **US11** | **Como** administrador, **quero** publicar posts no blog do sistema **para que** eu possa atrair novos pacientes via conteúdo educativo. | Editor de texto rico e upload de capa do post. |

---

## 🔐 Épico 5: Segurança e Infraestrutura
*Relacionado a: RNF03, RNF04, RNF07*

| ID | User Story | Critérios de Aceitação |
| :--- | :--- | :--- |
| **US12** | **Como** usuário do sistema, **quero** acessar a plataforma pelo celular ou tablet **para que** eu tenha mobilidade dentro da clínica. | Layout responsivo em todas as telas (RNF07). |
| **US13** | **Como** administrador, **quero** definir perfis de acesso (Recepcionista vs Dentista) **para que** cada colaborador acesse apenas o que é necessário. | Controle de permissões granular por rota/módulo. |