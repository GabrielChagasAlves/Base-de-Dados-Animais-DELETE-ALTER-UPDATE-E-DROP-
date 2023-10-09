# Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-
# # Exercicio com objetivo de mostrar diversas operações feitas em uma tabela de banco de dados, como alteração de nomes, inclusao de colunas de especie, alteração de cor de animais e etc..

## 1- Altere o nome do Pateta para Goofy:
#### Update animais set nome = 'Goofy' where id = 15
![Altere o nome do Pateta para Goofy;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/10458ebd-1a31-40c2-b479-29f8d7bf4ecc)
### alteração de nome do animal da tabela

## 2- Altere o peso do Garfield para 10 quilogramas:
#### update animais set peso  = 10.00 where id = 4
![Altere o peso do Garfield para 10 quilogramas;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/4fc08f4f-d839-433a-b119-125ea14bd748)
### Aqui fizemos a mudança do peso do animal

## 3- Crie um campo altura para os animais:
#### alter table add altura decimal (9,2)
![Crie um campo altura para os animais;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/2a0679af-3002-4eff-ac62-e612a820b859)
### Nesse caso foi incluido na tabela a coluna altura

## 4- Crie um campo observação para os animais:
#### alter table animais add observação varchar (200)
![Crie um campo observação para os animais;](https://github.com/GabrielChagasAlves/Base-de-Dados-Animais-DELETE-ALTER-UPDATE-E-DROP-/assets/125607847/0ffb56a3-625f-4890-833d-c948fc1a7add)
### Aqui foi incluido a coluna observação para mostrar mais sobre os animais

## Remova todos os animais que pesam mais que 200 quilogramas:
#### delete from animais where peso > 50
![Uploading Remova todos os animais que pesam mais que 200 quilogramas..PNG…]()


