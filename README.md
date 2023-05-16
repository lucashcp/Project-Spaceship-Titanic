# Projeto Spaceship Titanic

## Contexto

Este projeto tem por função a partir de um cenário ficticio onde uma nave está transportando diversos passageiros prever quais destes passageiros foram transportados para uma dimensão alternativa com base nos dados de cada passageiro, isto deve ser feito treinando um modelo e a partir deste modelo tentando realizar tal previsão posteriormente.

## Objetivo

Colocar em pratica um modelo de previsão funcional com base em uma situação fictícia proposta.


## Créditos 

As bases de dados foram retiradas do site kaggle: https://www.kaggle.com/competitions/spaceship-titanic/overview

Os dados estão dispostos nas seguintes colunas:

- PassengerId - Um Id único para cada passageiro. Cada Id segue o formato gggg_pp, onde gggg indica um grupo com o qual o passageiro está viajando e pp é o número dele dentro do grupo. As pessoas em um grupo geralmente são membros da família, mas nem sempre.
 
- HomePlanet - O planeta de onde o passageiro partiu, normalmente o planeta de residência permanente.

- CryoSleep - Indica se o passageiro optou por entrar em animação suspensa durante a duração da viagem. Os passageiros em criossono estão confinados às suas cabines.

- Cabin - O número da cabine onde o passageiro está hospedado. Segue o formato deck/num/side, onde side pode ser P para boreste ou S para estibordo.

- Destination - O planeta para o qual o passageiro vai desembarcar.

- Age - A idade do passageiro.

- VIP - Se o passageiro pagou por um serviço VIP especial durante a viagem.
 
- RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Valor que o passageiro gastou em cada uma das várias comodidades de luxo da Spaceship Titanic.

- Name - O nome e sobrenome do passageiro.

- Transported - Se o passageiro foi transportado para outra dimensão. Esse é o alvo, a coluna que você está tentando prever.
Transported - Se o passageiro foi transportado para outra dimensão. Esse é o alvo, a coluna que você está tentando prever.
