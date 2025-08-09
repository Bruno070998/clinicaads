# 📘 Documento de Requisitos - Sistema de Agendamento de Consultas

## 🎯 Objetivo

O objetivo deste projeto é automatizar o processo de agendamento de consultas em uma clínica médica, proporcionando maior agilidade, autonomia e facilidade para os pacientes. O sistema permitirá que os usuários criem suas próprias contas, agendem ou cancelem consultas e acompanhem seu histórico de atendimentos de forma prática e eficiente.

---

## 📌 Escopo do MVP

### ✅ Escopo IN (Incluso no MVP)

- Cadastro de usuários (pacientes, médicos e atendentes);
- Cadastro de pacientes;
- Visualização da disponibilidade de cada médico;
- Agendamento de consultas;
- Cancelamento de consultas com liberação imediata do horário;
- Validação de conflitos de horário, com exibição de mensagens de erro.

### ❌ Escopo OUT (Fora do MVP)

- Agendamento de consultas domiciliares;
- Comunicação via mensagens entre pacientes e médicos;
- Funcionalidades avançadas (serão consideradas em versões futuras):
  - Faturamento e integração com convênios;
  - Prontuário eletrônico;
  - Relatórios e dashboards analíticos.

---

## 📋 Regras de Negócio (RB)

- **RB01**: Consultas não podem ter conflitos de horário com outras já agendadas;
- **RB02**: Consultas devem ocorrer apenas dentro da janela de disponibilidade definida pelo médico;
- **RB03**: Cada consulta terá duração fixa de 30 minutos;
- **RB04**: Cancelamentos devem liberar o horário imediatamente para novos agendamentos.

---

## 🧱 Premissas

- O horário comercial padrão será das **08h às 18h**, com possibilidade de personalização por parte de cada profissional de saúde;
- O MVP será desenvolvido e implantado inicialmente para **apenas uma unidade/clínica**.

---

## 👥 Stakeholders

- **Pacientes** – Usuários finais do sistema, que realizarão agendamentos e acompanharão seus atendimentos;
- **Médicos** – Definirão suas janelas de disponibilidade e realizarão os atendimentos;
- **Atendentes** – Apoiarão os pacientes e médicos no uso do sistema e na gestão dos agendamentos;
- **Gestor da Clínica** – Responsável por acompanhar a performance da clínica e garantir o bom funcionamento do sistema.

---
