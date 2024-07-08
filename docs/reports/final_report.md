# Funcionalidades desenvolvidas no decorrer do projeto

- Microserviço de CRUD e simulações:
    - Simulação de empréstimo;
    - Simulação de consórcio;
    - Simulação de financiamento;
    - CRUD de usuário
- Microserviço de empréstimo P2P:
    - Lógica do back e front que fazem os emprestimos acontecerem;

## Relato da Experiência de Consumo de Microsserviços
&emsp;&emsp;No decorrer do projeto, utilizamos dois microsserviços desenvolvidos por outros grupos, o que se mostrou uma experiência valiosa, apesar de alguns desafios enfrentados.

**Microserviço de Dados de Ações (Stock Compass)**

&emsp;&emsp;O primeiro microsserviço consumido foi o de dados de ações, fornecido pelo grupo Stock Compass. Essa integração nos permitiu acessar informações cruciais sobre o mercado financeiro, enriquecendo as funcionalidades da nossa aplicação.

- Desafios:

    - Deploy no Vercel: Inicialmente, tivemos dificuldades para realizar o deploy do microsserviço no ambiente Vercel.
    - Falta de tempo em decorrência de outras matérias.
- Beneficios
    - Facilidade de Integração: A utilização de um microsserviço dedicado nos poupou tempo e esforço, pois não precisamos desenvolver toda a lógica de coleta e tratamento dos dados de ações.
    - Qualidade dos Dados: O microsserviço forneceu dados precisos e atualizados, o que agregou valor à nossa aplicação.

**Microserviço de Criptografia (CryptoBot)**

&emsp;&emsp;O segundo microsserviço consumido foi o de criptografia RSA, desenvolvido pelo grupo CryptoBot. Essa funcionalidade nos permitiu adicionar uma camada extra de segurança à nossa aplicação, protegendo dados sensíveis dos usuários.

- Desafios:
    - Deploy no Vercel: Inicialmente, tivemos dificuldades para realizar o deploy do microsserviço no ambiente Vercel.
    - Falta de tempo em decorrência de outras matérias.
- Benefícios:
    - Segurança Reforçada: A criptografia dos dados garantiu a confidencialidade das informações, protegendo-as de acessos não autorizados.

**Microserviço de Chatbot(PixIt)**

&emsp;&emsp;O terceiro microsserviço consumido foi o de chatbot, desenvolvido pelo aluno do PixIt. Conseguimos adicionar um chatbot para que os usuários do simula-fin pudessem tirar dúvidas sobre ações e investimentos. Esse microsserviço foi tranquilo de ser consumido pelo fato do aluno responsável pela funcionalidade nos fornecer todo apoio na hora de consumir, chaves de api etc.    

**Conclusão**

&emsp;&emsp;Em suma, a experiência de consumo de microsserviços foi positiva, apesar dos desafios enfrentados. A utilização desses serviços nos permitiu acelerar o desenvolvimento da nossa aplicação, adicionar funcionalidades valiosas e garantir a qualidade e segurança dos dados.
&emsp;&emsp;É importante ressaltar que a colaboração entre os grupos foi fundamental para o sucesso da integração, e que a melhoria contínua da documentação e da performance dos microsserviços pode otimizar ainda mais a experiência de consumo.

## Descrição das atividades realizadas no desafio Sebrae

- Primeiramente todos os integrantes criaram sua  conta;
- Entramos na nossa equipe e adicionamos o professor Ricardo Chaim como orientador;
- Vimos todas as aulas pedidas no desafio, e sempre ao menos um integrante assinava a lista de presença, que era necessária para continuar no desafio;
- Ao terminarmos as nossas funcionalidades, criamos o vídeo do pitch como pedido no desafio SEBRAE, seguindo todas as suas orientações;
    - Adicionamos o vídeo dias antes do prazo final que era dia 24/06/2024;
    - Vídeo está disponível no seguinte link: [Pitch do grupo Simula-Fin](https://www.youtube.com/watch?v=CMIlVEfxVMw);
    - Pdf do slide utilizado está disponível em: [PDF da apresentação do grupo Simula-Fin](../assets/Pitch/PitchSimulaFin.pdf);
    - Link da aplicação disponível em: [Deploy do grupo Simula-Fin](https://frontend-indol-pi.vercel.app/);

## Experiência da gestão da equipe

&emsp;&emsp;No início do projeto, a equipe enfrentou um período de adaptação para compreender os requisitos e objetivos da disciplina. No entanto, após o alinhamento inicial, conseguimos estabelecer um fluxo de trabalho eficiente, utilizando o [Trello](https://trello.com/b/Pm8a7sy8/eps-simulafin) para organizar e acompanhar as tarefas

&emsp;&emsp;As reuniões semanais, realizadas principalmente pelo Discord ou de forma assíncrona pelo WhatsApp, foram essenciais para manter a comunicação e o alinhamento da equipe. Durante o desenvolvimento, alguns integrantes enfrentaram dificuldades para conciliar o projeto com outras atividades acadêmicas, como o TCC. No entanto, essa situação já havia sido prevista no nosso plano de riscos, e conseguimos contorná-la com sucesso, redistribuindo tarefas e ajustando prazos, e no fim todos conseguiram ajudar de forma satisfatória no projeto.

&emsp;&emsp;Apesar dos desafios, a experiência de gestão da equipe e do escopo foi extremamente satisfatória e enriquecedora. Aprendemos a trabalhar em equipe de forma colaborativa, a lidar com imprevistos e a gerenciar o tempo de forma eficiente. A comunicação aberta e transparente, aliada à flexibilidade e ao comprometimento de todos os integrantes, foram fatores cruciais para o sucesso do projeto.

## Trabalhos futuros

Para trabalhos futuros, há áreas de evolução na rede de empréstimos p2p.

- Interessante adicionar lógica de vários investidores aportando dinheiro para um mesmo tomador de empréstimo.
- Adicionar melhor validação de quem pode investir ou solicitar empréstimos.
- Melhor tela dos admnistradores da rede p2p, adicionado dados importantes de se observar dos empreéstimos.
- Integrar via pix, os pagamentos e recebimentos da rede de empréstimos.