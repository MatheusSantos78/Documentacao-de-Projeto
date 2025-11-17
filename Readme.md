Descrição Geral da Documentação do Projeto: Sistema de Moeda Estudantil

Este documento detalha a modelagem e os modelos de projeto para o Sistema de Moeda Estudantil, uma plataforma digital inovadora. O objetivo central do sistema é reconhecer e incentivar o mérito estudantil por meio de uma moeda virtual, que é concedida por professores e utilizada pelos alunos para adquirir vantagens e produtos oferecidos por empresas parceiras.

1. Fundamentos e Requisitos do Sistema

A documentação estabelece a base do sistema através da identificação de quatro perfis de usuários primários: Professor, Aluno, Parceiro Comercial e Administrador. Os requisitos funcionais são rigorosamente definidos por meio de Casos de Uso (como o Envio de Moedas, o Resgate de Vantagens e a Validação de Cupons) e formalizados em Contratos de Operação que especificam as condições de sucesso e as regras de negócio para as interações críticas.

2. Estrutura e Comportamento do Projeto

O projeto é estruturado sob o padrão arquitetural Model-View-Controller (MVC), o que assegura uma clara separação de responsabilidades entre a lógica de negócios, a interface e o controle de fluxo.

•
Componentes e Distribuição: A solução é implementada com um Frontend (React/TypeScript) para a camada de apresentação e um Backend (Node.js/TypeScript) que expõe a API. A persistência é gerenciada por um Banco de Dados PostgreSQL e o sistema se integra a um Serviço de E-mail para notificações. O Diagrama de Componentes ilustra a interação entre esses módulos.

•
Modelagem Estática: O Diagrama de Classes, derivado do schema.prisma, define a estrutura de dados do domínio, incluindo as entidades centrais como User, Account, Reward (Vantagem) e Redemption (Cupom de Resgate).

•
Modelagem Dinâmica: O comportamento do sistema é detalhado por Diagramas de Sequência para os principais fluxos de trabalho. Além disso, o ciclo de vida do objeto Redemption é modelado por um Diagrama de Estados, que transiciona entre os estados GERADO, UTILIZADO e EXPIRADO.

3. Persistência e Integridade dos Dados

O modelo de dados é gerenciado pelo Prisma ORM, que facilita o Mapeamento Objeto-Relacional (O/R) para o banco de dados PostgreSQL. Essa abordagem garante a integridade e a consistência dos dados, sendo o Diagrama de Classes a representação visual desse esquema relacional.

Em conclusão, a documentação fornece uma visão completa, abrangendo desde a especificação dos requisitos funcionais e a definição da arquitetura técnica até a modelagem detalhada do comportamento e da persistência, servindo como o principal artefato para o desenvolvimento e a manutenção do Sistema de Moeda Estudantil.

