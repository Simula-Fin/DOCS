# Introdução

&emsp;&emsp;O plano de custos delineia a estratégia para planejar, estruturar e monitorar os custos do projeto, fornecendo uma visão detalhada dos processos e ferramentas a serem utilizados. A primeira fase envolve a estimativa de custos, que visa calcular o custo dos recursos necessários para a execução do projeto. Em seguida, é estabelecido o orçamento, que consolida todas as estimativas de custos. Por fim, são implementados controles para monitorar e, se necessário, ajustar o orçamento ao longo do projeto.

Este documento oferece uma visão abrangente das etapas de estimativa de custos, orçamentação e controle, permitindo a execução do projeto dentro do orçamento planejado.

## Estimativa de custos

### Pessoas

Para a estimativa de custos, utilizamos o custo médio anual por aluno de um instituto federal, conforme relatado pelo jornal da Unesp, que é de R$40.900 por aluno ao ano. Considerando o curso da equipe, Engenharia de Software, que tem a duração de 5 anos e é composto por 232 créditos, além das 12 semanas de duração do projeto e os 5 membros da equipe, realizamos os seguintes cálculos:

- Custo médio por crédito * custo médio anual por integrante x número padrão de anos do curso ÷ número de créditos necessários para conclusão do curso * 40.900 x 5 ÷ 232 = R$881,50
- Custo médio por integrante da equipe * custo médio por crédito x quantidade de créditos da disciplina * 881,5 x 4 = R$3.526,00
- Custo TOTAL por equipe * custo médio por integrante x número de membros da equipe * 3526,00 x 5 = R$17.630,00
- Custo médio semanal por equipe * custo TOTAL por equipe ÷ número de semanas do projeto * 17.630,00 ÷ 12 = R$1.469,17

### Equipamentos

Para a estimativa de custos dos equipamento será considerado o preço de um notebook com as configurações mínimas de um Intel Core I5 de pelo menos décim geração ou AMD Ryzen 5 pelo menos da geração 5000 com 8gb de memória RAM em 2024. Segundo o site Mercado Livre, o preço de um notebook com essas características está em torno de R$ 3 mil. Considerando os 5 integrantes da equipe:

Custo TOTAL dos equipamentos = custo médio do notebook x quantidade de integrantes da equipe * 3.000 x 5 = R$15.000,00

### Ferramentas

&emsp;&emsp;Para a estimativa de custos relacionados às ferramentas, consideraremos R$0, pois a equipe utiliza plataformas e ferramentas gratuitas.

### Capacitação

&emsp;&emsp;Os custos relacionados à capacitação serão estimados como R$0, uma vez que a equipe utiliza recursos de aprendizado gratuitos.

### Infraestrutura

&emsp;&emsp;Na avaliação dos custos de infraestrutura, contemplamos o consumo de energia elétrica e o acesso à internet.

#### Internet

&emsp;&emsp;Para calcular o custo da internet, utilizaremos o preço médio de planos de 250 MB por mês, que é aproximadamente R$89,99, conforme dados de melhorescolha.

- Custo semanal de internet por integrante * custo mensal da internet ÷ número de semanas no mês * R$89,99 ÷ 4 = R$22,50
- Custo semanal de internet por equipe * custo semanal da internet por integrante x número de integrantes * R$22,50 x 5 = R$112,50
- Custo TOTAL de internet por equipe * custo semanal da internet por equipe x número de semanas do projeto * R$112,50 x 12 = R$1.350,00

#### Energia

&emsp;&emsp;Para estimar o custo da energia elétrica, utilizamos os dados da tabela de tarifas da neoenergiabrasilia, considerando o custo do KW/h residencial, que é cerca de R$0,70, conforme dados de novembro de 2022 a abril de 2024. Segundo informações da cultura uol de 2021, um notebook consome em média cerca de 65W/h, conectado ao carregador. Supomos que cada membro da equipe trabalhe 4 horas por semana em sua residência, ao longo de 12 semanas. Com base nesses dados, temos:

- Consumo do notebook em KW/h: * potência x horas ÷ 1000
    - 65 x 1 ÷ 1000 = 0,065* KW/h

- Custo semanal de energia por integrante =
horas de trabalho x consumo do notebook x tarifa
    - 4h x x 0,065KW/h x R$0,70
    - 4 x 0,065 x R$0,70 = R$0,18
- Custo semanal de energia por equipe * custo semanal por integrante x número de integrantes da equipe 
    - R$0,18 x 5 = R$0,90
- Custo TOTAL de energia por equipe * custo semanal por equipe x número de semanas do projeto 
    - R$0,90 x 12 = R$10,80

#### Custo TOTAL de infraestrutura

&emsp;&emsp;Ao somar as estimativas de custo semanal de internet (R$90,00) e energia (R$0,72) por equipe, obtemos um custo semanal de infraestrutura de R$340,20. Considerando as 12 semanas de projeto, o custo total de infraestrutura será de R$5.171,04.

### Vales

&emsp;&emsp;Considerando os custos de transporte e alimentação associados à participação na disciplina e ao desenvolvimento do projeto, adotamos os seguintes valores: duas passagens de R$5,50 por dia de aula e R$6,10 destinados ao almoço no restaurante universitário da UnB. Portanto, os custos são os seguintes:

- Custo semanal de vale transporte * custo do transporte X quantidade de viagens por dia X quantidade de aulas por semana X quantidade de alunos 
    - R$((5,50 * 2) * 2) * 5 = R$110,00
- Custo semanal de vale alimentação * custo do almoço X quantidade de aulas por semana X quantidade de alunos 
    - R$(6,10 * 2) * 5 = R$61,00
- Custo total semanal com vales pela equipe * Custo semanal de vale transporte + Custo semanal de vale alimentação 
    - R$110,00 + R$61,00 = R$171,00
- Custo total com vales pela equipe * Custo total semanal com vales X quantidade de alunos 
    - R$171,00 * 5 = R$855,00

## Definição do orçamento

- Considerando as estimativas de custos acima calculadas e uma margem de 10%, o orçamento total para o projeto em 12 semanas é:
custo pessoas + custo equipamentos + custo ferramentas + custo capacitação + custo infraestrutura + custo vales
    - R$19.393,00 + R$16.500,00 + R$0 + R$0 + R$5.688,14 + R$940,50 = R$42.521,64
- O custo do MVP é calculado com base nas semanas até sua entrega, calculado para X semanas. Portanto, o custo do MVP é de R$X.

## Histórico de versão

| Data | Versão | Descrição | Autor(es) |
| ---- | ------ | --------- | --------- |
| 18/04/2024 | 1.0 | Criação do documento do plano de custo | João Henrique |
