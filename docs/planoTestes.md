# Plano de Testes

## Introdução
Este plano de testes foi desenvolvido para garantir a qualidade e confiabilidade do software Simula-Fin, projetado na disciplina de Engenharia de Produto de Software da Universidade de Brasília. O Simula-Fin é uma aplicação que permite simular financiamentos, empréstimos e consórcios, oferecendo uma usabilidade fácil e um propósito diferenciado.

## Objetivos
Os objetivos deste plano de testes são:
- Verificar se as funcionalidades relacionadas à gestão de usuários, simulação de empréstimo, simulação de financiamento e simulação de consórcio estão implementadas corretamente, garantindo a integridade e o funcionamento adequado do sistema.
- Garantir que o software atenda aos critérios de aceitação estabelecidos para cada funcionalidade, assegurando que ele cumpra os requisitos e expectativas dos clientes de crédito.
- Identificar e corrigir possíveis defeitos no sistema, promovendo a confiabilidade e a estabilidade do software.
- Assegurar que o software seja seguro, confiável e de fácil utilização, proporcionando uma experiência satisfatória aos usuários e atendendo às necessidades específicas dos clientes de crédito.

## Escopo
O escopo deste plano de testes inclui:
- Testes de unidade para as funcionalidades mencionadas.
- Testes de integração entre as diferentes funcionalidades.
- Testes de sistema para verificar o comportamento do sistema como um todo.
- Testes de aceitação do usuário para validar se o software atende aos critérios estabelecidos.
- Análise estática de código utilizando o SonarCloud para identificar issues e security hotspots no código fonte. O SonarCloud ajuda a garantir que o código seja confiável, mantível e seguro, identificando problemas que requerem correção e áreas potencialmente vulneráveis que precisam ser revisadas. Ele se integra ao fluxo de trabalho de integração contínua/desenvolvimento contínuo (CI/CD) para intervir precocemente durante o desenvolvimento, permitindo que problemas sejam corrigidos rapidamente e evitando que cheguem à produção. O SonarCloud fornece feedback diretamente no ambiente de desenvolvimento (IDE), em solicitações de pull (pull requests) e no próprio código fonte, facilitando a correção de problemas antes que se tornem críticos.

## Abordagem de Teste
A abordagem de teste seguirá as seguintes etapas:
1. Identificação dos requisitos de teste com base nos critérios de aceitação estabelecidos na planilha de especificações.
2. Criação de casos de teste para cada funcionalidade, cobrindo diferentes cenários de uso.
3. Execução dos casos de teste para verificar o comportamento do sistema.
4. Utilização do SonarCloud para análise estática de código, identificando issues e security hotspots no código fonte.
5. Relato e acompanhamento de defeitos encontrados durante os testes.
6. Revisão e validação dos resultados dos testes em relação aos critérios de aceitação.

## Recursos Necessários
Os seguintes recursos serão necessários para a execução dos testes:
- Ambiente de desenvolvimento e teste.
- Ferramentas de teste, SonarCloud até o momento.
- Acesso à planilha de critérios de aceitação para referência durante os testes.
- Equipe de testes para execução e validação dos casos de teste.

  ## Histórico de versão

| Data | Versão | Descrição | Autor(es) |
| ---- | ------ | --------- | --------- |
| 07/05/2024 | 1.0 | Criação do documento do plano de testes | Eurico Neto |
