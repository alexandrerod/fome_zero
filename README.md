
# 1. Problema de negócio

A empresa Fome Zero é uma marketplace de restaurantes. Ou seja, seu core business é facilitar o encontro e negociações de clientes e restaurantes. 
Os restaurantes fazem o cadastro dentro da plataforma da Fome Zero, que disponibiliza informações como endereço, tipo de culinária servida, se possui reservas, se faz entregas e também uma nota de avaliação dos serviços e produtos do restaurante, dentre outras informações.

Você acaba de ser contratado como Cientista de Dados da empresa Fome Zero, e a sua principal tarefa nesse momento é ajudar o CEO Kleiton Guerra
a identificar pontos chaves da empresa, respondendo às perguntas que ele fizer utilizando dados! 

O CEO Guerra também foi recém contratado e precisa entender melhor o negócio para conseguir tomar as melhores decisões estratégicas e alavancar ainda mais a Fome Zero, e para isso, ele precisa que seja feita uma análise nos dados da empresa de forma a responder as seguintes perguntas:

## Visão Geral:
    1. Quantos restaurantes únicos estão registrados?
    2. Quantos países únicos estão registrados?
    3. Quantas cidades únicas estão registradas?
    4. Qual o total de avaliações feitas?
    5. Qual o total de tipos de culinária registrados?

    
## Visão por País:
    1. Qual o nome do país que possui mais cidades registradas?
    2. Qual o nome do país que possui mais restaurantes registrados?
    3. Qual o nome do país que possui mais restaurantes com o nível de preço igual a 4
    registrados?
    4. Qual o nome do país que possui a maior quantidade de tipos de culinária
    distintos?
    5. Qual o nome do país que possui a maior quantidade de avaliações feitas?
    6. Qual o nome do país que possui a maior quantidade de restaurantes que fazem
    entrega?
    7. Qual o nome do país que possui a maior quantidade de restaurantes que aceitam
    reservas?
    8. Qual o nome do país que possui, na média, a maior quantidade de avaliações
    registrada?
    9. Qual o nome do país que possui, na média, a maior nota média registrada?
    10. Qual o nome do país que possui, na média, a menor nota média registrada?
    11. Qual a média de preço de um prato para dois por país?

    
## Visão por Cidade:
    1. Qual o nome da cidade que possui mais restaurantes registrados?
    2. Qual o nome da cidade que possui mais restaurantes com nota média acima de
    4?
    3. Qual o nome da cidade que possui mais restaurantes com nota média abaixo de
    2.5?
    4. Qual o nome da cidade que possui o maior valor médio de um prato para dois?5. Qual o nome da cidade que possui a maior quantidade de tipos de    culinária
    distintas?
    6. Qual o nome da cidade que possui a maior quantidade de restaurantes que fazem
    reservas?
    7. Qual o nome da cidade que possui a maior quantidade de restaurantes que fazem
    entregas?
    8. Qual o nome da cidade que possui a maior quantidade de restaurantes que
    aceitam pedidos online?
## Visão por Restaurante:
    1. Qual o nome do restaurante que possui a maior quantidade de avaliações?
    2. Qual o nome do restaurante com a maior nota média?
    3. Qual o nome do restaurante que possui o maior valor de uma prato para duas
    pessoas?
    4. Qual o nome do restaurante de tipo de culinária brasileira que possui a menor
    média de avaliação?
    5. Qual o nome do restaurante de tipo de culinária brasileira, e que é do Brasil, que
    possui a maior média de avaliação?
    6. Os restaurantes que aceitam pedido online são também, na média, os
    restaurantes que mais possuem avaliações registradas?
    7. Os restaurantes que fazem reservas são também, na média, os restaurantes que
    possuem o maior valor médio de um prato para duas pessoas?
    8. Os restaurantes do tipo de culinária japonesa dos Estados Unidos da América
    possuem um valor médio de prato para duas pessoas maior que as churrascarias
    americanas (BBQ)?
    
## Visão por Tipo de Culinária

    1. Dos restaurantes que possuem o tipo de culinária italiana, qual o nome do
    restaurante com a maior média de avaliação?
    2. Dos restaurantes que possuem o tipo de culinária italiana, qual o nome do
    restaurante com a menor média de avaliação?
    3. Dos restaurantes que possuem o tipo de culinária americana, qual o nome do
    restaurante com a maior média de avaliação?
    4. Dos restaurantes que possuem o tipo de culinária americana, qual o nome do
    restaurante com a menor média de avaliação?
    5. Dos restaurantes que possuem o tipo de culinária árabe, qual o nome do
    restaurante com a maior média de avaliação?
    6. Dos restaurantes que possuem o tipo de culinária árabe, qual o nome do
    restaurante com a menor média de avaliação?
    7. Dos restaurantes que possuem o tipo de culinária japonesa, qual o nome do
    restaurante com a maior média de avaliação?
    8. Dos restaurantes que possuem o tipo de culinária japonesa, qual o nome do
    restaurante com a menor média de avaliação?
    9. Dos restaurantes que possuem o tipo de culinária caseira, qual o nome do
    restaurante com a maior média de avaliação?
    10. Dos restaurantes que possuem o tipo de culinária caseira, qual o nome do
    restaurante com a menor média de avaliação?
    11. Qual o tipo de culinária que possui o maior valor médio de um prato para duas
    pessoas?
    12. Qual o tipo de culinária que possui a maior nota média?
    13. Qual o tipo de culinária que possui mais restaurantes que aceitam pedidos
    online e fazem entregas?


O objetivo desse projeto é criar um conjunto dashboard que exibam asmétricas solicitadas pelo CEO da melhor forma possível.
# 2. Premissas assumidas para a análise

    1. Marketplace foi o modelo de negócio assumido.
    2. As 3 principais visões do negócio desenvolvidas foram: Visão dos restaurantes por Paises, Visão dos restaurantes por Cidades e Visão dos restaurantes por tipos de Culinária.

# 3. Estratégia da solução

Cada visão é representada pelo seguinte conjunto de métricas.

    1. Visão dos restaurantes por País
        1. Quantidade de restaurante registrados por país.
        2. Quantidade de cidades registradas por país.
        3. Média de avaliações feitas por país.
        4. Média de preço de um prato para duas pessoas.
    

    2. Visão dos restaurantes por Cidades
       1. Cidades com mais restaurantes cadastrados na base de dados.
       2. Cidades com média de avaliação acima de 4.
       3. Cidades com média de avaliação menor que 2,5.
       4. Cidades com mais restaurantes contendo tipos de culinárias distintos.


    3. Visão dos restaurantes por tipo de culinária
       1. Melhores restaurantes dos principais tipos de culinária.
       2. Melhores restaurantes.
       3. Melhores restaurantes por tipo de culinária.
       4. Piores restaurantes por tipo de culinária.
      

# 5. O produto final do projeto

Painel online, hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet.

O painel pode ser acessado através desse link: https://alexandrerod-project-cury-company.streamlit.app/
# 6. Conclusão

O objetivo desse projeto é criar um conjunto de gráficos e/ou tabelas que exibam essas métricas da melhor forma possível para o CEO.

Da visão da Empresa, podemos concluir que o número de pedidos cresceu entre a semana 06 e a semana 13 do ano de 2022.
# 7. Próximo passos

    - Reduzir o número de métricas.
    - Criar novos filtros.
    - Adicionar novas visões de negócio.
