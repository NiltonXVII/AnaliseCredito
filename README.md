Projeto Análise de Crédito (Full-Stack)

Status: Em Desenvolvimento

Objetivo Principal

O objetivo é criar um sistema de análise de crédito instantânea, onde o usuário possa inserir dados (renda, idade, etc.) para calcular um score de crédito. A interface do frontend foi estilizada para simular a identidade visual do Banco do Brasil. O backend (em desenvolvimento) fornecerá a API para uma análise mais complexa e para salvar os dados do cliente.

Tecnologias Utilizadas

Frontend (lado do cliente)

HTML5: Estruturação semântica da página de análise.
CSS3: Estilização personalizada, incluindo o uso de variáveis CSS para o tema.
Bootstrap 5: Framework principal CSS para layout, componentes (modais, formulários) e responsividade.
Bootstrap Icons: Biblioteca de ícones.
JavaScript (ES6+): Manipulação de eventos e lógica do cálculo de score.
jQuery: Utilizado para simplificar a manipulação do DOM e validar formulários.

Backend (lado do servidor)

Node.js: Ambiente de execução para JavaScript no servidor.
Express.js: Framework para criação do servidor web e das rotas da API.
node-postgres (pg): Driver para a comunicação entre a aplicação Node.js e o banco de dados PostgreSQL.
CORS: Middleware para permitir que o frontend possa fazer requisições para a API.
PostgreSQL: Sistema de gerenciamento de banco de dados relacional.
