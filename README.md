#Requisitos Funcionais para o sistema de uma clínica 

RU1 - Quero cadastrar os médicos
RF1 - O sistema deve possibilitar o cadastro de médicos com os seguintes dados: Nome completo, crm, especialidade, disponibilidade e cpf

RU2 – Quero cadastrar os pacientes para registrar seus dados e histórico.
RF2 - O sistema deve possibilitar o cadastro de pacientes com os seguintes dados: Nome completo, data de nascimento, sexo, cpf econvênio

RU3 – Quero agendar consultas sem conflito de horários para organizar o atendimento.
RF3 – O sistema deve permitir o agendamento de consultas, associando médico, paciente, data e horário.

RU4 – Quero que cada funcionário tenha seu próprio usuário para segurança e controle de acesso.
RF4 – O sistema deve permitir que cada funcionário tenha um login e senha únicos para acesso ao sistema.

RU5 – Quero poder cancelar ou remarcar consultas para flexibilidade no atendimento.
RF5 – O sistema deve permitir o cancelamento e a remarcação de consultas com atualização automática da agenda.

RU7 – Quero que o sistema valide os dados cadastrados para evitar erros.
RF7 – O sistema deve permitir o cadastro, edição e exclusão dos convênios médicos aceitos pela clínica.

RU8 – Quero que o sistema registre automaticamente todas as consultas realizadas para garantir a atualização do histórico.
RF8 – O sistema deve armazenar e permitir a consulta do histórico de consultas realizadas para cada paciente.

RU8 – Quero gerar relatórios mensais de consultas para análise do desempenho da clínica.
RF8 – O sistema deve gerar relatórios mensais de consultas realizadas, separados por médico e convênio.

RU9 – Quero controlar os convênios médicos aceitos para facilitar o faturamento.
RF9- O sistema deve gerar relatórios de faturamento agrupados por convênio para facilitar a análise financeira.

RU10 – Quero receber notificações de consultas agendadas para melhor organização do dia a dia.
RF10 – O sistema deve enviar notificações automáticas para pacientes e médicos sobre consultas agendadas ou alteradas.

#Requisitos não funcionais para o sistema de uma clínica

RNF1 – O sistema deve possuir uma interface intuitiva e fácil de usar, permitindo que funcionários com diferentes níveis de experiência consigam operar sem dificuldades.

RNF2 – O sistema deve garantir a segurança dos dados pessoais e médicos, implementando autenticação com login e senha, além de criptografia para armazenar informações sensíveis, como CPF e histórico médico.

RNF3 – O sistema deve estar disponível para uso pelo menos 99% do tempo durante o horário comercial da clínica, garantindo que agendamentos e consultas possam ser realizados sem interrupções.

RNF4 – O sistema deve responder às operações de cadastro, consulta e agendamento em no máximo 3 segundos, mesmo com grande volume de dados.

RNF5 – O sistema deve realizar backups automáticos diários dos dados armazenados para garantir a recuperação rápida em caso de falhas ou perdas de dados.

#Requisitos de software

RS1 - O sistema deve funcionar em Windows, Linux e MacOS.
RS2 - O sistema deve ser acessível pela internet, via navegador web.
RS3 - O sismeta deve funcionar em dispositivos móveis.
RS4 - A interface deve se redimensionar automaticamente para diferentes tamanhos de tela.
RS5 - O sistema deve ter instalações simples e rápida.
