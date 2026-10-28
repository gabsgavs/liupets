# 🐾 Liu Pets - Sistema de Agendamento Web

Projeto desenvolvido como Atividade Prática Profissional (Estágio Supervisionado) para o curso de **Análise e Desenvolvimento de Sistemas** da **Multivix**.

## 📌 Sobre o Projeto
Uma aplicação Web responsiva e intuitiva para agendamento de serviços de estética animal. O sistema foi projetado para eliminar gargalos de atendimento via WhatsApp, permitindo que o cliente solicite horários de forma estruturada. 

## 🚀 Tecnologias e Arquitetura
Conforme as exigências do manual da instituição (Aplicações Web), o projeto foi desenvolvido com foco exclusivo no Front-end, visando alta disponibilidade e baixa manutenção:
* **HTML5:** Estruturação semântica do formulário em etapas (Progressive Disclosure).
* **CSS3 (Bootstrap 5):** Estilização, responsividade mobile-first e componentes visuais (Cards, Modals).
* **JavaScript (ES6):** Lógica de interface, validação de regras de negócio (dias úteis), armazenamento de dados via `localStorage` (simulando persistência de banco de dados) e integração nativa com a API de links do WhatsApp.

## ⚙️ Funcionalidades
* **Interface do Cliente:** Formulário inteligente que memoriza os dados do usuário (Tutor e Pet) para agilizar agendamentos futuros, enviando a solicitação formatada direto para o WhatsApp da empresa.
* **Painel Administrativo:** Dashboard restrito para a gestão do petshop, com visualização da agenda do dia em cartões (Cards), alteração de status (Cancelamento) e consulta de histórico de visitas por animal.

## 🔗 Acesso ao Sistema
O projeto está hospedado no GitHub Pages.
* **Tela do Cliente:** https://gabsgavs.github.io/liupets/